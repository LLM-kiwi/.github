![LLM.kiwi Hero Banner](https://user-images.githubusercontent.com/your-hero-image-link.png)

<div align="center">

# 🥝 LLM.kiwi

### Free LLM API. No Token Counting. One API for All Major AI Models.

[![Website](https://img.shields.io/badge/Website-llm.kiwi-97CF43?style=for-the-badge&logo=safari&logoColor=white)](https://llm.kiwi) 
[![Docs](https://img.shields.io/badge/Docs-API%20Reference-365C3C?style=for-the-badge&logo=readthedocs&logoColor=white)](https://docs.llm.kiwi) 
[![Status](https://img.shields.io/badge/Status-Operational-97CF43?style=for-the-badge&logo=statuspage&logoColor=white)](https://llm.kiwi/uptime)
[![Free Tier](https://img.shields.io/badge/Free%20Tier-60%20req%2Fhr-97CF43?style=for-the-badge)](https://docs.llm.kiwi/free-tier)

</div>

---

## ✨ Why Choose LLM.kiwi?

| Feature | Description |
|---------|-------------|
| 🔗 **One API** | Single endpoint for OpenAI, Google, DeepSeek, Mistral, Meta, and more |
| 💰 **Fixed Pricing** | €20/month flat — never pay per token |
| ⚡ **OpenAI Compatible** | Drop-in replacement: just change your base URL |
| 🚀 **High Performance** | Low latency, generous rate limits (25 req/s) |
| 🆓 **Free Tier** | Start for free with 60 requests/hour |

---

## 🤖 Supported AI Models

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

### 1️⃣ Get Your API Key
Sign up at [llm.kiwi/dashboard](https://llm.kiwi/dashboard) to get your free API key.

### 2️⃣ Make Your First Request

```bash
curl https://api.llm.kiwi/v1/chat/completions \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -d '{
    "model": "default",
    "messages": [{"role": "user", "content": "Hello!"}]
  }'
```

### 3️⃣ Use With Your Favorite SDK

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
| [Getting Started](https://docs.llm.kiwi/getting-started) | Quick setup guide |
| [API Reference](https://docs.llm.kiwi/chat-completions) | Full endpoint docs |
| [Models](https://docs.llm.kiwi/models) | Complete list of supported models |
| [Free Tier](https://docs.llm.kiwi/free-tier) | Free tier limits and usage |
| [Rate Limits](https://docs.llm.kiwi/rate-limits) | Request limits explained |
| [IDE Integration](https://docs.llm.kiwi/ide-agents) | VS Code, Cursor, Windsurf guides |

---

## 💳 Pricing Plans

| Plan | Price | Features |
|------|-------|----------|
| **Free** | $0 | 60 requests/hour, 8K chars/request, API key required |
| **Pro** | €20/mo | Unlimited tokens, 25 req/s, all models, priority support |

[View full pricing →](https://llm.kiwi/pricing)

---

## 🔗 Quick Links

<div align="center">

| Website | Docs | Pricing | Showcase | Status |
|:-------:|:----:|:-------:|:--------:|:------:|
| [llm.kiwi](https://llm.kiwi) | [docs.llm.kiwi](https://docs.llm.kiwi) | [/pricing](https://llm.kiwi/pricing) | [/showcase](https://llm.kiwi/showcase) | [/uptime](https://llm.kiwi/uptime) |

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
