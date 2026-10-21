# Awesome-Foundation-LLM-Models

## Top Foundation LLM Models Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Frontier Model Access, Open-Weight Releases & Self-Hosted Inference*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Foundation LLM Models**. These tools represent the base language models that power applications, agents, and research—ranging from proprietary frontier models accessible only via API to open-weight models that can be downloaded, fine-tuned, and self-hosted.



**Examples** include OpenAI GPT-5, Anthropic Claude Opus 4.7, Google Gemini 3 Deep Think, Microsoft Copilot, AWS Bedrock, Mistral Large 3, Cohere Command A, AI21 Jamba2, Perplexity, and Grok 4.5 (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active open-weight model family for self-hosting, fine-tuning, and transparent AI development—ideal for organizations that require data sovereignty, avoid vendor lock-in, and need auditable model behavior. The open-weight landscape is anchored by **Meta Llama 4** (flagship MoE with 1M context), **Mistral Large 3** (675B parameter enterprise model with Apache 2.0 licensing) , **AI21 Jamba2** (hybrid SSM-Transformer for enterprise reliability) , and **Cohere Command A** (agentic reasoning with 256K context) , with **DeepSeek**, **Qwen**, and **Gemma** providing strong alternatives across size classes.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[OpenAI GPT-5](https://openai.com/)**  

  OpenAI's flagship multimodal model family, launched August 2025 and iterated through GPT-5.6 by July 2026 . Features automatic routing between fast and deep reasoning modes, a million-token context window in GPT-5.4 Thinking, and built-in computer use. Proprietary and API-only.



- **[Anthropic Claude Opus 4.7](https://www.anthropic.com/)**  

  Anthropic's most capable model as of April 2026, with significant gains in agentic coding (CursorBench 70%+), tool-call reliability, and computer-use accuracy (98.5% on XBOW's visual-acuity benchmark vs. 54.5% for Opus 4.6) . Claude Sonnet 4.6 offers a 1M-token context window in beta . Proprietary.



- **[Google Gemini 3 Deep Think](https://deepmind.google/technologies/gemini/)**  

  Google's specialized reasoning mode for scientific and engineering problems. Achieves 48.4% on Humanity's Last Exam (no tools), 84.6% on ARC-AGI-2, and 95.4% on LiveCodeBench . Available to Google AI Ultra subscribers and via API early access. Proprietary.



- **[Microsoft Copilot](https://copilot.microsoft.com/)**  

  Microsoft's AI assistant built on OpenAI models, integrated across Windows, Office, and Edge. Offers enterprise data protection and Graph integration for organizational context.



- **[AWS Bedrock](https://aws.amazon.com/bedrock/)**  

  Managed service providing API access to multiple foundation models (Anthropic Claude, Meta Llama, Mistral, Cohere, AI21, and Amazon Titan) through a single interface. Best for AWS-native architectures requiring multi-model access.



- **[Mistral Large 3 (API)](https://mistral.ai/)**  

  Mistral's 675B parameter flagship model, available via API and NVIDIA NIM. Optimized for FP8 on 8xH200 or NVFP4 on H100/A100, with 256K context and native function calling . The model itself is open-weight (see below).



- **[Cohere Command A](https://cohere.com/)**  

  Cohere's flagship 111B parameter model for enterprise reasoning and agentic workflows. Command A Reasoning (August 2025) offers a 256K context window, 23-language reasoning, and ReAct agent support . Available via Cohere API and OCI Generative AI.



- **[AI21 Labs Jamba](https://www.ai21.com/)**  

  Jamba2 family (January 2026) with hybrid Mamba-Transformer architecture, 256K context, and 3B dense plus 52B/12A MoE variants . Enterprise-focused with private cloud and on-prem deployment options. API pricing: Jamba Mini $0.20/$0.40 per 1M tokens; Jamba Large $2/$8 per 1M tokens .



- **[Perplexity Pro](https://www.perplexity.ai/)**  

  AI-powered search and answer engine with access to multiple frontier models. Real-time web grounding with citations. Best for research workflows requiring up-to-date information.



- **[Grok 4.5](https://x.ai/)**  

  xAI's flagship model (July 2026) with 500K context window, multimodal vision, and real-time web search. API pricing at $2/$6 per 1M tokens (input/output) . Proprietary.



## Open-Source GitHub Projects



- **[Meta Llama 4 (Maverick)](https://github.com/meta-llama/llama-models)**  

  Meta's flagship open-weight MoE model with 17B active / 400B total parameters, 1M context window, native vision, and tool-use capabilities. Released April 2026 under the Llama 4 Community License . **Deployment requirements**: FP8 production default needs 4x H200; AWQ INT4 fits on 2x H100-80GB; GGUF Q4 runs on a single B200 . Best for organizations with multi-GPU capacity that need a capable, open-weight flagship model.



- **[Mistral Large 3](https://huggingface.co/mistralai/Mistral-Large-3-675B-Instruct-2512)**  

  Mistral's 675B parameter open-weight model under Apache 2.0 . Optimized for NVIDIA B200/H200 with FP8 (single 8xH200 node) or NVFP4 for H100/A100 . 256K context, native function calling, vision support, and best-in-class agentic capabilities. **Deployment**: vLLM with `--tensor-parallel-size 8` is the recommended serving path; speculative decoding via the Eagle draft model improves throughput . Best for enterprises that need a frontier-class open-weight model with permissive licensing.



- **[AI21 Jamba2](https://huggingface.co/ai21labs)**  

  Open-weight (Apache 2.0) hybrid SSM-Transformer model family in 3B dense and 52B/12A MoE variants . 256K context window. The 3B model can run on iPhones, Androids, Macs, and PCs—enabling truly local enterprise deployment. Leads on instruction-following (IFBench, IFEval, Collie) and grounding (FACTS) benchmarks, with statistically significant human-eval preference over Ministral3 14B on enterprise tasks . Best for enterprises that need reliable, steerable models without reasoning-model overhead.



- **[Cohere Command A](https://huggingface.co/CohereLabs)**  

  Cohere's 111B parameter model available via Hugging Face and OCI. 256K context, multimodal (text + images), 23-language reasoning, ReAct agent support, and built-in grounding citations . Can run on one or two GPUs with a four-layer transformer architecture using hybrid attention (sliding window + global) . Best for agentic enterprise workflows requiring multilingual support and tool use.



- **[DeepSeek-V3 / R1](https://github.com/deepseek-ai/DeepSeek-V3)**  

  Chinese open-weight models with strong reasoning and coding performance. DeepSeek-R1 demonstrated that reasoning capabilities can be distilled into open models at lower cost. MIT licensed for many releases. Best for teams exploring reasoning-model architectures without API dependency.



- **[Qwen 2.5 / Qwen3](https://github.com/QwenLM/Qwen2.5)**  

  Alibaba's open-weight model family from 0.5B to 72B+ parameters. Strong multilingual and coding performance. Apache 2.0 licensed. Best for teams that need a range of model sizes from edge to server deployment.



- **[Google Gemma 3 / 4](https://github.com/google-deepmind/gemma)**  

  Google's open-weight models designed for responsible AI development. Gemma 4 (E2B/E4B) targets edge deployment with LiteRT-LM. Apache 2.0 licensed. Best for mobile and edge inference within the Google ecosystem.



### Additional Strong Open-Source Options



- **Microsoft Phi-4** — Small language model family (14B and smaller) emphasizing reasoning capability at compact sizes. MIT licensed. Best for Windows edge deployment and resource-constrained environments.

- **OLMo (Allen AI)** — Fully open model family with training data, code, and logs released alongside weights. Best for research requiring complete reproducibility.

- **Frameworks for building custom systems**: Use **Llama 4** or **Mistral Large 3** as the foundation for high-capability applications requiring multi-GPU infrastructure. Deploy **Jamba2 3B** for local/edge enterprise QA. Serve **Command A** via vLLM for agentic workflows with grounding citations. Combine with **Ollama** or **vLLM** for inference serving and **LangChain** or **LlamaIndex** for application orchestration.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- "Open-source" for LLMs typically means **open-weight**, not open-source in the OSI sense—training data and code are rarely released in full.

- License terms vary significantly: Apache 2.0 (Mistral, Jamba2) allows unrestricted commercial use, while Llama 4 Community License and Gemma have usage restrictions. Verify before commercial deployment.

- Open-weight models require substantial GPU infrastructure; deployment costs (H200/B200 nodes) may exceed API pricing for low-volume use cases .



---



**Made for AI engineers, researchers, ML platform teams, and organizations building on foundation models.**  

Let's make foundation LLMs more open, accessible, and transparent.
