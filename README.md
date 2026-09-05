# ToolPort

<p align="center">
  Turn a Colab GPU into a tool-enabled LLM endpoint.
</p>

<p align="center">
  Run long-context GGUF models with <code>llama.cpp</code>, expose an OpenAI-compatible API, and connect browser tools through MCP.
</p>

<p align="center">
  <img src="docs/toolport-ui.png" alt="ToolPort UI" width="100%">
</p>

---

## What is ToolPort?

**ToolPort** is a lightweight setup for running LLMs on **Google Colab** with:

- **llama.cpp**
- **OpenAI-compatible API**
- **long context support**
- **Cloudflare public URL**

It gives you a simple way to turn a Colab runtime into a usable AI endpoint with tools.

---

## Highlights

- Run **GGUF models** on Colab
- OpenAI-compatible `/v1` API
- Automatic active-port detection
- Public HTTPS access with Cloudflare
- MCP support for tool use

---

## Project Structure

```text
ToolPort/
├── toolport_colab_qwen3_5_4b.ipynb
└── README.md
