# MCP Server & Client (TypeScript + Gemini LLM)

## Overview
- A server that manages user data, with the ability to add, remove, and query users.  
- Integration with the Gemini API to generate realistic sample users.  
- A command-line client that connects to the MCP server, lists available tools/resources/prompts, and allows interactive queries.

The project demonstrates backend protocol implementation, CLI-based client interaction, and schema-based data handling.

---

## Features

### Server
- **User Management**
  - Retrieve all users
  - Fetch an individual user's profile
  - Create new users manually
  - Generate sample users with realistic details
- **MCP Endpoints**
  - Resources: read-only access to user data
  - Tools: create or modify user records
  - Prompts: parameterized AI-assisted operations
- **Local Storage**
  - Uses a JSON file (`users.json`) for persistence

### Client
- Command-line interface with menu-based navigation
- Dynamically lists available tools, prompts, and resources from the server
- Runs server tools and prompts interactively
- Query mode that accepts freeform input and uses available tools to respond

---
