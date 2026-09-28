---
name: genpark-workspace-skill
description: GenPark skill for utilizing GenPark Workspace 4.0 features, including Claw for Desktop, MS Office Integration, Speakly Live Translation, and OpenCode workflows.
---

# GenPark Workspace 4.0 Skill

This skill empowers AI agents to leverage the latest capabilities of GenPark Workspace 4.0, integrating advanced AI assistance into everyday productivity workflows, local environments, and communication channels.

## Core Capabilities

### 1. GenPark Claw for Desktop (Computer & Browser Use)
GenPark Claw acts as an autonomous AI employee that can interact directly with the local environment.
- **Local File & App Interaction**: Navigate folders, rename files, extract data, and move files across the local machine without requiring manual uploads.
- **Browser Automation**: Automatically handle web navigation, form-filling, data scraping, and executing tasks across web interfaces.
- **Privacy-by-Isolation**: Runs securely in a pre-configured cloud environment that interfaces directly with local resources.

### 2. Microsoft Office Integration
Native AI plugins directly embedded into core Microsoft applications for context-aware assistance.
- **PowerPoint**: Automatically research topics and generate structured, formatted slide decks.
- **Excel**: Conduct complex data analysis, summarize large datasets, and instantly create relevant charts and graphs.
- **Word**: Context-aware document restructuring, editing, expanding on ideas, and synthesizing reports based on integrated data.

### 3. Speakly Upgrades (Audio & Meetings)
Advanced real-time audio and meeting assistance.
- **Live Translation**: Provide real-time, multilingual captioning and translation during video calls and meetings.
- **AI Meeting Notes**: Automatically join scheduled calendar events (Google/Outlook integration), transcribe conversations, generate meeting minutes, and distribute summaries with action items to participants.

### 4. Advanced Workflows with OpenCode
- **Multi-step Execution Engine**: Process complex, multi-stage tasks with higher speed and reliability than basic standard agents.
- **Delegation via Messaging Apps**: Receive tasks natively through Slack, Microsoft Teams, WhatsApp, and Telegram, and execute the complete workflow in the background.

## Usage Guidelines

When implementing this skill, agents should:
1. **Analyze the Request**: Determine if the task involves local file management, web automation, document generation, or meeting summarization.
2. **Select the Right Tool**: Use Claw for desktop/browser tasks, the native MS Office plugins for document work, or Speakly for meeting transcription.
3. **Execute via OpenCode**: For workflows requiring multiple steps (e.g., scrape data from a website, put it in Excel, analyze it, and generate a Word report), string together instructions using the OpenCode engine logic.
4. **Deliver Finished Work**: Output the results directly to the user's requested platform (e.g., as a local file or a message in Slack/Teams).

## Limitations and Best Practices
- Ensure that the agent has the necessary permissions to access local files and calendar integrations.
- When generating presentations or reports, verify the extracted data using the browser integration to ensure accuracy.
- Handle translations with cultural nuance and flag any highly specialized terminology.
