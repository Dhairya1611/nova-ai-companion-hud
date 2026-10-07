# NOVA — Futuristic HUD AI companion

A static GitHub Pages interface for a private, local-first AI companion. The central neural avatar is embedded in the page so the site does not depend on an external image host.

## Features

- Circular sci-fi HUD layout inspired by the supplied reference image
- Exact blue neural-face avatar placed at the center of the HUD
- Free local Llama 3.2 3B model through WebLLM and WebGPU
- Chat mode with suggestions and local conversation
- Talk mode with browser speech recognition and speech synthesis
- Avatar expression, scanline, eye and mouth animation while NOVA listens, thinks and speaks
- Responsive layout for desktop, tablet and mobile

## Run locally

Serve the repository over HTTP, then open the page in a browser with WebGPU enabled. The first model initialization downloads the model to the browser cache. No API key is required.

## Hosting

This project is designed for GitHub Pages. Static hosting serves the interface; the AI model runs locally in the visitor browser.
