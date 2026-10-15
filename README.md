# AI-Agents-
This Repository contains all AI-Agents that i have created. 

# Data Analyst Agent in n8n
An automated AI-powered data analyst agent built using n8n that connects OpenAI, Google Sheets, and Gmail to analyze sales data and deliver automated insights directly to your inbox.

## Architecture & Components
- **Chat Trigger / AI Agent Node**: Handles user prompts and orchestration.
- **OpenAI Chat Model (GPT-4o mini)**: Acts as the brain for data reasoning.
- **Simple Memory**: Maintains conversation context.
- **Google Sheets Tool**: Reads and processes raw sales dataset rows.
- **Gmail Tool**: Formats and emails clean HTML reports.

## How to Use
1. Import the `workflow.json` file into your self-hosted or cloud n8n instance.
2. Set up your OpenAI, Google Sheets, and Gmail credentials.
3. Run or test the workflow via the chat trigger link.


--------------------------------------------------------------------------------------------------------------------------------------------
