# ai-email-management-automation
An n8n AI-powered email automation workflow that classifies incoming emails, organizes Gmail messages, logs data in Google Sheets, and automates responses.

# AI Email Management Automation

## Overview

This project is an AI-powered email management workflow built with n8n. It uses Large Language Models (LLMs) to classify incoming emails and automate email organization and handling.

The workflow integrates Gmail, Google Gemini, and Google Sheets to reduce manual email management and improve productivity.

## Key Features

- AI-powered email classification.
- Email categorization into administrative, spam, marketing, client service, professional, and meeting request categories.
- Automated Gmail labeling for supported categories.
- Google Sheets integration for logging and tracking email information.
- Automated email response workflows for selected categories.
- AI agent integration for handling meeting-related requests.

## Workflow Architecture

1. Receive incoming emails through Gmail.
2. Process email content using an LLM.
3. Classify emails according to their purpose.
4. Route emails to the appropriate workflow branch.
5. Apply Gmail labels or process emails according to their category.
6. Store relevant email information in Google Sheets.
7. Trigger automated responses for selected email categories.

## Technologies Used

- **n8n** — Workflow automation and orchestration
- **Google Gemini** — AI-powered email classification
- **Gmail** — Email processing, labeling, and responses
- **Google Sheets** — Email data logging and tracking
- **LLM Chains and AI Agents** — AI processing and task automation

## Use Cases

- Automating repetitive email management tasks.
- Organizing business emails by category.
- Tracking customer service and professional communications.
- Managing meeting-related requests.
- Improving productivity through AI-powered workflows.

## Setup Requirements

- An n8n instance.
- A connected Gmail account.
- Google Gemini API credentials.
- Google Sheets access and the required spreadsheet.
- Properly configured Gmail labels and workflow branches.

## Security

API keys, OAuth credentials, personal email content, and other sensitive information must never be included in public repository files.

## Author 

Electronics graduate interested in AI automation, intelligent systems, and workflow development.

Hadid Mouadh



