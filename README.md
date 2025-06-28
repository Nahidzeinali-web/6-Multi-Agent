# 📚 Tutorial Summary: LangGraph Multi-Agent System

This tutorial demonstrates:

- **Environment setup**: Load API keys and initialize GPT-4o.
- **Tool definitions**: Create dummy tools for agent communication.
- **Agent creation**:
  - *Addition Expert*: Performs addition and hands off to multiplication expert if needed.
  - *Multiplication Expert*: Performs multiplication and hands off to addition expert if needed.
- **Graph setup**: Build, connect, and compile the LangGraph with these agents.
- **Execution**: Run the graph on a user query combining addition and multiplication.
