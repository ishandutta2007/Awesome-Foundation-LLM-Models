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

| Platform / Model | Description | Starting Tier Pricing | Free Tier Limits |
| :--- | :--- | :--- | :--- |
| **[OpenAI GPT-5](https://openai.com/)** | OpenAI's flagship multimodal model family with automatic routing between fast and deep reasoning modes, 1M context window in Thinking variants, and built-in computer use. | Consumer: $20/mo (ChatGPT Plus); API starting at $1.25 / 1M input tokens, $10.00 / 1M output tokens (GPT-5 series) | Free forever plan: Unlimited standard text chats (dynamic model fallback); rolling quota of up to 10-16 messages per 3 hours on advanced models, limited web search, file analysis, and 2 image generations per day. |
| **[Anthropic Claude Opus 4.7](https://www.anthropic.com/)** | Anthropic's flagship model specialized for complex reasoning, agentic coding, computer use, and long-form analysis with 1M context beta support. | Consumer: $20/mo (Claude Pro); API starting at $5.00 / 1M input tokens, $25.00 / 1M output tokens (Opus series) | Free forever plan: Dynamic message quota (typically ~10–30 messages per 5-hour rolling window depending on demand and prompt length) using standard Claude models; 5 artifacts/projects max. |
| **[Google Gemini 3 Deep Think](https://deepmind.google/technologies/gemini/)** | Google's specialized reasoning mode for scientific and engineering problem solving with native multimodality and live code execution. | Consumer: $19.99/mo (Google AI Pro); API starting at $1.25 / 1M input tokens, $5.00 / 1M output tokens (Gemini Pro/Flash variants) | Free forever plan: Full access to Gemini base web app with up to 60 queries/hour on standard models; Google AI Studio API free tier allows 15 RPM (requests per min), 1M TPM, and 1,500 requests/day. |
| **[Microsoft Copilot](https://copilot.microsoft.com/)** | Microsoft's enterprise-grade AI assistant built on OpenAI models, integrated across Microsoft 365, Windows, and Edge with commercial data protection. | Consumer/Pro: $19.99/mo (Microsoft 365 Premium / Copilot Pro) or $30/user/mo (M365 Copilot Enterprise) | Free forever plan: Unlimited basic chat and search grounding on web/mobile/Edge; capped at 15 DALL-E / Designer fast image boosts per day; no M365 desktop app integration. |
| **[AWS Bedrock](https://aws.amazon.com/bedrock/)** | Fully managed AWS service offering unified API access to foundation models from Anthropic, Meta, Mistral, Cohere, AI21, and Amazon Titan. | Pay-as-you-go starting at $0.00015 / 1K input tokens ($0.15 / 1M tokens on Amazon Nova Micro) | Free trial plan: No permanent free tier; new AWS accounts receive a $200 promotional credit valid for up to 6 months (180 days) applicable across Bedrock foundation model inference. |
| **[Mistral Large 3 (API)](https://mistral.ai/)** | Mistral's 675B parameter flagship model available via La Plateforme API and NVIDIA NIM, optimized for FP8/NVFP4 inference with 256K context. | Pay-as-you-go starting at $2.00 / 1M input tokens, $6.00 / 1M output tokens (Mistral Large) | Free forever plan: "Experiment" evaluation tier on La Plateforme with $0 payment required; strictly rate-limited to 1 request per second (RPS) and up to ~1B monthly tokens across evaluation endpoints. |
| **[Cohere Command A](https://cohere.com/)** | Cohere's 111B parameter enterprise model family built for multi-step agentic workflows, multilingual reasoning (23 languages), and grounded citations. | Pay-as-you-go starting at $0.40 / 1M input tokens, $1.60 / 1M output tokens (Command A) | Free forever plan: Evaluation Trial Key provides up to 1,000 API calls per month total across all endpoints, capped at 20 requests per minute (RPM) for Command chat models (strictly non-production). |
| **[AI21 Labs Jamba](https://www.ai21.com/)** | Hybrid SSM-Transformer architecture with 256K context, offering Jamba Mini ($0.20/$0.40 per 1M tokens) and Jamba Large ($2.00/$8.00 per 1M tokens). | Pay-as-you-go starting at $0.20 / 1M input tokens, $0.40 / 1M output tokens (Jamba Mini) | Free trial plan: $10.00 USD in free platform credits upon account creation, valid for 90 days (3 months) without requiring a credit card. |
| **[Perplexity Pro](https://www.perplexity.ai/)** | AI-powered conversational search engine providing real-time web citations, multi-file uploads, and multi-model access across leading frontier LLMs. | Pro plan: $20/mo (or $200/year billed annually) | Free forever plan: Unlimited standard search queries; 3 Pro Searches (deep research / multi-step reasoning) every 24 hours; 1 Deep Research query per month; up to 3 file uploads/day. |
| **[Grok 4.5](https://x.ai/)** | xAI's flagship model featuring 500K context, multimodal vision, real-time X data access, and deep reasoning capabilities. | Consumer: $8/mo (X Basic/Plus) or $30/mo (X Premium+); API pay-as-you-go starting at $2.00 / 1M input tokens, $6.00 / 1M output tokens | Free forever plan: Free web/mobile chat with dynamic quota (typically 10-20 queries per 2 hours on Grok 2/3 variants); API console grants a one-time $25 promotional credit valid for 30 days upon registration. |

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
