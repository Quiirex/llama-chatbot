<p align="center">
    <img src="https://www.pngmart.com/files/22/Llama-PNG.png" alt="Logo" width="150" height="150">
</p>

# LLaMa Chatbot

This web application is designed to demonstrate the capability of creating a basic chatbot web application using Rust, Leptos, TailwindCSS, and an open-source language model like GPT, LLaMA, or similar variants.

## Running the chatbot

- Download an LLM in GGML format
- Define the environment variable `MODEL_PATH` (in a .env file) to be the path to the model you want to use
- Run `npm install`
- Run `npx tailwindcss -i ./input.css -o ./style/output.css --watch`
- Run `cargo leptos watch`
- Navigate to `localhost:3000`
- Start chatting!
