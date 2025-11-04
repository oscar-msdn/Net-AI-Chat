# Net-AI-Chat
A .NET Console Application that connects to a local Ollama server and interacts with the phi3:mini model to perform conversational AI tasks.

Project Name: OllamaChatConsole

Description:
A .NET Console Application that connects to a local Ollama server and interacts with the phi3:mini model to perform conversational AI tasks.
The application sends user input as prompts to the Ollama API (http://127.0.0.1:11434/api/generate) and displays the model’s responses directly in the console, enabling a lightweight local chatbot experience without requiring cloud-based inference.

Key Features:

Local LLM chat powered by Ollama and phi3:mini.

Simple text-based interface in the console.

Uses HTTP POST requests to communicate with the Ollama REST API.

100% offline — all inference runs locally.

Easy to extend with custom logic (logging, memory, context, etc.).

Technical Stack:

.NET 9.0 (Console App)

Ollama (local server on port 11434)

C# HttpClient for API communication

JSON serialization via System.Text.Json
