# Quell-Inbox-Agent
AI-powered email triage app — classifies urgency, extracts deadlines, identifies opportunities, and drafts replies using Claude AI.

# Quell

Quell is a standalone AI-powered inbox assistant that connects to your Gmail account and helps you cut through email chaos. Built with vanilla HTML/CSS/JS and powered by Claude AI.

## Features

- **Urgency & Category Classification** — every email is rated Critical, High, Medium, or Low with a one-sentence explanation
- **Due Date Extraction** — deadlines and time-sensitive actions are automatically surfaced from email body text
- **Opportunity Identifier** — flags partnership leads, hiring opportunities, event invitations, and RSVPs
- **One-Click Reply Drafting** — generates a context-aware reply instantly, with a typewriter reveal and copy to clipboard

## Setup

1. Create a project in [Google Cloud Console](https://console.cloud.google.com)
2. Enable the **Gmail API**
3. Create **OAuth 2.0 credentials** (Web application type)
4. Add your GitHub Pages URL as an authorized JavaScript origin
5. Open the app, paste your Client ID, and connect your Gmail account

## Stack

- Vanilla HTML, CSS, JavaScript — no build step, no dependencies
- [Gmail API](https://developers.google.com/gmail/api) for inbox access
- [Claude API](https://anthropic.com) (claude-sonnet) for AI triage

## Usage

Open the app at your GitHub Pages URL, enter your Google OAuth Client ID, and click **Connect with Google**. Once authenticated, click **▶ triage all** to analyze your inbox, or triage individual emails from the detail panel.

Demo mode is available without any credentials — click **try demo mode** on the login screen.
