# LangGraph Cookbook

Welcome to the LangGraph Cookbook repository. This repository is dedicated to exploring the main concepts of [LangGraph](https://langchain-ai.github.io/langgraph/) and provides an implementation of a chatbot with a customized workflow.

## Contents

- **Main Concepts**: A detailed guide on the fundamental concepts of LangGraph.
- **Chatbot Implementation**: A practical example of how to implement a chatbot using LangGraph with a customized workflow. The chatbot workflow is divided into two main stages:

    1. **Tool Usage Determination**: A first language model (LLM) decides whether additional tools are needed or if it can respond directly to the query.

    2. **Response Elaboration**: A second language model elaborates the response using the provided context.
