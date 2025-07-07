# N8N
For developing in N8N
# Codex Automation Workflows

This repository contains development resources, nodes, and documentation for automating tasks using [Codex](https://codex.ai) with integration to various platforms such as Microsoft 365, n8n, MySQL, and Telegram.

## 🔧 Overview

This project is focused on building intelligent, reusable automation workflows for both work-related and personal tasks. It leverages:

- **Microsoft Graph API** (Teams, Outlook, SharePoint) for work task management and communications
- **n8n**, self-hosted on Unraid, as the orchestration engine
- **MySQL**, hosted locally, for structured data storage
- **Telegram** as a lightweight interface for personal project interactions

## 🧠 Goals

- Enable natural language and AI-driven task automation for daily operations
- Centralize data from communication platforms into actionable tasks or logs
- Build a scalable structure for adding custom Codex nodes and workflows

## 📦 Tech Stack

| Component     | Description                                     |
|---------------|-------------------------------------------------|
| Microsoft 365 | Teams, Outlook, SharePoint via Microsoft Graph |
| n8n           | Workflow automation, self-hosted on Unraid     |
| MySQL         | Local database for workflow state/logging      |
| Telegram      | Personal task and bot testing interface         |

## 📁 Repository Structure

```bash
codex-workflows/
├── nodes/              # Custom Codex or n8n nodes
├── workflows/          # JSON exports of automation flows
├── templates/          # Prompt and document templates
├── docs/               # Documentation and setup guides
├── .env.example        # Sample environment variables
└── README.md           # This file