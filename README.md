# Wynby-Chatbot
# 📈 Stock Analytics Chatbot

## Overview

The Stock Analytics Chatbot is an AI-powered conversational application developed during my internship at WynbyTech. The system enables users to interact with stock trading and portfolio data using natural language, eliminating the need for manual database queries or complex reporting tools.

Built using Python, Streamlit, Neo4j, and OpenAI APIs, the chatbot retrieves relevant trading information and presents insights in a user-friendly conversational format.

---

## Problem Statement

Business users often need quick access to stock trading information such as:

- Profit & Loss (PnL)
- Trade history
- Order details
- Stock-specific transactions
- Portfolio summaries

Traditionally, retrieving this information requires navigating dashboards or writing database queries.

This project simplifies the process by allowing users to ask questions in plain English.

---

## Features

### Natural Language Queries

Users can ask questions such as:

```text
What is my total PnL?
```

```text
Show all orders placed on 2024-06-06
```

```text
Give me details of stock transactions for today
```

### AI-Powered Responses

The chatbot uses OpenAI APIs to:

- Understand user intent
- Interpret natural language requests
- Generate human-readable responses

### Neo4j Integration

Trading and stock-related information is stored in Neo4j.

The chatbot retrieves relevant data and presents it through an intuitive conversational interface.

### Interactive Dashboard

Built with Streamlit for:

- Real-time interaction
- Easy navigation
- Fast prototyping
- User-friendly experience

---

## System Architecture

```text
User
 ↓
Streamlit Interface
 ↓
Python Backend
 ↓
OpenAI API
 ↓
Neo4j Database
 ↓
Retrieved Trading Data
 ↓
Generated Response
 ↓
User
```

---

## Technology Stack

| Component | Technology |
|------------|------------|
| Frontend | Streamlit |
| Backend | Python |
| Database | Neo4j |
| AI Layer | OpenAI API |
| Data Processing | Pandas, NumPy |
| Version Control | Git & GitHub |

---

## Workflow

1. User enters a natural language query through the Streamlit interface.
2. The application processes the query using OpenAI APIs.
3. Relevant trading information is retrieved from Neo4j.
4. Retrieved data is formatted and passed back to the LLM.
5. The chatbot generates a user-friendly response.
6. Results are displayed as conversational text or structured tables.

---

## Key Responsibilities

During the internship, my contributions included:

- Integrating Streamlit UI components
- Connecting Neo4j with the chatbot workflow
- Handling OpenAI API interactions
- Designing conversational response flows
- Testing chatbot responses and retrieval logic
- Improving user experience and response quality

---

## Challenges Faced

One of the main challenges was ensuring that different user phrasings resulted in accurate retrieval of relevant information.

For example:

```text
What is my total PnL?
```

and

```text
How much profit have I made?
```

should produce consistent results.

This required careful testing of prompts, retrieval logic, and response formatting.

---

## Key Learnings

This project helped me understand:

- Building end-to-end AI applications
- Integrating LLMs with enterprise data sources
- Prompt engineering concepts
- Database integration with AI systems
- User-centered AI design
- The importance of retrieval quality in conversational systems

---

## Future Improvements

Potential enhancements include:

- Conversational memory
- Multi-turn interactions
- Advanced portfolio analytics
- Response validation mechanisms
- Performance monitoring and evaluation metrics
- Role-based access control

---

## Impact

The chatbot demonstrates how AI can make complex business data more accessible by enabling users to interact with enterprise information through natural language rather than traditional querying methods.

---

## Resume Summary

Developed an AI-powered stock analytics chatbot using Streamlit, Neo4j, Python, and OpenAI APIs, enabling natural-language access to trading and portfolio data while improving accessibility of business insights for non-technical users.
