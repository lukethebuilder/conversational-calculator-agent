# project1 — AI Chatbot with Calculator

A beginner Python project: a CLI chatbot powered by LangChain and OpenAI that can hold conversations and perform arithmetic using a built-in calculator tool.

## Features

- Conversational AI using OpenAI's GPT models
- Calculator tool that returns sum, difference, product, and quotient of two numbers
- ReAct agent pattern — the model decides when to use the tool
- Streaming responses

## Requirements

- Python 3.9+
- [uv](https://github.com/astral-sh/uv) package manager
- An [OpenAI API key](https://platform.openai.com/api-keys)

## Setup

1. Clone the repo:
   ```bash
   git clone https://github.com/lukethebuilder/project1.git
   cd project1
   ```

2. Install dependencies:
   ```bash
   uv sync
   ```

3. Copy `.env.example` to `.env` and add your OpenAI API key:
   ```bash
   cp .env.example .env
   ```
   Then edit `.env` and replace `your-openai-api-key-here` with your actual key.

## Usage

```bash
python main.py
```

Type a message and press Enter. Type `quit` to exit.

**Example:**
```
You: What is 42 multiplied by 7?
Assistant: 42 multiplied by 7 is 294.
```
