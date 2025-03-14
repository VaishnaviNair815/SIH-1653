# Smart India Hackathon Workshop
# Date:14.03.2025
## Register Number:212224110058
## Name:Vaishnavi.R.Nair
## Problem Title 
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
1.Role-Based Access System

-> Admin Panel → Manage vacancies, interviewers, and questions

-> Interview Panel (Experts) → Select/customize questions, rate responses

-> Candidates → Participate in AI-driven/mock/live interviews

2.Smart Questioning System

AI-Powered Question Selection:

Ice-breaking → General discussion → Techno-managerial questions

Adaptive difficulty based on candidate performance

Questions fetched dynamically from job-specific database

-> Question Types:

Multiple-Choice Questions (MCQs)

Descriptive/Text-based Answers

Scenario-based / Problem-Solving

Behavioral Questions (HR-based)

-> Question Relevance Matching:

NLP-based expertise analysis to ensure questions align with the candidate’s background

3.AI-Powered Response Evaluation
-> Candidate Answer Analysis:

Natural Language Processing (NLP) & Machine Learning evaluate clarity, relevance, depth

AI checks grammar, coherence, and logical reasoning

Experts rate responses for accuracy

-> Scoring System:

Weighted AI Score + Expert Score

Real-time feedback for improvement

-> Live AI Feedback:

AI suggests how to improve answers in mock interviews

AI-driven speech & sentiment analysis

4.Realistic Boardroom Experience
-> Live Video Interviews (WebRTC / Zoom API)

-> AI Avatar-Based Mock Interviews

-> Real-time Transcription & Answer Grading (Google Speech-to-Text / Whisper AI)

-> Emotion & Tone Analysis (IBM Watson / Google NLP)

5.Post-Interview Analytics & Reporting

-> Detailed Performance Report for Candidates

-> Expert Questioning Analysis (Ensuring Fairness & Relevance)

-> Data Dashboard with Insights


## Proposed Solution / Architecture Diagram
![0b2fe140-a390-4ded-9692-65bebefe0353](https://github.com/user-attachments/assets/32cb6475-1701-462b-8339-e18feb53ee79)


## Use Cases

![a47938fc-8aa0-4a1d-adda-1ce70007e92b](https://github.com/user-attachments/assets/da9af486-112b-4042-8c71-6dbbf4cbed77)

## Technology Stack
Frontend: React.js / Angular / Vue.js

Backend: Node.js / Django / Flask

Database: MySQL / PostgreSQL / MongoDB

AI/NLP: OpenAI API, Google NLP, IBM Watson

Video Integration: WebRTC / Zoom SDK

## Dependencies
react-router-dom → For navigation in React

axios → For handling API requests

socket.io-client → For real-time communication

tailwindcss → For styling the UI

chart.js → For interview performance graphs

