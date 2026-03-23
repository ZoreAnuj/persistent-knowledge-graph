# Persistent Knowledge Graph for Coding Agents

A persistent project knowledge graph that enables coding agents to maintain context across sessions. It provides semantic search capabilities and a web-based explorer for navigating project knowledge.

## Key Features
- **MCP Server Integration** - Implements the Model Context Protocol for agent communication
- **Semantic Search** - In-process embeddings for efficient knowledge retrieval
- **Web Explorer** - Browser-based interface for visualizing and navigating the knowledge graph
- **Persistent Storage** - Maintains project context across agent sessions

## Tech Stack
- Python
- FastAPI
- Sentence Transformers
- React (web interface)
- SQLite

## Getting Started
```bash
git clone https://github.com/zoreanuj/persistent-knowledge-graph.git
cd persistent-knowledge-graph
pip install -r requirements.txt
python server.py
```