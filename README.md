# LangChain Agents Learning Repository

A collection of hands-on exercises, examples, and notes documenting my journey of learning **LangChain**, **LangGraph**, **LLM integrations**, **tool calling**, **conversation memory**, and **structured outputs**.

---

## 🚀 What I Learned

### 🤖 LangChain Agents

* Creating agents using `create_agent()`
* Understanding agent execution flow
* Agent reasoning and tool selection
* Building agent-driven workflows
* Working with agent state and context

---

### 🧠 LLM Integrations

Integrated multiple model providers with LangChain:

#### OpenAI

* GPT models
* Model configuration
* API integration

#### Groq

* Fast inference models
* LangChain integration
* Provider-specific configurations

#### Google Generative AI

* Gemini models
* Prompt execution
* Response handling

---

### 🛠️ Tool Calling

Built and used custom tools with LangChain.

Topics covered:

* Creating tools using decorators
* Tool schemas
* Tool invocation
* Agent-tool interaction
* Multi-tool workflows

Example tools:

* Calculator tool
* Utility functions
* Custom business logic tools

---

### 💬 Message Management

Learned how LangChain handles different message types:

* `HumanMessage`
* `AIMessage`
* `SystemMessage`
* `ToolMessage`

Understanding message flow:

```text
User → Agent → Tool → Agent → User
```

---

### 📝 Conversation History & Memory

Implemented conversation memory using:

* Chat history
* Checkpointers
* Thread-based conversations
* Session persistence

Concepts explored:

* Maintaining context
* State persistence
* Conversation continuity
* Memory management

---

### 📦 Structured Output

Generated reliable structured responses using Pydantic models.

Example:

```python
from pydantic import BaseModel

class ContactInfo(BaseModel):
    name: str
    email: str
    phone: str
```

Topics covered:

* Schema definition
* Validation
* Typed responses
* JSON generation
* Agent structured outputs

Benefits:

* Consistent responses
* Type safety
* Easier parsing
* Better reliability

---

### 👨‍💻 Human-in-the-Loop Workflows

Learned how to implement:

* Interrupts
* Resume commands
* Approval workflows
* Reject/Edit/Approve patterns
* Checkpoint recovery

---

### 🧾 Memory Optimization

Explored techniques such as:

* Summarization Middleware
* Message trimming
* Token management
* Long conversation handling

---

## 📚 Key Concepts Learned

* Agents vs Chains
* Tool Calling
* Function Calling
* Prompt Engineering
* Structured Outputs
* Conversation Memory
* Checkpointing
* Human Feedback Loops
* Token Usage
* Context Windows
* Multi-Model Integrations

---

## 🛠️ Tech Stack

* Python
* LangChain
* LangGraph
* OpenAI
* Groq
* Google Generative AI
* Pydantic

---

## 🎯 Learning Outcomes

Through this repository, I gained practical experience in:

* Building AI agents
* Integrating multiple LLM providers
* Creating and using tools
* Managing conversation state
* Producing structured outputs
* Implementing human approval workflows
* Optimizing context and memory handling

---


## 📌 Repository Purpose

This repository serves as a personal learning log and reference for understanding how modern AI agents are built using LangChain and the broader LLM ecosystem.

---

## 🙏 Acknowledgements

A significant portion of the concepts and hands-on examples in this repository were learned through the tutorials and courses by **Krish Naik**. His content provided a practical introduction to LangChain, LangGraph, LLM integrations, agent workflows, memory management, and structured outputs.

This repository represents my personal notes, experiments, implementations, and understanding developed while following and practicing these concepts.
