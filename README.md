# PacDefBot 🌏

An automated system for tracking and analyzing US-China defense activities in the Pacific Area of Responsibility (AOR).

## Overview 🔍

PacDefBot automates the collection, processing, and distribution of defense-related news and updates, focusing on US-China activities in the Pacific region. It leverages AI and automation to provide timely, accurate intelligence summaries.

## Key Features 🚀

- **Automated News Scraping**: Monitors multiple sources for defense-related content
- **AI-Powered Analysis**: Uses Venice.ai (Mistral 24B) for content processing
- **Vector Search**: Implements RAG for intelligent information retrieval
- **Automated Distribution**: Generates newsletters and social media updates

## Tech Stack 💻

- **Web Scraping**: n8n automation workflows
- **Backend**: FastAPI + Python
- **Databases**: 
  - PostgreSQL (structured data)
  - Qdrant (vector storage)
- **AI/ML**: 
  - Venice.ai (Mistral Small 3.1 24B)
  - SentenceTransformers
- **Infrastructure**: 
  - Docker containers
  - DigitalOcean cloud hosting

## Architecture 🏗️

```
[Web Sources] → [n8n Scraper] → [FastAPI Service]
                                       ↓
[Venice.ai LLM] ← [Content Processor] → [Databases]
                                       ↓
                            [Newsletter/Social Distribution]
```

## Setup 🛠️

Detailed setup instructions coming soon...

## License 📄

MIT License - See LICENSE file for details

## Contributing 🤝

Contributions, issues, and feature requests are welcome!
