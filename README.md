# AWS_Cloud_Labs

# 1. Building Generative AI Workflows with Amazon Bedrock: using AWS Bedrock Flows to build intelligent generative AI workflows, manage prompts, and deploy AI-driven agents for dynamic user interactions

This project covers the development of an AI-powered support system using Amazon Bedrock. It involves working with Bedrock’s core capabilities—prompt management, Prompt Flows, Bedrock Agents, Knowledge Bases, and foundational models—to build intelligent, context-aware workflows.

The system integrates Bedrock with AWS services such as Lambda for query categorization and Amazon RDS for storing embeddings and enabling efficient retrieval. Dynamic Prompt Flows are designed to adapt based on query intent and complexity, ensuring accurate and personalized responses.

A full support workflow is implemented, where Bedrock Agents handle user questions, provide information, and assist with tasks like infrastructure setup and troubleshooting.

Overall, the work demonstrates how LLMs, retrieval components, and serverless AWS infrastructure can be combined to create scalable, AI-driven applications.

<img width="1156" height="444" alt="image" src="https://github.com/user-attachments/assets/74004782-791b-4937-bf30-4ca3a7be4f3d" />


# 2. Building Serverless GenAI Application with Amazon Bedrock: serverless GenAI question-answering application using Amazon Bedrock, Aurora PostgreSQL, Lambda, API Gateway, and Amplify

This project focuses on building an end-to-end serverless GenAI application using Amazon Bedrock. It covers the creation of a knowledge base using an Amazon embedding model, transforming raw data into vector representations and storing the embeddings in an Amazon Aurora PostgreSQL database for structured, efficient retrieval.

The workflow includes configuring Bedrock Guardrails to enforce responsible AI output and integrating these with a Bedrock Agent powered by the Amazon Premier model. A Lambda function is implemented to interface with the Agent, retrieve relevant context from the database, and process user queries. An API Gateway is set up to invoke this Lambda function and handle incoming requests.

The project also includes deploying a React web application via AWS Amplify, enabling a seamless connection between the frontend interface and the backend GenAI pipeline.

Overall, the work demonstrates how Knowledge Bases, Guardrails, serverless components, and foundational models within Amazon Bedrock can be integrated with AWS services like Lambda, API Gateway, and Aurora to deliver a fully functional, AI-powered question-answering system.

<img width="1152" height="616" alt="image" src="https://github.com/user-attachments/assets/0f3de6e3-a159-4807-9d13-71b78ac5a43e" />



