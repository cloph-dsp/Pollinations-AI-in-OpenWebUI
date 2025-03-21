# How to Add **Pollinations AI Text Models** to **OpenWebUI**  
_Access top language models for free_

## What is Pollinations AI?

[Pollinations AI](https://pollinations.ai) offers free, easy-to-use text and image generation APIs. No signups or API keys required, with zero data storage and completely anonymous usage. Access powerful models like **GPT-4o**, **Mistral**, **Claude**, and **Gemini** instantly.

> **Note for Image Generation**: For image generation with Pollinations AI, install [this tool](https://openwebui.com/t/kaneki/image_generation) in OpenWebUI.

## Quick Setup

### 1. In OpenWebUI, go to **Settings > Admin > Connections**
- Click **"Add Connection"** under OpenAI API connections

### 2. Configure as follows:
| Field | Value |
|-------|-------|
| **URL** | `https://text.pollinations.ai/openai` |
| **Key** | `dummy-key` (any text works) |
| **Model IDs** | Add models from the list below |

### 3. Click **"Save"** to add the models to OpenWebUI

## Available Models

| Model ID           | Description                          |
|--------------------|--------------------------------------|
| `openai-large`     | GPT-4o                               |
| `openai`           | GPT-4o-mini                         |
| `openai-reasoning` | o3-mini (Reasoning)                 |
| `searchgpt`        | SearchGPT (web search required)     |
| `mistral`          | Mistral 3.1 (Vision)                |
| `deepseek-r1`      | DeepSeek R1-Qwen (Reasoning)        |
| `deepseek-r1-llama`| DeepSeek R1-Llama 70B (Reasoning)   |
| `llama`            | Llama 3.3 70B                      |
| `llamalight`       | Llama 3.1 8B                       |
| `gemini`           | Gemini 2.0 Flash                   |
| `gemini-thinking`  | Gemini 2.0 Flash Thinking          |
| `qwen-coder`       | Qwen 2.5 Coder 32B                 |
| `claude`           | Claude 3.5 Haiku                   |
| `phi`              | Phi-4 Instruct                     |

> 📌 For the full model list, visit **[Pollinations Models](https://text.pollinations.ai/models)**. Note: Models like "unity" and "midijourney" are for niche use cases, and some DeepSeek models may return errors.

<details>
<summary>Connection example</summary>

![Connection Example](pollinations_connection.jpg)
</details>

## Support the Project
If you find this useful, consider sponsoring Pollinations:  
👉 **https://github.com/pollinations/pollinations**

Your support helps keep AI free and accessible to all.
