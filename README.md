# 🤖 RZ Agent

A local AI agent developed in Java, using Ollama4j to interact with Large Language Models (LLMs) running locally through Ollama.

## Overview

RZ Agent explores the integration of Java applications with local artificial intelligence models, allowing developers to experiment with LLM-powered applications without relying on external cloud-based AI APIs.

## Features and Concepts

- **Local AI:** Uses models hosted locally through Ollama.
- **Java Integration:** Uses Ollama4j as the communication layer.
- **Privacy-Oriented:** Supports local prompt processing.
- **Self-Hosted AI:** Gives developers control over their local models.
- **AI Agent Development:** Explores agent-based application architecture.

## Tech Stack

- Java
- Ollama
- Ollama4j

## Architecture

```text
User Input
    |
    v
Java Application
    |
    v
RZ Agent
    |
    v
Ollama4j
    |
    v
Ollama Runtime
    |
    v
Local LLM
    |
    v
Generated Response
```

## Requirements

- Java Development Kit (JDK)
- Ollama installed
- A compatible model downloaded locally

## Getting Started

```bash
git clone https://github.com/rianrz/rz-agent.git
cd rz-agent
```

## Setting Up Ollama

Install Ollama from https://ollama.com/.

Download an example model:

```bash
ollama pull llama3.2
```

Check installed models:

```bash
ollama list
```

Make sure Ollama is running before launching the application.

## Running the Project

Open the project in your preferred Java IDE and configure the dependencies according to the repository build configuration.

Ensure that Ollama is running and that the configured model is available locally.

## Why Local AI?

- **Privacy:** Prompts can remain in your local environment.
- **Control:** Choose which models to run.
- **Independence:** Reduce reliance on hosted AI APIs.
- **Experimentation:** Explore LLMs and agent architectures.

Local execution still depends on your hardware and model requirements.

## Project Goals

- Local Large Language Models
- Java and AI integration
- Ollama4j
- AI agent architecture
- Self-hosted AI applications

## Future Improvements

- Conversation memory
- Multiple model support
- Configurable model parameters
- Tool calling
- Conversation history
- Improved testing

## License

Check the repository for license information.

## Author

Developed by [rianrz](https://github.com/rianrz).
