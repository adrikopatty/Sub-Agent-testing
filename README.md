# Multi-Agent Trip Planner 🌍

A production-ready multi-agent system implementing AI  file-based orchestration approach for trip planning. This system demonstrates how specialized AI agents can work together through coordinated workflows without conflicts.

## 🎯 Overview

This project implements a **multi-agent trip planning system** where specialized AI agents collaborate to create comprehensive travel plans. Based on insights from AI Jason's research on sub-agent orchestration, the system uses file-based communication to prevent agent conflicts and ensure reliable coordination.

## 🏗️ Architecture

### Core Components

- **🎯 Coordinator Agent**: Main orchestrator that analyzes user requests and delegates tasks
- **🛂 Visa Agent**: Specialist in visa requirements and documentation  
- **✈️ Flight Agent**: Expert in flight booking and travel logistics
- **🏨 Hotel Agent**: Specialist in accommodations and local insights

### Communication Methods

1. **Variable-Based**: Direct agent-to-agent communication through shared variables
2. **File-Based**: AI Jason's approach using task files and result files for coordination

## 📁 Project Structure

```
Multi-Agent-Trip-Planner/
├── Notebooks/
│   ├── trip_planner_demo.ipynb     # Main demonstration notebook
│   ├── prompts/                    # Agent prompt definitions
│   │   ├── coordinator_prompt.md
│   │   ├── visa_agent_prompt.md
│   │   ├── flight_agent_prompt.md
│   │   └── hotel_agent_prompt.md
│   ├── tasks/                      # Task files for agent coordination
│   │   ├── visa_task.md
│   │   ├── flight_task.md
│   │   └── hotel_task.md
│   └── docs/                       # Agent result files
│       ├── visa_result.md
│       ├── flight_result.md
│       └── hotel_result.md
└── README.md
```

## 🚀 Features

### ✅ Multi-Agent Coordination
- **Specialized Expertise**: Each agent focuses on their domain
- **Conflict Prevention**: File-based communication prevents overlapping work
- **Scalable Architecture**: Easy to add new specialist agents

### ✅ Dual Communication Modes
- **Fast Variable-Based**: For quick prototyping and testing
- **Robust File-Based**: For production workflows and transparency

### ✅ Source Transparency
- **Citation Requirements**: All agents must provide sources for their information
- **Verifiable Results**: Users can fact-check recommendations
- **Trust Building**: Clear data provenance for all suggestions

### ✅ Production Ready
- **Error Handling**: Robust file operations and API calls
- **Modular Design**: Easy to modify and extend
- **Documentation**: Comprehensive prompts and examples

## 🛠️ Setup

### Prerequisites
- Python 3.8+
- OpenAI API key
- Jupyter Notebook

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/multi-agent-trip-planner.git
cd multi-agent-trip-planner
```

2. **Install dependencies**
```bash
pip install openai python-dotenv jupyter
```

3. **Setup environment variables**
Create a `.env` file in the root directory:
```
OPENAI_API_KEY=your_openai_api_key_here
```

4. **Launch Jupyter Notebook**
```bash
jupyter notebook Notebooks/trip_planner_demo.ipynb
```

### Modifying Workflows

- **Change Trip Parameters**: Update test scenarios
- **Adjust Agent Roles**: Modify prompt files
- **Add New Communication**: Extend file-based patterns

