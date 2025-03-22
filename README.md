# Mosaic AI Business Solution

<a id="readme-top"></a>

<details>
<summary>Table of Contents</summary>
<ol>
<li><a href="#about-the-project">About the Project</a></li>
<ul>
<li><a href="#business-overview">Business Overview</a></li>
<li><a href="#solution-architecture">Solution Architecture</a></li>
<li><a href="#tools-and-technologies">Tools and Technologies</a></li>
<li><a href="#deployment">Deployment</a></li>
</ul>
</ol>
</details>

---

## About the Project

The **Mosaic AI Business Solution** is designed to provide a seamless AI-driven experience using natural language processing (NLP) capabilities and machine learning algorithms. This system integrates multiple services to offer intelligent chat interactions, personalized recommendations, and data analytics.

**Pre-requisite:**
This is the link to the snag platform: [P177A](https://p177a.com)

---

## Business Overview

The solution leverages AI to summarize conversations, store chat histories, and provide personalized experiences. By combining AI models with a robust frontend and backend, the platform offers end-users a powerful conversational assistant.

**Key Features:**
- AI-based summarization
- Chat history management
- Personalized recommendations
- Scalable microservices
- Real-time analytics

---

## Solution Architecture

The architecture consists of multiple interconnected components:

1. **Frontend (Mosaic Web Client)**
    - Built using Angular and hosted on the cloud.
    - Provides a responsive user interface.
    - Accessible via this link: [Mosaic Web Client](https://mosaic-web-client-v2-s7yq7.ondigitalocean.app)

2. **Backend (Mosaic Concierge)**
    - Developed in Python.
    - Manages business logic, API requests, and AI model interactions.

3. **AI Model Server**
    - Hosts the language model (LLM) for conversational AI.
    - Supports chat history summarization and personalized suggestions.

4. **Summarizer Service**
    - Custom AI service to summarize chat interactions and generate insights.

5. **Data Management**
    - Stores chat histories securely.
    - Utilizes the Mosaic Configs for personalized settings.





---

## Tools and Technologies

- **Frontend:** Angular, Tailwind CSS
- **Backend:** Python (Flask/FastAPI)
- **AI Services:** ChatGPT, Custom LLM model, AI Summarizer
- **Hosting:** Digital Ocean, Heroku, Local server
- **Containerization:** Docker
- **CI/CD:** GitHub Actions

---

## Deployment

The Mosaic AI solution is deployed across different environments:

- **Frontend Production:** [Mosaic Web Client on Digital Ocean](https://mosaic-web-client-v2-s7yq7.ondigitalocean.app)
- **Backend API:** Cloud based Hosting
- **Staging Environments:** Managed using Heroku and Local Server for testing

<p align="right">(<a href="#readme-top">Back to top</a>)</p>

