### Recruiter Workflow Agent

This project demonstrates how to build an AI-powered recruitment workflow using LangGraph, LangChain, and Groq LLMs.

The agent automatically:

Categorizes candidate applications into Entry-level, Mid-level, or Senior-level

Matches skills against a Python Developer job description

Routes candidates to the correct outcome:

Schedule HR Interview

Escalate to Recruiter

Reject Application

The workflow is represented as a graph, making the candidate evaluation process transparent and easy to modify.
![alt text](image-1.png)

#### 🚀 Features

Stateful Graph: Each step in the pipeline enriches the candidate’s application state.

Experience Categorization: Uses LLMs to determine seniority.

Skill Matching: Matches candidate skills to the job requirements.

Automated Decision Routing: Candidates are either shortlisted, escalated, or rejected.

Graph Visualization: View the workflow structure using Mermaid or Graphviz.
