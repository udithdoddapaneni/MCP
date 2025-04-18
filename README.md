# Viśva Mitra
## One Assistant. Infinite Possibilities.

## to setup do the following
(Pre-req - need to have Ollama installed, just and uv)
for setting up - "just setup"
for runnning -   "just run"

## Important
- Add you GOOGLE_API_KEY in universal_assistant/.env file

## Introduction
The Viśva Mitra universal assistant comes to your help by accessing the Tools from different MCP servers and wisely calling it to solve your query. It acts as an intelligent router between user requests and specialized tools, creating a unified experience.

## Core Concept
Viśva Mitra is built on the idea of tool integration and orchestration. Rather than attempting to solve all problems within a single model, it:

1. **Understands user intent** through natural language processing
2. **Identifies required tools** to complete the task
3. **Routes requests** to appropriate MCP (Model Control Protocol) servers
4. **Aggregates results** from various tools
5. **Presents a unified response** to the user

This approach allows for:
- Greater specialization of individual tools
- Easier scaling and addition of new capabilities
- Better performance on domain-specific tasks

## How It Works

When a user interacts with Viśva Mitra:

1. The system processes the natural language input to determine intent
2. It searches its tool registry for appropriate tools to handle the request
3. Selected tools are called through standardized MCP interfaces
4. Results from multiple tools may be combined or refined if necessary
5. A coherent response is generated and delivered to the user

## to see the docs

- cd universal_assistant/mk_docs
- uv run mkdocs serve
