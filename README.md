# n8n Workflow Library

> Production-grade automation workflows built for real-world business use cases

[![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)](https://n8n.io)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

**Author:** [Skarl7](https://github.com/Skarl7) | [AdnexAI](https://www.adnexai.co.uk)

---

## About

This repository contains a collection of production-ready n8n workflow templates designed for businesses, legal firms, and content creators. Each workflow is built, tested, and deployed in real-world scenarios.

## Workflows Included

| Workflow | Description | Use Case |
|----------|-------------|----------|
| `client-onboarding-workflow.json` | Automated client intake from form submission to CRM | Law firms, agencies |
| `email-notification-system.json` | Smart email routing with AI-powered categorisation | Business communications |
| `legal-document-automation.json` | AI-generated legal documents (NDAs, SLAs, LoEs) | Legal practices |
| `social-media-scheduler.json` | Multi-platform content scheduling and publishing | Marketing teams |
| `youtube-shorts-automation.json` | End-to-end YouTube Shorts content pipeline | Content creators |

---

## Getting Started

### Prerequisites

- [n8n](https://n8n.io) (self-hosted or cloud)
- API keys for integrated services (OpenAI, Google Workspace, etc.)

### Import a Workflow

1. Open n8n and go to **Workflows**
2. Click the three-dot menu and select **Import from File**
3. Choose the `.json` file from the `workflows/` directory
4. Configure the required credentials
5. Activate the workflow

### Credentials Required

| Service | Used In | Purpose |
|---------|---------|--------|
| OpenAI API | All AI workflows | LLM-based content generation |
| Google Sheets | Client onboarding | Data storage |
| Gmail / SMTP | Email notifications | Sending emails |
| YouTube API | Shorts automation | Video uploads |
| Telegram Bot | Notifications | Real-time alerts |

---

## Workflow Details

### Client Onboarding Workflow

Triggers on new Typeform/Google Form submission, then:
- Enriches client data via AI
- Creates contact in CRM (Google Sheets / HubSpot)
- Sends personalised welcome email
- Creates task in project management tool

### Legal Document Automation

Generates standard legal documents using OpenAI:
- Non-Disclosure Agreements (NDAs)
- Service Level Agreements (SLAs)
- Letters of Engagement (LoEs)
- Terms of Service templates

### YouTube Shorts Automation

Full content pipeline:
- Script generation via ChatGPT
- Voiceover synthesis (TTS)
- Video assembly and rendering
- Auto-upload to YouTube with metadata
- Cross-post to TikTok/Instagram Reels

---

## Contributing

Contributions are welcome! Feel free to:
- Submit new workflow templates
- Report bugs or suggest improvements
- Share your own n8n automation patterns

## License

Apache 2.0 — See [LICENSE](LICENSE) for details.

---

> Built with passion by [Skarl7](https://github.com/Skarl7) for [AdnexAI](https://www.adnexai.co.uk) & [Lexsk Legal](https://lexsk.co.uk)
