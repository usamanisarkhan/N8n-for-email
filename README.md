# N8n-for-email

# AI-Powered Email Automation Agent (n8n + Gemini)

This project demonstrates how to build an intelligent automation agent using **n8n**, **Google Gemini**, and the **Gmail API**. It was designed as a classroom demo to showcase how HR departments can automate personalized client onboarding and congratulatory emails with a single natural language prompt.

## 📺 Project Demo

Below is the demonstration of the agent in action.

<!-- 
NOTE: To display your video on GitHub:
1. Drag and drop your video file directly into the GitHub README editor. 
2. GitHub will automatically upload it and provide a <video> tag or a link.
3. Replace the line below with that generated code.
-->

[https://github.com/user-attachments/assets/your-video-link-here](https://youtu.be/jap4e9A5JJQ)

---

## 🛠️ How it Works

The workflow uses a **Linear Optimization** architecture consisting of four main nodes:

1.  **Chat Trigger:** The interface for the user to provide instructions.
2.  **AI Agent:** The decision-maker that chooses which tools to use.
3.  **Gemini Chat Model:** The language engine that drafts the email content.
4.  **Gmail Tool:** The execution tool that sends the finalized email.

## 🚀 Setup Guide

### 1. Requirements
* An [n8n](https://n8n.io/) account (Self-hosted or Cloud).
* A Google Cloud Project with the **Gmail API** enabled.
* A **Gemini API Key** from [Google AI Studio](https://aistudio.google.com/).

### 2. Implementation Steps
* **Agent Node:** Connect the Gemini Chat Model to a "Reasoning" or "Tool" agent.
* **Gmail Node:** Add the Gmail tool to the Agent. Ensure you select "Let the model define this parameter" for the **Subject** and **Body** fields. This allows the AI to craft the message contextually.
* **Prompting:** Give the agent a simple command like: *"Send an email to a client congratulating them on their CCNA certification."*

## 📈 Use Cases
* **HR Onboarding:** Send 50+ personalized welcome emails with one prompt.
* **Client Management:** Automated follow-ups based on specific triggers.
`* **Certification Tracking:** Congratulate team members on professional achievements automatically.

---
*Created for educational purposes at Xamk.*
README.md
Displaying README.md.
