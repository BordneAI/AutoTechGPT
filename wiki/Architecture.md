# 🏗️ Architecture

This document outlines the high-level design of AutoTechGPT.

## Components

1. **Frontend (index.html)**  
   - Dark-themed UI, dropdown menu, static hosting.
2. **OpenAI GPT Backend**  
   - Menu-driven system prompts, brand overlays, tuning logic.
3. **GitHub Repository**  
   - Documentation, policies, code templates.
4. **Wiki**  
   - User & developer docs, guides, and reference material.

## Data Flow

User → index.html UI → ChatGPT session (via OpenAI API) → GPT responses → UI

## Extensibility

- **Prompts**: Modify system message.
- **Frontend**: Customize CSS/HTML.
