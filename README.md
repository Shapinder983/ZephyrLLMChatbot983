---
title: CustomizedLLMApp
emoji: 💬
colorFrom: yellow
colorTo: purple
sdk: gradio
sdk_version: 4.36.1
app_file: app.py
pinned: false
---

An example chatbot using [Gradio](https://gradio.app), [`huggingface_hub`](https://huggingface.co/docs/huggingface_hub/v0.22.2/en/index), and the [Hugging Face Inference API](https://huggingface.co/docs/api-inference/index).
This code sets up an interactive chat application using Gradio and HuggingFace's Inference API to discuss blockchain technology. It initializes the chatbot with a predefined system message about blockchain and allows users to ask questions. The respond function manages the conversation history and generates responses based on user input and configurable parameters like max_tokens, temperature, and top_p. The Gradio interface, complete with example queries and a title, facilitates user interaction, enabling them to learn about blockchain concepts and features.
