# Software Bug Assistant

The Software Bug Assistant is a sample agent designed to help IT Support and Software Developers triage, manage, and resolve software issues. This sample agent uses ADK Python, a PostgreSQL bug ticket database (internal tickets), GitHub MCP server (external tickets), RAG, Google Search, and StackOverflow to assist in debugging.

## Key Features

Retrieval-Augmented Generation (RAG): Leverages Cloud SQL's built-in Vertex AI ML Integration to fetch relevant/duplicate software bugs.
MCP Toolbox for Databases: MCP Toolbox for Databases to provide database-specific tools to our agent.
GitHub MCP Server: Connects to GitHub's remote MCP server to fetch external software bugs (open issues, pull requests, etc).
Google Search: Leverages Google Search as a built-in tool to fetch relevant search results in order to ground the agent's responses with external up-to-date knowledge.
StackOverflow: Query StackOverflow's powerful Q&A data, using LangChain's extensive tools library— specifically, the StackExchange API Wrapper tool.. ADK comes with support for third-party tools like LangChain tools
Quick Start
