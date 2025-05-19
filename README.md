# VertexMemory - Google Vertex AI / Vector Search MCP Server

VertexMemory is your memory layer for LLMs using Google Vertex AI Vector Search - private, portable, open-source MCP Server. Your memories live locally, giving you complete control over your data. Build AI applications with sophisticated vector search integration..

## Prerequisites

- Docker and Docker Compose
- Python 3.9+ (for backend development)
- Node.js (for frontend development)
- OpenAI API Key (required for LLM interactions)

## Quickstart

You can run the project using the following two commands:
```bash
make build # builds the mcp server and ui
make up  # runs vertexmemory mcp server and ui
```

After running these commands, you will have:
- VertexMemory MCP server running at: http://localhost:8765 (API documentation available at http://localhost:8765/docs)
- VertexMemory UI running at: http://localhost:3000

## Project Structure

- `api/` - Backend APIs + MCP server
- `ui/` - Frontend React application

