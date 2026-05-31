# Instagram Content Automation System

Multi-agent AI system that auto-generates ready-to-post Instagram carousels 3x/week for a niche travel brand using a single line of input.

## How It Works
A team of 4 AI agents handle the full pipeline — research, content strategy, copywriting, and QA — before delivering a finished carousel with slides, caption, and hashtags.

## RAG Pipeline
Brand knowledge stored in Supabase pgvector ensures every output matches the brand's voice, pricing, and content rules. No generic AI content.

## Content Gap Checker
Reads posted topics history from Notion before each run. Never repeats a topic.

## Auto Scheduler
Make.com triggers the full flow automatically on scheduled days. Carousels saved to Notion and queued as drafts in Buffer. Zero manual work.

## Trend Scanner and Persona Rotation
Agents suggest topics based on live trends and current season. Content rotates across audience personas automatically.

## Performance Feedback Loop
Platform insights fed back into the system after 7 days. Future content biased toward what actually performed.

## Tech Stack
Flowise · Groq (Llama 3.3 70B) · Supabase · pgvector · Google Gemini Embeddings · Notion · Make.com · Buffer · Instagram API · LangChain · RAG
