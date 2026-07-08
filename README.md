# AI Agent Workflow with n8n and Gemini 🤖

This is a simple autonomous AI Agent built using **n8n** (the modern cloud version) and **Google Gemini 2.5 Flash**. The agent can answer user questions and use tools like Wikipedia to look up information live.

## Features
- **AI Model:** Google Gemini 2.5 Flash (connected easily via n8n Connect).
- **Memory:** Uses Simple Memory to remember chat history and context.
- **Tools:** Connected to the Wikipedia tool for live information search.
- **UI:** Works with n8n's built-in chat trigger and responds via Webhook.

## How to Setup and Use
To use this workflow in your own n8n setup, just follow these steps:

1. Download the `ai-agent-workflow.json` file from this repository.
2. Open your n8n dashboard and create a new workflow.
3. Click on the menu (top right) and choose **Import from File**, then select the JSON file you downloaded.
4. Make sure the Gemini Chat Model is connected (you can use your own API key or n8n Connect).
5. Click **Test Workflow** and start chatting with your new AI agent!
