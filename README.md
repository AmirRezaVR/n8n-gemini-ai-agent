# AI Agent Workflow with n8n and Gemini 🤖

Hey! This is a simple autonomous AI Agent workflow that I built using **n8n cloud** and **Google Gemini 2.5 Flash**. The cool thing about this agent is that it doesn't just chat—it can actually decide when and how to use external tools to browse the web, scrape content, and research information live based on what you ask.

## Features
- **AI Model:** Powered by Google Gemini 2.5 Flash (connected easily via n8n Connect).
- **Memory:** Uses Simple Memory so it keeps track of the conversation context and remembers what you said earlier.
- **Autonomous Tools:** Equipped with live web-tools (including Wikipedia search and an HTTP web scraper) to fetch live data from almost any URL or online resource for free.
- **UI:** Works perfectly with n8n's built-in chat window and responds via Webhook.

## How to Setup and Use
Want to try it out? It’s super easy to import into your own n8n setup:

1. Download the `ai-agent-workflow.json` file from this repo.
2. Go to your n8n dashboard and create a blank workflow.
3. Open the top-right menu, click **Import from File**, and choose the JSON file you just downloaded.
4. Make sure the Gemini Chat Model node is active (you can use n8n Connect or paste your own API key).
5. Click **Test Workflow**, open the chat box, and start talking to your new AI agent! Try asking it to summarize a website link for you!
