# CIRO AI
### Crisis Intelligence and Response Orchestrator

**An AI powered crisis intelligence and response decision support prototype.**

[Live Demo](https://ciro-ai.vercel.app/)

## Project Overview

CIRO AI is a web based simulation project designed to demonstrate how AI agents can support the analysis of emergency scenarios.

Users can submit a simulated incident with its type, location, severity, and number of people affected. The system processes the information through six specialized agent roles and presents an analysis with suggested actions and a response plan.

This project was developed as a Software Engineering project to explore AI integration, multi agent workflows, and crisis decision support.

## Key Features

- Simulated emergency incident dashboard
- Six specialized agent roles
- AI powered incident analysis using Google Gemini
- Risk assessment demonstration
- Suggested response actions
- Recommended resources
- Incident verification status
- React based web interface
- Node.js and Express backend
- Online deployment using Vercel

## Six Agent Roles

| Agent | Responsibility |
|---|---|
| Incident Agent | Summarizes the submitted incident |
| Geo Agent | Processes the location supplied by the user |
| Risk Agent | Demonstrates risk classification using predefined scores |
| Resource Agent | Suggests resources based on the incident type |
| Response Agent | Presents a suggested response plan |
| Verification Agent | Shows verification notes and pending human review |

## System Architecture

The project follows a frontend and backend architecture.

1. The user submits a simulated incident through the React frontend.
2. The frontend sends the incident information to the Express backend.
3. The backend coordinates the six agent roles.
4. Google Gemini generates the incident analysis and response recommendations.
5. The backend returns the results to the frontend.
6. The dashboard displays the analysis and agent outputs.

## Technology Stack

**Frontend**
- React
- Vite
- Tailwind CSS
- Framer Motion
- Three.js
- Recharts
- Leaflet

**Backend**
- Node.js
- Express.js
- Google Gemini API

**Deployment and Version Control**
- GitHub
- Vercel

## Live Demo

Visit the deployed project:

https://ciro-ai.vercel.app/

## Project Repository

The full source code is maintained in a separate private GitHub repository.

This public repository is a project showcase containing documentation and project information.

## Important Disclaimer

CIRO AI is a simulation and decision support prototype developed for educational and demonstration purposes.

All incident scenarios, agent activities, risk scores, and response plans are simulated. The system does not contact emergency services, perform real emergency dispatch, or replace trained emergency professionals.

AI generated recommendations must not be used as the basis for real emergency response decisions.

## Developed By

**Hassan Ali Bangash**

Software Engineering Student

[GitHub Profile](https://github.com/hassan-bangash12)

[Live Project](https://ciro-ai.vercel.app/)
