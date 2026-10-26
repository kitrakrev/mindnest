# MindNest

AI-powered conversation platform with robot control integration. Built at **Cal Hacks 12.0** (Oct 24–26, 2025, San Francisco).

> My first hardware project: an SO-101 robot arm driven from a REST API, playing rock-paper-scissors live on the hackathon floor.

<p align="center">
  <img src="media/so101_demo.gif" width="280" alt="SO-101 arm at Cal Hacks 12.0">
</p>

🎥 **Demo clip (40 s):** [media/so101_calhacks_clip.mp4](media/so101_calhacks_clip.mp4)


## Projects

### 🎭 Chat Simulator (`chat_simulator/`)
Multi-agent AI conversation platform with:
- Dynamic persona creation and management
- Global Meta-Advisor with Letta memory integration
- Real-time conversation simulation
- TLDR summaries (text & video styles)
- Group management

### 🤖 Robot Controller (`bot_code/`)
SO-101 Rock-Paper-Scissors Robot API:
- REST API for robot gesture control
- Rock, Paper, Scissors gestures
- Shake animations and timing controls

## Quick Start

### Chat Simulator
\`\`\`bash
cd chat_simulator
cp .env.example .env  # Add your API keys
uv run main.py
\`\`\`
Visit: http://localhost:8000

### Robot Controller
\`\`\`bash
cd bot_code
uv run api.py
\`\`\`
API: http://localhost:8001

## Features
- Multi-persona AI conversations
- Persistent memory with Letta
- Robot control interface
- Real-time WebSocket updates
- Group-based simulations
