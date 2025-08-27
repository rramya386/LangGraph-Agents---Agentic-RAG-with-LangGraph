# LangGraph-Agents---Agentic-RAG-with-LangGraph
This repository contains an interactive Jupyter Notebook demonstrating how to build **Agentic RAG (Retrieval-Augmented Generation)** workflows using **LangGraph**, **LangChain**, and **LLM tools**. It integrates memory, graph-based control flow, TypedDict state management, and tool usage.

| Concept            | Description                                                  |
| ------------------ | ------------------------------------------------------------ |
| `TypedDict`        | Defines the structure of shared graph state                  |
| `StateGraph`       | Manages nodes and flow across the LangGraph pipeline         |
| `llm.bind_tools()` | Attaches custom Python tools to be used inside LLM calls     |
| `Annotated`        | Adds metadata to elements of state                           |
| `RunnableBinding`  | Chains together multiple steps like retriever + prompt + LLM |
| `Retriever`        | Searches context chunks from vector DB using user input      |
