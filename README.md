# Awesome Free AI APIs [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI APIs and developer services you can use for free: free tiers, free credits and free models.

Every entry links to the provider's official pricing or docs page. Free tiers change often, so check the linked page before you build on one.

## Contents

- [LLM and Chat Completion APIs](#llm-and-chat-completion-apis)
- [Embeddings and Reranking](#embeddings-and-reranking)
- [Code Models and Coding Assistants](#code-models-and-coding-assistants)
- [Search and Scraping APIs for Agents](#search-and-scraping-apis-for-agents)
- [Image Generation](#image-generation)
- [Video Generation](#video-generation)
<!-- toc-end -->

## LLM and Chat Completion APIs

- [Alibaba Cloud Model Studio](https://www.alibabacloud.com/help/en/model-studio/new-free-quota) - Qwen and other models through an OpenAI-compatible API. Free: new users get a per-model free quota (typically 1M tokens) valid for 90 days, Singapore region only.
- [Cerebras Inference](https://inference-docs.cerebras.ai/support/rate-limits) - Open-weight models such as gpt-oss-120b served on Cerebras hardware. Free: trial tier with $5 in credits that expire after 30 days, 5 RPM and 1M tokens per day.
- [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai/platform/pricing/) - Serverless inference for open models from Workers or a REST API. Free: 10,000 Neurons per day on Free and Paid Workers plans.
- [Cohere](https://cohere.com/pricing) - Command chat models plus embed and rerank endpoints. Free: trial API key, 20 chat requests per minute and 1,000 calls per month, not for production or commercial use.
- [Google Gemini API](https://ai.google.dev/gemini-api/docs/pricing) - Gemini Flash and Flash-Lite models through Google AI Studio. Free: free input and output tokens on selected models with rate limits shown in AI Studio; free-tier content may be used to improve Google products.
- [Groq](https://console.groq.com/docs/rate-limits) - Low-latency inference for open models, speech-to-text and TTS. Free: free plan with per-model limits on requests and tokens per minute and per day.
- [Hugging Face Inference Providers](https://huggingface.co/docs/inference-providers/pricing) - One API routing to many inference providers and hundreds of models. Free: $0.10 in monthly credits for free accounts, $2.00 for PRO.
- [Mistral AI](https://docs.mistral.ai/admin/user-management-finops/tier) - Mistral open and proprietary models through La Plateforme. Free: free mode with included monthly usage within the limits shown in the admin console.
- [NVIDIA NIM](https://developer.nvidia.com/nim) - Hosted NIM endpoints for open models on build.nvidia.com. Free: free API access for prototyping with an NVIDIA Developer Program membership.
- [OpenRouter](https://openrouter.ai/docs/api-reference/limits) - Unified API across many providers, including models with `:free` variants. Free: `:free` models at 20 requests per minute and 50 per day, or 1,000 per day after buying at least 10 credits.
- [SambaNova Cloud](https://docs.sambanova.ai/docs/en/models/rate-limits) - Open models such as DeepSeek, Llama and gpt-oss on SambaNova hardware. Free: tier without a payment method, 20 requests per minute, 20 per day and 200K tokens per day on selected models.
- [Scaleway Generative APIs](https://www.scaleway.com/en/pricing/model-as-a-service/) - OpenAI-compatible serverless API for open models hosted in Europe. Free: first 1,000,000 tokens.
- [SiliconFlow](https://www.siliconflow.com/pricing) - Pay-as-you-go API for open LLM, image and video models. Free: $1 in credits for new accounts.
- [Vercel AI Gateway](https://vercel.com/docs/ai-gateway/pricing) - One endpoint for models from many providers with no token markup. Free: monthly free credit on a subset of models, rate limited, until you purchase credits.
- [Z.ai](https://docs.z.ai/guides/overview/pricing) - GLM models through the Z.ai API. Free: GLM-4.7-Flash, GLM-4.5-Flash and GLM-4.6V-Flash are priced at $0.

## Embeddings and Reranking

- [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai/models/) - Hosted embedding models (BGE, EmbeddingGemma, Qwen3 Embedding) and the bge-reranker-base reranker. Free: 10,000 Neurons per day, shared with other Workers AI models.
- [Cohere](https://docs.cohere.com/docs/rate-limits) - Embed and Rerank endpoints. Free: trial key with 2,000 embed inputs per minute, 10 rerank requests per minute and 1,000 calls per month, not for production use.
- [Google Gemini Embedding](https://ai.google.dev/gemini-api/docs/pricing) - Multimodal embeddings for text, images, audio and video through the Gemini API. Free: free of charge on the free tier, with rate limits.
- [Hugging Face Inference Providers](https://huggingface.co/docs/inference-providers/pricing) - Feature extraction and text-ranking models, including CPU inference through hf-inference. Free: $0.10 in monthly credits for free accounts, $2.00 for PRO.
- [Jina AI](https://jina.ai/embeddings/) - Embeddings, reranker, classifier and segmenter APIs under one key. Free: every new API key includes 10M tokens shared across Jina APIs.
- [Pinecone Inference](https://www.pinecone.io/pricing/) - Hosted embedding and reranking models next to the Pinecone vector database. Free: Starter plan includes 5M embedding tokens and 500 rerank requests per month.
- [Voyage AI](https://docs.voyageai.com/docs/pricing) - Text, multilingual, domain and code embedding models plus rerankers. Free: first 200M tokens per account on voyage-4, voyage-4-large, voyage-4-lite, voyage-context-4 and voyage-code-3.

## Code Models and Coding Assistants

- [Amazon Q Developer](https://aws.amazon.com/q/developer/pricing/) - AWS coding assistant for the IDE and CLI with agentic tasks and Java upgrades. Free: 50 agentic requests and 1,000 lines of code transformation per month.
- [Cursor](https://cursor.com/pricing) - AI code editor with agent mode and the Composer model. Free: Hobby plan with limited agent requests, no credit card required.
- [GitHub Copilot](https://github.com/features/copilot/plans) - Code completion and chat in the editor and on GitHub. Free: 2,000 completions and 50 chat requests per month.
- [Inception](https://docs.inceptionlabs.ai/get-started) - Mercury diffusion language models for code and chat through an OpenAI-compatible API. Free: 100M tokens for each new account, no payment required.
- [Kiro](https://kiro.dev/pricing/) - Agentic IDE and CLI from AWS. Free: 50 credits with access to Claude Sonnet 4.5 and selected open-weight models such as Qwen3 Coder Next, rate limited.
- [Mistral Leanstral](https://mistral.ai/pricing/api/) - Code agent model for the Lean 4 proof language. Free: endpoint priced at $0 for a limited period.
- [Voyage AI Code Embeddings](https://docs.voyageai.com/docs/pricing) - voyage-code-3 embeddings for code search and retrieval. Free: first 200M tokens per account.

## Search and Scraping APIs for Agents

- [Apify](https://apify.com/pricing) - Platform for running scrapers and crawlers (Actors) through an API. Free: $5 in platform credit per month.
- [Brave Search API](https://brave.com/search/api/) - Web search results from Brave's independent index, plus an Answers plan. Free: $5 in credits every month.
- [Exa](https://exa.ai/pricing) - Search API built for LLMs, with content retrieval. Free: $20 in credits for new accounts, plus $10 in credits every month.
- [Firecrawl](https://www.firecrawl.dev/pricing) - Scrape, crawl and search the web into LLM-ready markdown or JSON. Free: 1,000 credits per month and 2 concurrent requests, no credit card.
- [Jina Reader](https://jina.ai/reader/) - Converts any URL to LLM-friendly text through r.jina.ai. Free: 20 RPM without a key, 500 RPM with a free key, and 10M tokens for each new key.
- [Linkup](https://www.linkup.so/pricing) - Web search, fetch and research API for AI apps. Free: 4,000 queries.
- [Parallel](https://parallel.ai/pricing) - Web search, extract and research APIs for AI agents. Free: up to 5,000 requests per month.
- [ScrapingBee](https://www.scrapingbee.com/pricing/) - Scraping API that handles headless browsers and proxies. Free: 1,000 API credits trial, no credit card.
- [SerpApi](https://serpapi.com/pricing) - Structured JSON results from Google and other search engines. Free: 250 searches per month.
- [Serper](https://serper.dev/) - Google Search results API covering web, images, news, maps and shopping. Free: 2,500 queries, no credit card.
- [Tavily](https://docs.tavily.com/documentation/api-credits) - Search and extract API built for AI agents and RAG. Free: 1,000 API credits per month, no credit card.

## Image Generation

- [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai/platform/pricing/) - Serverless inference with FLUX and Leonardo image models on Cloudflare's network. Free: 10,000 Neurons per day on both Free and Paid plans.
- [deAPI](https://deapi.ai/pricing) - Pay-as-you-go API for text-to-image and image-to-image with models such as FLUX.2 Klein. Free: $5 in credits on signup, no credit card required.
- [Hugging Face Inference Providers](https://huggingface.co/docs/inference-providers/pricing) - One API routing text-to-image requests to partner providers for models hosted on the Hub. Free: $0.10 in monthly credits for free accounts, $2.00 for PRO.
- [Photoroom API](https://www.photoroom.com/api/pricing) - Background removal and image editing API for product photos. Free: 1,000 watermarked sandbox calls per month on the Image Editing API and 10 production calls on the Remove Background API.
- [remove.bg](https://www.remove.bg/api) - Background removal API. Free: 50 API calls per month.
- [Runware](https://runware.ai/pricing) - Single API for image, video and audio generation models. Free: $2 in credits for new users.
- [Stability AI](https://platform.stability.ai/pricing) - API for Stable Diffusion image generation, editing and upscaling. Free: 25 credits for new accounts (1 credit = $0.01).

## Video Generation

- [deAPI](https://deapi.ai/pricing) - Pay-as-you-go API for text-to-video, image-to-video and video upscaling. Free: $5 in credits on signup, no credit card required.
- [Hugging Face Inference Providers](https://huggingface.co/docs/inference-providers/tasks/text-to-video) - One API routing text-to-video requests to partner providers such as fal and Replicate. Free: $0.10 in monthly credits for free accounts, $2.00 for PRO.
- [Magic Hour](https://magichour.ai/api/text-to-video) - API for text-to-video, image-to-video and other video generation endpoints. Free: credits on signup that work across all API endpoints, no credit card required.
- [Runware](https://runware.ai/pricing) - Single API for image, video and audio generation models. Free: $2 in credits for new users.
- [Tavus](https://www.tavus.io/pricing) - API for real-time conversational video with AI avatars. Free: 25 minutes of conversational video and 25 stock AI humans on the Basic plan.

## Contributing

Contributions are welcome. Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

---

Maintained by [Ali Hesari](https://alihesari.com). Follow on [GitHub](https://github.com/alihesari) and [X](https://x.com/alihesari) for updates.
