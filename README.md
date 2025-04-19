# Clerk

Clerk listens to your meeting transcripts so you don’t have to. It extracts tasks and turns them into GitHub Issues using LLMs.

# Project Structure

clerk/
│
├── clerk/
│   ├── transcripts/      # Stores raw or preprocessed transcript files
│   ├── parser/           # LLM calls + response parsing logic
│   ├── github_api/       # Functions for creating issues on GitHub
│   ├── utils/            # Shared utility functions (logging, formatting, etc.)
│   ├── config.yaml       # All runtime config (paths, model, repo settings)
│   └── main.py           # Entry point for pipeline execution
│
├── .gitignore
├── LICENSE
└── README.md

# Status

Project under active development. Contributions welcome.
