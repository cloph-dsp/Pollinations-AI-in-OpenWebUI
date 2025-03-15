# How to Add **Pollinations AI Models** to **OpenWebUI**  
_Access top language models for free_

## What is Pollinations AI?

[Pollinations AI](https://pollinations.ai) offers free API access to powerful language models like **GPT-4o**, **Mistral**, **Claude**, **Gemini**, **DeepSeek**, **LLaMA**, and more — no API key or billing required.

This guide shows how to connect Pollinations AI to **OpenWebUI** for instant access to these models.

---

## Setup in OpenWebUI

### 1. Go to **Settings > Connections**

- Click **“Add Connection”** or edit an existing one.

### 2. Configure the connection:

| Field        | Value                                       |
|--------------|---------------------------------------------|
| **URL**      | `https://text.pollinations.ai/openai`       |
| **Key**      | `dummy-key` (any text works; not validated) |
| **Model IDs**| Add one or more model names (see below)     |

---

### Example Configuration Screen

![Pollinations AI Connection Example](pollinations-connection-example.png)

---

## Available Model IDs

You can add any of the following models:

| Model ID              | Description                              |
|-----------------------|-------------------------------------------|
| `openai-large`        | GPT-4o                                    |
| `openai`              | GPT-4o-mini                               |
| `openai-reasoning`    | o3-mini                                   |
| `searchgpt`           | SearchGPT (web search is required)        |
| `mistral`             | Mistral                                   |
| `deepseek-reasoner`   | DeepSeek R1                               |
| `deepseek-r1`         | DeepSeek R1-Qwen                          |
| `deepseek-r1-llama`   | DeepSeek R1-Llama                         |
| `deepseek`            | DeepSeek-V3                               |
| `llama`               | Llama 3.3                                 |
| `llamalight`          | Llama 3.1                                 |
| `gemini`              | Gemini 2.0                                |
| `qwen-coder`          | Qwen 2.5 Coder                            |
| `claude`              | Claude 3.5 Haiku                          |
| `phi`                 | Phi-4                                     |

> 📌 You can always check the full model list at:  
**https://text.pollinations.ai/models**

---

## 3. Save and use

Click **“Save”** — the models will now be available in the OpenWebUI interface.

---

## Support the Project

If you find this useful, consider sponsoring the Pollinations team:  
👉 **https://github.com/pollinations/pollinations**

Your support helps keep AI free, open, and accessible to all.
