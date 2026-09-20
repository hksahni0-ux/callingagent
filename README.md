# AI Calling Agent

An AI-powered outbound calling agent for expo/event lead outreach — calls contacts over SIP/VoIP, converses using a language model, and logs outcomes back to a spreadsheet.

## What it does

- Places outbound calls over SIP/VoIP (Wildix/xbees compatible)
- Transcribes speech in real time with Whisper
- Drives natural conversation via an LLM (Groq for testing, local Ollama in production)
- Synthesizes responses with Piper (fast) or F5-TTS (voice-cloned) speech
- Schedules calls within configured calling-hour windows
- Reads contact lists and writes call logs to Google Sheets

## Stack

Python · pyVoIP (SIP) · faster-whisper (STT) · Groq / Ollama (LLM) · Piper / F5-TTS (TTS) · Google Sheets API

---

This is a private, closed-source project. This repository is a public overview only — no source code is published here.
