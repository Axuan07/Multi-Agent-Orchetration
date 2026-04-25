# Multi-Agent-Orchestration

A local multi-agent AI orchestration system that coordinates multiple LLM providers through a provider-agnostic, slot-based architecture.

## Overview

Multi-Agent-Orchestration is a desktop-based experimental system for coordinating multiple large language models within a shared workflow. Instead of relying on a single model, the system allows different LLM providers to participate as independent agents with configurable roles, memory structures, and output strategies.

The project is designed to explore multi-model collaboration, dynamic role assignment, prompt engineering, memory management, and human-AI workflow optimization.

## Key Features

- Provider-agnostic slot-based architecture
- Support for multiple LLM providers such as OpenAI, Claude, and Gemini
- Dynamic planner and lead-agent assignment
- Configurable final response strategies
- Multi-model parallel output
- Shared working context across agents
- Provider-specific memory design
- Desktop-based local orchestration interface

## Tech Stack

- Python
- Tkinter / CustomTkinter
- OpenAI API
- Anthropic Claude API
- Google Gemini API
- JSON-based configuration and memory storage

## Project Structure

```text
Multi-Agent-Orchestration/
├── main.py
├── providers/
├── memory/
├── config/
├── prompts/
├── ui/
└── README.md
