# n8n-Workflows

## *1️ Video Content Automation*
This workflow converts a user-uploaded video into a complete content package. It analyzes the video using Gemini 2.5, generates three Instagram-ready scripts, produces a professional production guide, and exports everything as clean, styled PDF files.

*Includes:*
* Video upload + Gemini 2.5 analysis
* 3 script variations (hooks, CTA, pacing)
* Production notes (camera angles, editing plan, overlays)
* Markdown → HTML → PDF conversion
* Auto-merged final output

## *2️ Deep Research Automation*
A structured 5-chapter research generator. Enter a topic and the workflow creates subtopics, searches the web via Tavily, processes sources, generates chapter content, and stores results in Google Sheets.

*Includes:*
* Topic → 5 subtopics planner
* Tavily deep search per chapter
* LLM-generated chapter summaries + citations
* HTML chapter formatting
* Sheets logging for results

## *3️ Email Scraper & Lead Extractor*
Extracts emails from user-provided URLs or text. Cleans the data, removes duplicates, structures results, and sends them into a Google Sheet for easy export or use in outreach tools.

*Includes:*
* URL crawling + scraping
* Regex-based email extraction
* Duplicate removal
* Clean structured sheet output

## *4️ AI Email Assistant (Compose + Send)*
A small but powerful workflow where you type a prompt (e.g., “Write an email to HR about leave”). The workflow identifies the receiver, drafts a professional email using an LLM, and sends it through Gmail.

*Includes:*
* Natural language → email intent extraction
* Auto-generated professional email draft
* Contact lookup
* Gmail send action

## *5️ Voice Assistant Workflow*
A conversational voice bot for Telegram. It receives a voice note, converts it to text, generates a contextual response using an LLM, converts it back to speech, and returns an audio reply.

*Includes:*
* Telegram voice input
* STT + LLM response + TTS
* ElevenLabs voice generation
* Personalized, funny, chat-style replies
