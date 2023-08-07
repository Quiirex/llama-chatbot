<p align="center">
    <img src="https://www.pngmart.com/files/22/Llama-PNG.png" alt="Logo" width="150" height="150">
</p>

<h1 align="center">LLaMa Chatbot</h1>
This web application is a proof-of-concept that demonstrates the ability to create a basic chatbot web application using Rust, Leptos, TailwindCSS, and an open-source large language model like GPT, LLaMA, or similar variants.

## Using an LLM

You can download and use any LLM in GGML format, although the parameters for the model may have to be tweaked accordingly. I've primarily used Llama-2-7b (13b and 70b should work just as well).

## Running the chatbot

- Download an LLM in GGML format
- Define the environment variable `MODEL_PATH` (in a .env file) to be the path to the model you want to use
- Run `npm install`
- Run `npx tailwindcss -i ./input.css -o ./style/output.css --watch`
- Run `cargo leptos watch`
- Navigate to `localhost:3000`
- Start chatting!
