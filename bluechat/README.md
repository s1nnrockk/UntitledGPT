# UntitledGPT

A dark blue/black AI chat interface powered by the LLM7.io OpenAI-compatible API.

- Model: `gpt-oss:20b`
- API endpoint: `https://api.llm7.io/v1/chat/completions`
- No local model runtime required.
- Chat history is stored in browser localStorage.

## Run

Open `index.html` in a browser. Requests are sent directly from the browser to LLM7.io; this prototype uses anonymous access and does not embed an API token. Provider limits and availability may change. Do not send sensitive information.

## GitHub Pages

To publish, enable GitHub Pages for the repository and choose the `main` branch with `/ (root)` as the source. The app will be available at `/untitledgpt/`.
