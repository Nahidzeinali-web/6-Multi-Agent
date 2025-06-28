Dummy Example: Multi-Agent System with LangGraph

1️⃣ Setup

Load environment variables and set the API key.

2️⃣ Initialize Model

Create a GPT-4o instance.

3️⃣ Define Tools

Create dummy tools like transfer_to_addition_expert() and transfer_to_multiplication_expert() that simply print messages.

4️⃣ Bind Tools

Attach one of the dummy tools to the model.

5️⃣ Create Agents

Write dummy agent functions:

Addition Expert: prints "I am the addition expert" and optionally passes control to multiplication expert.

Multiplication Expert: prints "I am the multiplication expert" and optionally passes back to addition expert or finishes.

6️⃣ Build Graph

Add both dummy agents to a LangGraph state graph and define transitions.

7️⃣ Test

Run the graph with a dummy input like "What is 2 + 2?" and observe printed messages showing how agents pass tasks between each other.

