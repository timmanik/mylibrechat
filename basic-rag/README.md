# LibreChat Setup with Ollama

This repository contains the necessary files to set up and run [LibreChat](https://github.com/danny-avila/LibreChat) with [Ollama](https://ollama.com) as your local language model provider.

## Files in this repository

- `.env`: Contains environment variables needed for the setup.
- `librechat.yaml`: Configuration file for LibreChat, specifying model details and settings.
- `docker-compose.override.yml`: Custom Docker Compose override file to ensure proper setup with Ollama.

## Note
This setup uses the `nomic-embed-text` embedding model provided by Ollama.