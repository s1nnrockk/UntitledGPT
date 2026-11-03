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


## Image generation

The composer includes an image-generation mode backed by Pollinations' legacy anonymous image endpoint (`image.pollinations.ai`). It requires no API key and runs remotely, but anonymous access is rate-limited and may be unavailable; the app reports failures in the chat. Generated images are shown inline and the prompt/image URL are saved with the local chat history.
