Friday-pAI 

A Personal AI Desktop Assistant

Friday-pAI is a personal AI assistant I'm building to make everyday computer tasks easier. The idea is simple: instead of having an AI that only answers questions, I want to build something that can understand what I need, use different tools, remember useful information, and complete tasks through multiple steps.

The project is built with Electron and Node.js, with NVIDIA Nemotron handling AI interactions and Tavily helping with web research.

I'm continuously working on improving its capabilities and making it more useful as a personal desktop assistant.

What can it do?

AI Chat

- Chat naturally with the assistant.
- Uses NVIDIA Nemotron API for AI-powered responses.
- Can decide when to use available tools to handle a request.

Web Search

- Uses Tavily API to search the web.
- Helps gather information for research and other tasks.

Built-in Tools

Friday currently has integrations for:

- Calculator
- Date and time
- System information
- File management
- Web search

Memory

One of the things I wanted to add was the ability for Friday to remember useful information instead of treating every conversation as completely new.

The memory system stores useful context and makes it available for future interactions.

Workflow Automation

This is one of the main parts of the project.

I wanted Friday to handle tasks that require more than one action. For this, I've developed a workflow engine that supports:

- Multi-step task execution
- Dependencies between steps
- Workflow status tracking
- Retry handling
- Recovery of interrupted tasks
- Approval before protected operations
- Saving workflow history and task events

Some Workflows

I've created several workflow definitions to explore what Friday can do:

Workflow| What it does
Calculation Explainer| Calculates an expression, verifies the result, and explains it.
Daily Briefing| Searches requested topics and prepares a summary.
Project Assistant| Inspects project files and suggests improvements.
Research & Study| Researches a topic and organizes study notes.
System Check| Collects and summarizes system information.
File Organizer| Inspects files and prepares an organization plan.

Tech Stack

- JavaScript
- Node.js
- Electron
- NVIDIA Nemotron API
- Tavily API
- JSON

Running Locally

1. Clone the repository

git clone https://github.com/Maulik05Kalyan/Friday-pAI.git

2. Open the project directory

cd Friday-pAI

3. Install dependencies

npm install

4. Configure API keys

Create a ".env" file and add the API credentials required by the application. Check the source code for the exact environment-variable names.



5. Start the application

Check "package.json" for the available start or development command.

What's Next?

There are still plenty of things I want to improve.

Some of my goals for Friday are:

- Better memory and context retrieval.
- More reliable workflow execution.
- Ability to work with projects across different folders.
- More advanced file operations with user approval.
- Browser automation.
- Better task planning and result verification.
- Integration with additional AI model providers.

Why I Started This Project

I started Friday-pAI because I wanted to build my own personal AI assistant rather than just use another chatbot.

I wanted to understand how AI models, tools, memory, and automation can work together in a single application.

It's an ongoing project, and I'm learning and improving it as I build.
