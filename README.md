# Smart India Hackathon Workshop
# Date: 07-03-2025
## Register Number: 212224110001
## Name: AASHIKA JAIN . G
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
The solution should automate and enhance this process by creating a real-world interview with the following key components:

1.Question Relevance: Questions must be aligned with the expertise of the candidate.

2.Response Evaluation: Responses should be evaluated for relevancy and quality.

3.Scoring System: Both questions and responses should be assigned relevance scores, contributing to an overall score reflecting the candidate’s knowledge.

4.Real-time Experience: Simulating a real-life interview experience with ice-breaker questions, followed by in-depth techno-managerial questions based on the candidate's role.

5.Final Score: A quantifiable score to determine the candidate's suitability for the advertised post.

## Proposed Solution / Architecture Diagram

![Colorful Pink Organizational Chart Graph](https://github.com/user-attachments/assets/77498b66-8811-4f08-a698-3d091262f37f)



## Use Cases

![Uploading 1.png…]()

## Technology Stack
1)Frontend:
Framework: React.js, Angular, or Vue.js for building dynamic user interfaces.

UI Components: Material-UI, Bootstrap, or TailwindCSS for fast, responsive UI.

Real-time Communication: WebRTC for video/audio integration.

2)Backend:

Web Framework: Node.js with Express.js or Python with Django/Flask.

Database: PostgreSQL or MySQL for storing interview data, responses, and scoring.

Authentication: JWT for secure login/authentication.

Real-time Communication: Socket.io or Django Channels for handling real-time interactions between interviewer and candidate.

3)AI/NLP:

NLP Models: Analyzing candidate responses and scoring based on relevancy.

Libraries: spaCy or NLTK for text preprocessing.

4)Deployment:

Cloud Hosting: AWS, Google Cloud, or Azure for hosting the application.

Containers: Docker for containerization, making the system portable and scalable.

CI/CD: GitHub Actions or Jenkins for continuous integration and deployment.

## Dependencies

1.Frontend: React.js or Vue.js, Material-UI or Tailwind CSS, WebRTC, Redux or Context API, and Socket.io for real-time communication.

2.Backend: Node.js/Express.js or Python/Django, PostgreSQL or MySQL, JWT/OAuth for authentication, and Socket.io for real-time interactions.

3.AI/NLP: Hugging Face Transformers (BERT, GPT), spaCy, or NLTK for analyzing responses.

4.Deployment: AWS, Google Cloud, or Azure, Docker for containerization, and CI/CD tools like GitHub Actions.

5.Testing: Jest, Mocha, PyTest for unit testing and Cypress/Selenium for end-to-end testing.
