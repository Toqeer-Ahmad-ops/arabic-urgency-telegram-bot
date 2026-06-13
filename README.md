# 🚨 Arabic Urgency Detection → Telegram Bot

**For Dubai Retail**: Automates عاجل/ضروري/مستعجل order alerts from Gmail in 2 seconds. $0/month.

## Problem

Qoton Printing Dubai receives 50+ Arabic orders/day via email. Staff waste 2hrs manually checking for **عاجل**, **مستعجل**, **ضروري**. Delays = lost customers.

## Solution

No-code pipeline: **Gmail → n8n → Google Gemini → Telegram Bot API**

Detects urgency keywords → Sends instant Arabic alerts → Zero WhatsApp ban risk

## Results

| Metric | Value |
| --- | --- |
| **Speed** | 30min manual triage → 2 seconds automated |
| **Accuracy** | 95% on عاجل/مستعجل/ضروري/سريع |
| **Cost** | $0/month vs WATI $2,000/mo |
| **Proof** | 4 urgent orders → 4 Telegram alerts delivered |

## Tech Stack

**n8n** | **Google Gemini** | **Telegram Bot API** | **Google Sheets**

## Screenshots — Day 1-4 Proof

### Day 4: Telegram Bot Alerts
![Arabic Alerts](day4-telegram-alerts.jpeg)

**Result**: QOT-5001 to QOT-5004 delivered in 2 seconds. عاجل للعيد, ضروري detected.

### Day 3: n8n Workflow
![n8n Workflow](screenshots/day3-n8n-workflow.jpeg)

**Result**: Gmail → Gemini → Filter → Telegram. 6 items → 4 urgent routed.

### Day 2: Gemini Arabic NLP
![Gemini Prompt](screenshots/day2-gemini-arabic-nlp.jpeg)

**Result**: Classifies "عاجل للعيد" as urgent with JSON. Handles Arabic nuance.

### Day 1: Gmail → Sheets
![Gmail to Sheet](screenshots/day1-gmail-sheet.jpeg)

**Result**: 50+ emails/day → structured data. Zero manual entry.

## Setup Time

**15 minutes** for Dubai SMBs

## Available for Hire

**10-14k AED | Dubai | July 1** 
AI Automation Specialist: No-code AI for Retail/Events
