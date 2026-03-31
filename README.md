# voice-to-linkedin

A Make.com automation that turns voice memos into drafted LinkedIn posts using OpenAI Whisper and Claude.

## How it works

1. Drop a voice memo (.m4a) into a Google Drive folder
2. Whisper transcribes the audio
3. Claude drafts a LinkedIn post in your voice — picking the strongest single idea if multiple are present
4. Draft lands in your inbox via Gmail
5. Unused ideas are saved to a Google Doc for future posts

## Tools used

- Make.com
- Google Drive
- OpenAI Whisper
- Anthropic Claude (claude-sonnet-4)
- Gmail
- Google Docs

## Setup

1. Import `workflow.json` into Make.com
2. Add your own API keys where indicated
3. Point the Google Drive trigger at your folder
4. Add your email to the Gmail step
5. Create a Google Doc for your ideas library and connect it to the final step

## Part of a larger personal operating stack

This is one module in an ongoing project to build an AI-augmented personal operating system. More automations coming.

## Built by

Lindsey Bond — Fractional Chief of Staff & Ops Partner
[plutoventures.io](https://plutoventures.io)
