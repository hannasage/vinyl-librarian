# Vinyl Record Collection Agent

A LangGraph-powered agent that automatically processes vinyl record purchase emails and maintains a personal vinyl collection database. The agent uses AI to extract structured data from email receipts, matches or creates artist records, and stores album information in a Supabase database.

## Key Features
- Automated email receipt processing
- AI-powered data extraction using Claude 3 Sonnet
- Artist name resolution and deduplication
- Robust error handling and retry logic
- Comprehensive tracing and monitoring
- Scheduled processing via pgcron

## Technologies
- **Framework**: LangGraph
- **AI/ML**: 
  - Anthropic's Claude 3.5 Sonnet for NLP
- **Monitoring**: LangSmith
