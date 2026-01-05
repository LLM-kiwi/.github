<div align="center">

# 🥝 LLM.kiwi

### One API. All AI Models. Fixed Price.

[![Website](https://img.shields.io/badge/Website-llm.kiwi-97CF43?style=for-the-badge&logo=safari&logoColor=white)](https://llm.kiwi)
[![Documentation](https://img.shields.io/badge/Docs-API%20Reference-365C3C?style=for-the-badge&logo=readthedocs&logoColor=white)](https://llm.kiwi/docs)
[![Status](https://img.shields.io/badge/Status-Operational-97CF43?style=for-the-badge&logo=statuspage&logoColor=white)](https://llm.kiwi/uptime)

<br />

**Access 15+ leading AI models through a single unified API.**  
**€20/month flat rate. No token counting. No surprise bills.**

<br />

[🚀 Get Started](https://llm.kiwi/dashboard) · [📖 Documentation](https://llm.kiwi/docs) · [💬 Contact Us](https://llm.kiwi/contact)

</div>

---

## ✨ Why LLM.kiwi?

| Feature | Description |
|---------|-------------|
| 🔗 **One API** | Single endpoint for OpenAI, Google, DeepSeek, Mistral, and Meta models |
| 💰 **Fixed Pricing** | €20/month flat — no per-token billing, ever |
| ⚡ **OpenAI Compatible** | Drop-in replacement — just change your base URL |
| 🚀 **High Performance** | Low latency, generous rate limits (25 req/s) |
| 🆓 **Free Tier** | Get started with 60 requests/hour at no cost |

---

## 🤖 Supported Models

<table>
<tr>
<td align="center"><strong>OpenAI</strong><br/>GPT-4, GPT-4.1, GPT-5-mini</td>
<td align="center"><strong>Google</strong><br/>Gemini 2.5 Flash, Gemini Search</td>
<td align="center"><strong>DeepSeek</strong><br/>DeepSeek V3.1</td>
</tr>
<tr>
<td align="center"><strong>Mistral</strong><br/>Mistral Small, Codestral</td>
<td align="center"><strong>Meta</strong><br/>Llama 3.1 8B Turbo</td>
<td align="center"><strong>And More</strong><br/>Whisper, FLUX, GLM-4.5</td>
</tr>
</table>

---

## 🔧 Quick Start

### 1. Get Your API Key
Sign up at [llm.kiwi/dashboard](https://llm.kiwi/dashboard) to get your free API key.

### 2. Make Your First Request

```bash
curl https://api.llm.kiwi/v1/chat/completions \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -d '{
    "model": "default",
    "messages": [{"role": "user", "content": "Hello!"}]
  }'
```

### 3. Use with Your Favorite SDK

```python
from openai import OpenAI

client = OpenAI(
    base_url="https://api.llm.kiwi/v1",
    api_key="YOUR_API_KEY"
)

response = client.chat.completions.create(
    model="default",
    messages=[{"role": "user", "content": "Hello!"}]
)
```

---

## 📚 Documentation

| Resource | Description |
|----------|-------------|
| [Getting Started](https://llm.kiwi/docs/getting-started) | Quick setup guide |
| [API Reference](https://llm.kiwi/docs/chat-completions) | Full endpoint documentation |
| [Models](https://llm.kiwi/docs/models) | Complete list of available models |
| [Free Tier](https://llm.kiwi/docs/free-tier) | Free tier limits and usage |
| [Rate Limits](https://llm.kiwi/docs/rate-limits) | Understand rate limiting |
| [IDE Integration](https://llm.kiwi/docs/ide-agents) | Cursor, VS Code, Windsurf guides |

---

## 🛠️ Products & Apps

| App | Description | Link |
|-----|-------------|------|
| 🥝 **Promptich** | AI-powered prompt expander for web dev, images, video & more | [promptich.llm.kiwi](https://promptich.llm.kiwi) |

> Building with LLM.kiwi? [Submit your project](https://llm.kiwi/contact) to be featured!

---

## 💳 Pricing

| Plan | Price | Features |
|------|-------|----------|
| **Free** | $0 | 60 req/hour, 8K chars/request, API key required |
| **Pro** | €20/mo | Unlimited tokens, 25 req/s, all models, priority support |

[View full pricing details →](https://llm.kiwi/pricing)

---

## 🔗 Links

<div align="center">

| Website | Docs | Pricing | Showcase | Status |
|:-------:|:----:|:-------:|:--------:|:------:|
| [llm.kiwi](https://llm.kiwi) | [/docs](https://llm.kiwi/docs) | [/pricing](https://llm.kiwi/pricing) | [/showcase](https://llm.kiwi/showcase) | [/uptime](https://llm.kiwi/uptime) |

</div>

---

## 📫 Contact

- **Website:** [llm.kiwi](https://llm.kiwi)
- **Email:** hello@llm.kiwi
- **Contact Form:** [llm.kiwi/contact](https://llm.kiwi/contact)

---

## 📄 Legal

- [Privacy Policy](https://llm.kiwi/privacy)
- [Terms of Service](https://llm.kiwi/terms)
- [Cookie Policy](https://llm.kiwi/cookie-policy)
- [Responsible AI](https://llm.kiwi/responsible-ai)

---

<div align="center">

**Built with 💚 for developers**

© 2025 LLM.kiwi. All rights reserved.

</div>
