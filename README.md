---
layout: default
title: 首页
nav_order: 1
permalink: /
---

# AI Provider List
{: .fs-9 }

一个全面的 AI 模型供应商列表，帮助开发者快速了解和选择合适的 AI 服务。
{: .fs-6 .fw-300 }

[开始使用](#支持的供应商){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }
[GitHub](https://github.com/getofferhelp/ai-provider-list){: .btn .fs-5 .mb-4 .mb-md-0 }

---

![GitHub last commit](https://img.shields.io/github/last-commit/getofferhelp/ai-provider-list)
![GitHub](https://img.shields.io/github/license/getofferhelp/ai-provider-list)

## 📊 供应商概览
{: .d-inline-block }

New
{: .label .label-green }

下面列出了目前支持的 AI 服务供应商及其模型数量统计。最后更新时间：2025-02-27
{: .fs-5 }

| 供应商 | 模型数量 | 最大上下文窗口 | 最低价格(输入/输出) |
| :--- | :---: | :---: | :--- |
| **Claude** | 3 | 200,000 | $3000.00/1M - $15000.00/1M |
| **DeepSeek** | 2 | 32,000 | $100.00/1M - $200.00/1M |
| **Gemini** | 4 | 32,000 | $250.00/1M - $500.00/1M |
| **Groq** | 15 | 128,000 | $40.00/1M - $40.00/1M |
| **Grok** | 1 | 8,192 | $200.00/1M - $200.00/1M |
| **Kimi** | 3 | 131,072 | $100.00/1M - $100.00/1M |
| **Mistral** | 3 | 32,000 | $200.00/1M - $600.00/1M |
| **OpenAI** | 4 | 128,000 | $500.00/1M - $1500.00/1M |
| **Qwen** | 4 | 150,000 | $200.00/1M - $200.00/1M |
{: .table-responsive }

## 📑 详细供应商信息

## Claude
- API接口: `https://api.anthropic.com/v1/messages`
- API密钥获取: [点击这里](https://console.anthropic.com/account/keys)


### Claude 3.5 Opus
- 模型ID: `claude-3-5-opus-20240229`
- 上下文窗口: 200,000 tokens
- 价格:
  - 输入: $15000.00/1M tokens
  - 输出: $75000.00/1M tokens


### Claude 3.5 Sonnet
- 模型ID: `claude-3-5-sonnet-20240229`
- 上下文窗口: 200,000 tokens
- 价格:
  - 输入: $3000.00/1M tokens
  - 输出: $15000.00/1M tokens


### Claude 3.7 Sonnet
- 模型ID: `claude-3-7-sonnet`
- 上下文窗口: 100,000 tokens
- 价格:
  - 输入: $8000.00/1M tokens
  - 输出: $24000.00/1M tokens

---

## DeepSeek
- API接口: `https://api.deepseek.com/v1/chat/completions`
- API密钥获取: [点击这里](https://platform.deepseek.com/settings)


### DeepSeek Chat
- 模型ID: `deepseek-chat`
- 上下文窗口: 32,000 tokens
- 价格:
  - 输入: $200.00/1M tokens
  - 输出: $2000.00/1M tokens


### DeepSeek R1
- 模型ID: `deepseek-r1`
- 上下文窗口: 32,000 tokens
- 价格:
  - 输入: $100.00/1M tokens
  - 输出: $200.00/1M tokens

---

## Gemini
- API接口: `https://generativelanguage.googleapis.com/v1/models`
- API密钥获取: [点击这里](https://makersuite.google.com/app/apikey)


### Gemini 1.5 Pro
- 模型ID: `gemini-1.5-pro`
- 上下文窗口: 32,000 tokens
- 价格:
  - 输入: $250.00/1M tokens
  - 输出: $500.00/1M tokens


### Gemini 1.5 Pro Vision
- 模型ID: `gemini-1.5-pro-vision`
- 上下文窗口: 32,000 tokens
- 价格:
  - 输入: $250.00/1M tokens
  - 输出: $500.00/1M tokens


### Gemini 1.5 Ultra
- 模型ID: `gemini-1.5-ultra`
- 上下文窗口: 32,000 tokens
- 价格:
  - 输入: $1000.00/1M tokens
  - 输出: $2000.00/1M tokens


### Gemini 2.0 Pro
- 模型ID: `gemini-2.0-pro`
- 上下文窗口: 32,000 tokens
- 价格:
  - 输入: $250.00/1M tokens
  - 输出: $500.00/1M tokens

---

## Groq
- API接口: `https://api.groq.com/v1/chat/completions`
- API密钥获取: [点击这里](https://console.groq.com/keys)


### DeepSeek R1 Distill LLaMA 70B
- 模型ID: `deepseek-r1-distill-llama-70b`
- 上下文窗口: 8,192 tokens
- 价格:
  - 输入: $750.00/1M tokens
  - 输出: $990.00/1M tokens


### DeepSeek R1 Distill Qwen 32B
- 模型ID: `deepseek-r1-distill-qwen-32b`
- 上下文窗口: 128,000 tokens
- 价格:
  - 输入: $690.00/1M tokens
  - 输出: $690.00/1M tokens


### Qwen 2.5 32B Instruct
- 模型ID: `qwen-2.5-32b-instruct`
- 上下文窗口: 128,000 tokens
- 价格:
  - 输入: $790.00/1M tokens
  - 输出: $790.00/1M tokens


### Qwen 2.5 Coder 32B Instruct
- 模型ID: `qwen-2.5-coder-32b-instruct`
- 上下文窗口: 128,000 tokens
- 价格:
  - 输入: $790.00/1M tokens
  - 输出: $790.00/1M tokens


### Mistral Saba 24B
- 模型ID: `mistral-saba-24b`
- 上下文窗口: 8,192 tokens
- 价格:
  - 输入: $790.00/1M tokens
  - 输出: $790.00/1M tokens


### LLaMA 3.2 1B
- 模型ID: `llama-3.2-1b`
- 上下文窗口: 8,192 tokens
- 价格:
  - 输入: $40.00/1M tokens
  - 输出: $40.00/1M tokens


### LLaMA 3.2 3B
- 模型ID: `llama-3.2-3b`
- 上下文窗口: 8,192 tokens
- 价格:
  - 输入: $60.00/1M tokens
  - 输出: $60.00/1M tokens


### LLaMA 3.3 70B Versatile
- 模型ID: `llama-3.3-70b-versatile`
- 上下文窗口: 128,000 tokens
- 价格:
  - 输入: $590.00/1M tokens
  - 输出: $790.00/1M tokens


### LLaMA 3.1 8B Instant
- 模型ID: `llama-3.1-8b-instant`
- 上下文窗口: 128,000 tokens
- 价格:
  - 输入: $50.00/1M tokens
  - 输出: $80.00/1M tokens


### LLaMA 3 70B
- 模型ID: `llama-3-70b`
- 上下文窗口: 8,192 tokens
- 价格:
  - 输入: $590.00/1M tokens
  - 输出: $790.00/1M tokens


### LLaMA 3 8B
- 模型ID: `llama-3-8b`
- 上下文窗口: 8,192 tokens
- 价格:
  - 输入: $50.00/1M tokens
  - 输出: $80.00/1M tokens


### Mixtral 8x7B
- 模型ID: `mixtral-8x7b-32768`
- 上下文窗口: 32,768 tokens
- 价格:
  - 输入: $240.00/1M tokens
  - 输出: $240.00/1M tokens


### Gemma 2 9B
- 模型ID: `gemma2-9b-it`
- 上下文窗口: 8,192 tokens
- 价格:
  - 输入: $200.00/1M tokens
  - 输出: $200.00/1M tokens


### LLaMA Guard 3 8B
- 模型ID: `llama-guard-3-8b`
- 上下文窗口: 8,192 tokens
- 价格:
  - 输入: $200.00/1M tokens
  - 输出: $200.00/1M tokens


### LLaMA 3.3 70B SpecDec
- 模型ID: `llama-3.3-70b-specdec`
- 上下文窗口: 8,192 tokens
- 价格:
  - 输入: $590.00/1M tokens
  - 输出: $990.00/1M tokens

---

## Grok
- API接口: `https://api.grok.x.ai/v1/chat/completions`
- API密钥获取: [点击这里](https://grok.x.ai)


### Grok-1
- 模型ID: `grok-1`
- 上下文窗口: 8,192 tokens
- 价格:
  - 输入: $200.00/1M tokens
  - 输出: $200.00/1M tokens

---

## Kimi
- API接口: `https://api.moonshot.cn/v1/chat/completions`
- API密钥获取: [点击这里](https://platform.moonshot.cn/console/api-keys)


### Moonshot V1 8K
- 模型ID: `moonshot-v1-8k`
- 上下文窗口: 8,192 tokens
- 价格:
  - 输入: $100.00/1M tokens
  - 输出: $100.00/1M tokens


### Moonshot V1 32K
- 模型ID: `moonshot-v1-32k`
- 上下文窗口: 32,768 tokens
- 价格:
  - 输入: $200.00/1M tokens
  - 输出: $200.00/1M tokens


### Moonshot V1 128K
- 模型ID: `moonshot-v1-128k`
- 上下文窗口: 131,072 tokens
- 价格:
  - 输入: $400.00/1M tokens
  - 输出: $400.00/1M tokens

---

## Mistral
- API接口: `https://api.mistral.ai/v1/chat/completions`
- API密钥获取: [点击这里](https://console.mistral.ai/api-keys/)


### Mistral Tiny
- 模型ID: `mistral-tiny`
- 上下文窗口: 32,000 tokens
- 价格:
  - 输入: $200.00/1M tokens
  - 输出: $600.00/1M tokens


### Mistral Small
- 模型ID: `mistral-small`
- 上下文窗口: 32,000 tokens
- 价格:
  - 输入: $200.00/1M tokens
  - 输出: $2400.00/1M tokens


### Mistral Medium
- 模型ID: `mistral-medium`
- 上下文窗口: 32,000 tokens
- 价格:
  - 输入: $2700.00/1M tokens
  - 输出: $8700.00/1M tokens

---

## OpenAI
- API接口: `https://api.openai.com/v1/chat/completions`
- API密钥获取: [点击这里](https://platform.openai.com/api-keys)


### GPT-4 Turbo
- 模型ID: `gpt-4-turbo-preview`
- 上下文窗口: 128,000 tokens
- 价格:
  - 输入: $10000.00/1M tokens
  - 输出: $30000.00/1M tokens


### GPT-4 Vision
- 模型ID: `gpt-4-vision-preview`
- 上下文窗口: 128,000 tokens
- 价格:
  - 输入: $10000.00/1M tokens
  - 输出: $30000.00/1M tokens


### GPT-4
- 模型ID: `gpt-4`
- 上下文窗口: 8,192 tokens
- 价格:
  - 输入: $30000.00/1M tokens
  - 输出: $60000.00/1M tokens


### GPT-3.5 Turbo
- 模型ID: `gpt-3.5-turbo`
- 上下文窗口: 16,385 tokens
- 价格:
  - 输入: $500.00/1M tokens
  - 输出: $1500.00/1M tokens

---

## Qwen
- API接口: `https://dashscope.aliyuncs.com/api/v1/services/aigc/text-generation/generation`
- API密钥获取: [点击这里](https://help.aliyun.com/zh/dashscope/developer-reference/activate-dashscope-and-create-an-api-key)


### Qwen Turbo
- 模型ID: `qwen-turbo`
- 上下文窗口: 6,000 tokens
- 价格:
  - 输入: $200.00/1M tokens
  - 输出: $200.00/1M tokens


### Qwen Plus
- 模型ID: `qwen-plus`
- 上下文窗口: 30,000 tokens
- 价格:
  - 输入: $1000.00/1M tokens
  - 输出: $1000.00/1M tokens


### Qwen Max
- 模型ID: `qwen-max`
- 上下文窗口: 30,000 tokens
- 价格:
  - 输入: $2000.00/1M tokens
  - 输出: $2000.00/1M tokens


### Qwen Max Long Context
- 模型ID: `qwen-max-longcontext`
- 上下文窗口: 150,000 tokens
- 价格:
  - 输入: $2000.00/1M tokens
  - 输出: $2000.00/1M tokens

---


## 🌟 特点

- 实时更新的供应商和模型信息
- 详细的价格和性能参数
- 直观的API接口信息
- 完整的模型规格说明
- 开源维护，社区驱动

## 💡 选择建议

- **高性能需求**: 推荐使用 Claude 3 Opus、GPT-4等大型模型
- **性价比之选**: Mistral、Moonshot等价格较低的模型
- **长文本处理**: 选择 Claude 3系列、GPT-4 Turbo等大上下文窗口模型
- **成本敏感**: 可以考虑 DeepSeek、Moonshot等较经济的选择

## 🤝 如何贡献
{: .d-inline-block }

Contributing
{: .label .label-purple }

我们欢迎任何形式的贡献！参与方式：

1. Fork 本仓库
2. 更新 `data/providers.json`
3. 提交 Pull Request

## 📝 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件

## 📬 联系我们

如有问题或建议，欢迎：
{: .fs-5 }

[提交 Issue](https://github.com/getofferhelp/ai-provider-list/issues){: .btn .btn-blue }
[发起 Pull Request](https://github.com/getofferhelp/ai-provider-list/pulls){: .btn .btn-green }
