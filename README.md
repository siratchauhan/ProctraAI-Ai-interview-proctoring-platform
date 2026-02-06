# ProctraAI-Ai-interview-proctoring-platform

An AI-powered web platform designed to conduct secure and fair online interviews with real-time AI assistance and advisory proctoring.

This project focuses on using AI to support interviewers by providing live transcription, automated summaries, contextual Q&A, and integrity monitoring signals — without automatically disqualifying candidates.

---

## Key Features

- Live video interviews using WebRTC
- Real-time AI-powered speech transcription
- Automated interview summaries
- Context-aware AI Q&A based on interview transcripts
- Advisory integrity monitoring:
  - Face presence detection
  - Multiple face detection
  - Gaze deviation monitoring
  - Unusual audio pattern detection
  - Browser tab switching detection
- Explicit user consent and ethical AI practices
- Secure session management and role-based access

---

## Project Scope

This repository contains **system-level documentation** created as part of an architectural and design submission.  
The focus is on **requirements definition, system design, and implementation planning**, not on a fully deployed product.

---

## Repository Contents

- `requirements.md` – Functional and non-functional system requirements with acceptance criteria
- `design.md` – System architecture, component design, and correctness properties
- `tasks.md` – Step-by-step implementation and testing plan (optional)

---

## Technology Stack (Proposed)

- Frontend: Next.js, React, Tailwind CSS
- Backend: Node.js, REST APIs
- Real-time Communication: WebRTC
- AI Services: OpenAI (Transcription, Summarization, Q&A)
- Database: PostgreSQL
- Caching & Sessions: Redis
- Cloud Deployment: AWS / GCP (planned)

---

## Ethical & Privacy Considerations

- All integrity signals are **advisory only**
- No automatic candidate disqualification
- Explicit user consent required before AI processing
- AI insights include disclaimers and encourage human judgment

---

## Status

📌 **Documentation & design submission complete**  
🚧 Implementation planned as future work

---

## Author

Sirat Chauhan
