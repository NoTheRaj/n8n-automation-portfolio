# n8n Automation Portfolio

This repository contains practical automation workflows I built using n8n, local AI, webhooks, and external integrations.

## Purpose

This repo is my public portfolio of real automation systems.  
Each workflow is documented as a small case study with:
- the problem it solves
- the workflow structure
- the tools used
- example input/output
- screenshots

## Projects

### 1. Question Rewriter + Google Sheets Logger

A webhook-based workflow that:
- receives a user question
- rewrites it into a clearer AI prompt
- sends it to a local Ollama model
- returns the AI response
- logs the interaction to Google Sheets

Project folder:

`workflows/question-rewriter-sheets-logger`

## Skills Demonstrated

- n8n workflow design
- Webhook setup
- HTTP API requests
- Local AI integration with Ollama
- Prompt transformation
- Google Sheets logging
- Response handling
- Debugging request/response issues

## Repository Structure

```text
n8n-automation-portfolio/
  README.md
  workflows/
    question-rewriter-sheets-logger/
      README.md
      workflow.json
      screenshots/
        flow-overview.png
        webhook-output.png
        google-sheets-log.png
