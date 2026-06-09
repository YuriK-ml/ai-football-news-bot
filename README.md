# AI Football News Bot

AI-powered football news aggregation and Telegram publishing system built with n8n, OpenAI and RSS feeds.

## Overview

This project automatically collects football news from major media sources, filters irrelevant content, rewrites selected articles into engaging Telegram posts, and publishes them to a Telegram channel.

The system was created as a rapid AI prototyping project to evaluate automated content aggregation, filtering and publishing workflows.

## Features

* Automated RSS news collection
* AI-powered content filtering
* Football-specific news selection
* Women's football filtering
* Low-value content filtering
* FIFA World Cup prioritization
* Automatic Telegram publication
* Source attribution
* Original article links
* Telegram HTML formatting
* Fully automated workflow

## Data Sources

* BBC Football
* The Guardian Football

## Workflow

RSS Sources

↓

News Filtering

↓

AI Content Processing

↓

Telegram Publishing

## Technology Stack

* n8n
* OpenAI API
* Telegram Bot API
* RSS Feeds
* Prompt Engineering

## Example Processing

Input:

* RSS football article
* Source information
* Original URL

Output:

* Rewritten Telegram post
* HTML formatting
* Relevant hashtags
* Source attribution
* Original article link

## Future Improvements

* Python implementation
* Codex-assisted development
* ESPN Soccer integration
* Duplicate detection
* Multi-language publishing (RU / EN)
* Advanced news ranking

## Configuration

Before running the workflow:

1. Create OpenAI credentials in n8n.
2. Create Telegram Bot credentials.
3. Replace TELEGRAM_CHANNEL_ID with your Telegram channel ID.
4. Replace TELEGRAM_ADMIN_CHAT_ID with your Telegram chat ID.
5. Activate the workflow.

## Author

Yuri Korobkov

AI Systems Engineer | LLM | RAG | AI Agents | FastAPI
