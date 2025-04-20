# Functional Prompt Module System (FPMS)

## Purpose
A modular system to build, test, and share reusable prompt units in GPT-based systems.

## Module Format

### `INPUT`
Defines the required user input or topic context.

### `CONTEXT`
Specifies background information or domain rules.

### `INTENTION`
What the prompt is designed to achieve.

### `RESPONSE-TYPE`
Specifies the style, format, or tone of the AI's reply.

## Example Module
```
INPUT: Describe the user's current emotional tone.
CONTEXT: Based on recent statements and inferred mood.
INTENTION: Mirror their emotional state gently.
RESPONSE-TYPE: Short reflective statement.
```

## Application
Supports:
- Collaborative prompt repositories
- Transparent prompt development
- Testing and debugging via consistent structure

---

## README (Integrated)
FPMS offers a scalable way to manage prompt design across projects. Whether you are prototyping a chatbot or building AI interfaces, this modular system helps you stay organized and expressive.