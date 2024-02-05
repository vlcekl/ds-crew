# Project Name: AI Collaborative Agents System

## Overview
This project leverages the LangChain and CrewAI frameworks to create an AI system composed of specialized agents working collaboratively to perform complex tasks such as statistical/causal analysis and decision-making. By integrating semantic analysis, data preprocessing, statistical modeling, and decision analysis, our system aims to provide comprehensive insights and actionable recommendations from diverse datasets.

## Features
- **Modular AI Agents**: Individual agents dedicated to specific tasks like data preprocessing, statistical analysis, causal inference, decision analysis, and semantic analysis.
- **Collaborative Workflow**: Utilizes CrewAI to enable agents to work together as a team, sharing information and tasks to achieve complex objectives efficiently.
- **Incremental Knowledge Base Updating**: Supports continuous learning and updating of the system's knowledge base, ensuring decisions are based on the latest available information.
- **Custom Tools Integration**: Incorporates custom tools for tasks such as data visualization and external data retrieval, enhancing the agents' capabilities.

[Detailed agent descriptions](agents/README.md)

## Getting Started

### Prerequisites
Ensure you have Python 3.8+ installed on your system. Some knowledge of LangChain, CrewAI, and machine learning concepts is beneficial but not strictly necessary.

### Installation
1. Clone the repository:
   ```
   git clone https://github.com/vlcekl/ds-crew.git
   ```
2. Navigate to the project directory:
   ```
   cd project-name
   ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

### Quickstart Guide
Refer to the `notebooks/quickstart_guide.ipynb` for a step-by-step introduction to setting up and running a basic agent crew.

## Usage
- **Defining Agents**: Create new agents by extending the base Agent class in the `agents/` directory, specifying their roles and capabilities.
- **Creating Crews**: Combine agents into crews within the `crew/` directory, defining the collaborative tasks and objectives.
- **Running the System**: Execute the main crew script to start the system:
  ```
  python crew/main_crew.py
  ```

## Development
Feel free to contribute to the project by submitting pull requests or opening issues for bugs, suggestions, or enhancements.

## Testing
Run the tests to ensure the system's integrity:
```
pytest tests/
```

## Documentation
For more detailed information on LangChain and CrewAI, visit the official documentation:
- LangChain: [LangChain Documentation](https://python.langchain.com/docs/get_started/introduction)
- CrewAI: [CrewAI Guide](https://docs.crewai.com/)

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Thanks to the LangChain and CrewAI teams for providing the frameworks that made this project possible.
- Special thanks to all contributors who have helped shape this project.
