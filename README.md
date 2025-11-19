# 🤖 AI-Based Customer Support Chatbot (PyDatalog Logic System)

This project is an AI-powered expert system chatbot implemented using PyDatalog, a logic-programming library for Python. Instead of machine learning, it uses a rule-based reasoning model to answer user queries with high accuracy. The chatbot identifies keywords, matches them with predefined facts, and delivers instant support responses—just like a real customer care assistant.

## 🌟 Features

💠 Logic-Based Reasoning
Uses Datalog rules and facts to determine the best answer for customer queries.

💠 Automatic Keyword Extraction
Removes stopwords and finds meaningful keywords to understand user intent.

💠 Expandable Knowledge Base
Add or modify facts easily for new customer issues.

💠 Interactive Chat Interface
Smooth conversation experience through a command-line chat loop.

💠 Fast & Lightweight
No ML training required—pure rule-based intelligence.

## 🛠️ Technologies Used

Python 3

PyDatalog (Logic Programming)

Basic NLP Techniques (tokenizing, stopword removal)

Command Line Interface (CLI)

## 🧩 How the Chatbot Works

💠 Knowledge Base Initialization

  Predefined problem–solution pairs are stored as Datalog facts.

💠 User Query Processing

  The chatbot extracts important keywords from the user’s input.

💠 Logical Inference

  PyDatalog searches for matching solutions using rules.

💠 Response Generation

  If a relevant fact is found → chatbot returns the correct reply.

  If not → provides a fallback message.

💠 Continuous Interaction

  Chat remains active until the user types exit, quit, or bye.

## 🔮 Future Scope / Enhancements

Improve NLP using NLTK or spaCy for better intent recognition

Hybrid System combining ML-based intent classification + logic rules

GUI or Web App using Tkinter, Flask, or React

Integrate Speech-to-Text / Text-to-Speech

Advanced Knowledge Graph using Neo4j or RDF

Admin Panel to add/update knowledge base dynamically
