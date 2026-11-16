# Carmen Terminal

Carmen Terminal is a local-first coding assistant that runs in your terminal. It connects directly to Ollama, streams responses as they’re generated, and lets you switch between available models during a conversation.

## Features

- Coding help for programming, debugging, code review, and refactoring
- Automatic discovery and switching of installed models
- Multi-line prompts for sharing code
- Conversation history kept for the current session
- No npm packages required

## Requirements

- Node.js 18 or newer
- Ollama with at least one model installed

## Start

Run `npm start`, or launch `Start Carmen Terminal.bat` on Windows.

Type `/help` to see commands. Use `/multiline` to enter multi-line code, then `/send` to submit it.

## Configuration

The default configuration uses local Ollama. Copy `.env.example` to `.env` to customize the provider URL, API key, or default model.
