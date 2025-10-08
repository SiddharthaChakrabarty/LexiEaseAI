# LexiEase AI - An AI Powered Dyslexic Support System

**LexiEase AI** is an AI-powered system that offers personalized learning support for individuals with dyslexia. The platform provides dyslexia screening, tailored learning paths, and various assistive tools to improve accessibility and enhance learning outcomes for dyslexic individuals. 

<img width="952" height="533" alt="image" src="https://github.com/user-attachments/assets/cdc28302-987e-4d03-8836-cd8ccdf26cf3" />

---

## Table of Contents

- [Introduction](#introduction)
- [What Problems Does LexiEase AI Solve?](#what-problems-does-lexiease-ai-solve)
- [Installation](#installation)
- [Idea](#idea)
- [Dyslexia Screening Tests](#dyslexia-screening-tests)
  - [Phonological Awareness Test](#1-phonological-awareness-test)
  - [Kaufman Assessment Battery Test](#2-kaufman-assessment-battery-test)
  - [Gray Oral Reading Test (GORT)](#3-gray-oral-reading-test-gort)
- [Personalized Learning Paths](#personalized-learning-paths)
  - [Reading Aloud Support](#1-reading-aloud-support)
  - [Reading Comprehension](#2-reading-comprehension)
  - [Memory Games](#3-memory-games)
  - [Phonological Improvement Assistant](#4-phonological-improvement-assistant)
- [Other Features](#other-features)
  - [AI-Powered Writing Support](#1-ai-powered-writing-support)
  - [AI Chatbot](#2-ai-chatbot)
  - [AI-Powered Document Simplification](#3-ai-powered-document-simplification)
  - [Notes & Mind Map Generation from PDF](#4-notes--mind-map-generation-from-pdf)
- [Technology Stack](#technology-stack)
- [Impact of Dyslexic Support System for Thales](#impact-of-dyslexic-support-system-for-thales)
  - [Core Capabilities](#core-capabilities)
  - [Defence & Security](#defence--security)
  - [Aeronautics & Space](#aeronautics--space)
  - [Cybersecurity & Digital Identity](#cybersecurity--digital-identity)
  - [Cross-Domain Benefits](#cross-domain-benefits)
- [Project Architecture](#project-architecture)
- [User Flow](#user-flow)
- [Snapshots of our Project](#snapshots-of-our-project)

---

## Introduction

Welcome to **LexiEaseAI** – a powerful, AI-driven learning platform designed to enhance cognitive skills, reading abilities, and academic performance through personalized assessments and support tools. Leveraging advanced AI technology, LexiEaseAI offers users tailored tests, interactive learning paths, and engaging resources that cater to their unique learning needs.

Whether you’re aiming to improve phonological awareness, boost reading comprehension, or simplify complex documents, LexiEaseAI is here to make learning accessible, efficient, and enjoyable. With intuitive tools like memory games, mind map generation, and real-time chat assistance, this platform empowers learners of all backgrounds to reach their full potential.

<img width="947" height="533" alt="image" src="https://github.com/user-attachments/assets/c1ae44db-fac8-4b6c-8917-b3df684e2138" />

---

## What Problems Does LexiEase AI Solve?

1. **Limited Access to Dyslexia Screening**  
   Many individuals with dyslexia struggle to get timely and affordable screenings, leading to delayed interventions and missed educational opportunities.

2. **Lack of Personalized Learning Paths**  
   Traditional learning resources are not tailored to the unique needs of dyslexic learners, making it harder for them to achieve their full potential in conventional educational settings.

3. **Insufficient Support Tools for Dyslexic Learners**  
   Dyslexic individuals often lack access to specialized tools, like writing assistants and document simplifiers, that can make reading and learning more accessible and enjoyable.

---

## Installation

1. Clone the Repository
   ```bash
   git clone https://github.com/SiddharthaChakrabarty/LexiEaseAI.git
   cd LexiEaseAI
   ```
2. Frontend Setup
   - Navigate to the frontend folder.
     ```bash
       cd frontend
     ```
   - Install the dependencies.
     ```bash
       npm install
     ```
   - Run the frontend
     ```bash
       npm start
     ```
3. Backend Setup
    - Navigate to the backend folder.
      ```bash
       cd ../backend
      ```
    - Create a virtual environment and activate it.
      ```bash
      python3 -m venv venv
      source venv/bin/activate
      ```
    - Install the required Python packages.
      ```bash
       pip install -r requirements.txt
      ```
    - Run the backend
      ```bash
       python app.py
      ```
---

## Idea

## Dyslexia Screening Tests

<img width="946" height="528" alt="image" src="https://github.com/user-attachments/assets/388cae9c-8371-420c-9903-fad13c83f248" />

### 1. Phonological Awareness Test
- A cognitive test designed to assess the user's ability to identify and manipulate sounds in spoken words.  
- Includes various subtests to measure awareness of phonemes, syllables, and rhymes.  
![Phonological Awareness Test](https://github.com/user-attachments/assets/338a0022-ac5c-4c37-a5ff-0c74a1fb4997)

### 2. Kaufman Assessment Battery Test
- A comprehensive intelligence test that evaluates both verbal and non-verbal cognitive abilities.  
- Provides insights into cognitive strengths and weaknesses, helping tailor learning paths for individuals.  
![Kaufman Assessment Battery Test](https://github.com/user-attachments/assets/87c72380-5e93-4d76-b435-90bbc3e1ddb4)

### 3. Gray Oral Reading Test (GORT)
- A standardized test to assess the fluency and comprehension of oral reading.  
- Users read passages aloud, and the system evaluates speed, accuracy, and comprehension.  
![Gray Oral Reading Test](https://github.com/user-attachments/assets/32ce4a78-2681-47a1-b8e1-9768aaae6ec2)

---

## Personalized Learning Paths

<img width="946" height="532" alt="image" src="https://github.com/user-attachments/assets/c467f4ed-4dc3-40bd-910b-475dca7d0eed" />

### 1. Reading Aloud Support
- Text-to-speech functionality to read out content for users, particularly those with visual impairments or learning disabilities.  
- Helps improve literacy and comprehension by listening to the content aloud.  
![Reading Aloud Support](https://github.com/user-attachments/assets/62c9fb16-3eed-4c51-89e8-87c78ccd63f2)

### 2. Reading Comprehension
- Tests and exercises to assess a user’s understanding of written text.  
- Users answer questions based on passages, helping track and improve their comprehension skills.  
![Reading Comprehension](https://github.com/user-attachments/assets/0f2d0bf5-4829-4851-a42e-47dadffb59c2)

### 3. Memory Games
- Interactive memory-enhancing games designed to boost cognitive function and memory retention.  
- Games focus on recall, recognition, and matching activities, making learning engaging and fun.  
![Memory Games](https://github.com/user-attachments/assets/4e06049b-0bc4-4ad4-9001-83668c161400)

### 4. Phonological Improvement Assistant
- A virtual assistant to help users improve their phonological skills.  
- Provides feedback, exercises, and tailored tips to enhance sound recognition and manipulation abilities.  
![Phonological Improvement Assistant](https://github.com/user-attachments/assets/f51d5ece-d722-42b3-8cac-5c62573db2df)

---

## Other Features

<img width="947" height="532" alt="image" src="https://github.com/user-attachments/assets/043feb34-a031-41b1-99d9-7a1df510d8b5" />

### 1. AI-Powered Writing Support
- Extracts text from documents or images using a fine-tuned OCR pipeline.  
- Uses DistilBERT to identify mistakes, restructure sentences, improve coherence, and produce polished versions of text.  
![AI-Powered Writing Support](https://github.com/user-attachments/assets/c3b44b4f-7503-4e2b-a605-c08873f44f52)

### 2. AI Chatbot
- Conversational AI designed to answer queries, provide study assistance, or explain concepts in real-time.  
![AI Chatbot](https://github.com/user-attachments/assets/f8208a6b-355b-473a-bbcc-2591b5817dd1)

### 3. AI-Powered Document Simplification
- Simplifies complex documents by rephrasing and summarizing content without losing essential meaning.  
- Helps users better understand dense information by breaking it into digestible chunks.  
![AI-Powered Document Simplification](https://github.com/user-attachments/assets/72492cd7-b6e9-4780-986b-269100bc71dc)

### 4. Notes & Mind Map Generation from PDF
- Converts textual content from PDFs into structured mind maps.  
- Provides visual representation of concepts, aiding understanding of relationships and ideas.  
![Notes & Mind Map Generation](https://github.com/user-attachments/assets/0b32bd4a-81ab-4ce1-8537-5436a121ccba)

---

## Technology Stack

| Layer / Component | Technologies / Libraries | 
|-------------------|--------------------------|
| Frontend | React, Tailwind CSS |
| Backend | Flask (Python) | 
| Machine Learning / NLP | PyTorch, Hugging Face Transformers (DistilBERT, custom fine-tuning), scikit-learn | 
| Speech & Audio | gTTS & SpeechRecognition(JS) | 
| OCR & Computer Vision | Tesseract, EasyOCR, OpenCV | 
| Document Processing | PyPDF | 
| Personalization / Recommender | Custom rule-based engine | 
| Database & Storage | MySQL | 
| Authentication & Security | OAuth2, bcrypt, JWT |
| Accessibility | OpenDyslexic fonts, Dyslexic-friendly spacing | 

## Impact of Dyslexic Support System for Thales

> **Focus:** how **LexiEase** (dyslexic support) delivers concrete value across Thales’s **Defence & Security**, **Aeronautics & Space**, and **Cybersecurity & Digital Identity** domains.

<img width="945" height="531" alt="image" src="https://github.com/user-attachments/assets/0562c2c3-1685-4eb8-bc17-244a12140f3b" />

---

### Core Capabilities
- **Document simplification**, **text-to-speech (TTS)**, and **multimodal presentation** (audio + text + visuals)  
- **Personalized spaced-repetition learning**  
- **Side-by-side simplified + original documents** for legal/technical fidelity  
- **Comprehension analytics** to identify confusion points  
- **Secure, on-prem or hybrid deployments** with **audit trails**

---

### Defence & Security
- **Faster mission readiness:** Simplified procedures and TTS shorten time-to-proficiency for dyslexic personnel.  
- **Reduced human error:** Clear SOPs and dual-view documents minimize misinterpretation in critical operations.  
- **Inclusive workforce:** Tailored training improves recruitment, retention, and access to neurodiverse talent.  
- **Secure assessments:** On-prem deployments and audit logs maintain classification and medico-legal compliance.

---

### Aeronautics & Space
- **Reliable maintenance & manuals:** Dyslexia-friendly versions of complex technical content reduce maintenance errors.  
- **Safer crew responses:** Multimodal emergency procedures accelerate comprehension and reaction times.  
- **Human factors insight:** Analytics highlight confusion points to enhance cockpit documentation and design.  
- **Faster certification:** Personalized learning paths shorten simulator and qualification timelines.

---

### Cybersecurity & Digital Identity
- **Clear identity flows:** Simplified onboarding and admin documentation prevent configuration errors.  
- **Phishing resilience:** Personalized microlearning and spaced repetition improve detection of social engineering.  
- **Secure integration:** Compatible with SSO/ABAC and encrypted storage—ensuring accessibility without compromising security.  
- **Privacy alignment:** Consent, anonymization, and audit features support compliance in identity-linked data use.

---

### Cross-Domain Benefits
- **Safety & mission assurance:** Simplified content reduces errors that could trigger safety incidents.  
- **Workforce resilience:** Enables continuous upskilling and neurodiverse inclusion.  
- **Operational savings:** Lower instructor time, fewer remediation sessions, and reduced rework.  
- **Flexible deployment:** Cloud, hybrid, or fully on-prem—including air-gapped environments.

---

**Bottom Line:**  
**LexiEase** transforms complex technical, operational, and cybersecurity materials into **accessible, secure, and audit-ready formats**—empowering dyslexic personnel to perform safely, efficiently, and confidently across Thales’s high-stakes domains.

---




## Project Architecture

<img width="4484" height="3128" alt="image" src="https://github.com/user-attachments/assets/9bfc7e71-9162-4422-8976-3b9c6853f94c" />

## User Flow
![image](https://github.com/user-attachments/assets/a1a63b5f-5e55-4033-a5ce-711da18bca2f)


## Snapshots of our Project
![image](https://github.com/user-attachments/assets/bb52cd20-16fe-49f6-b95c-e973a44e52fe)
![image](https://github.com/user-attachments/assets/ad438d3c-43c7-4b14-b9a6-f58ab63f38df)
![image](https://github.com/user-attachments/assets/20578bf6-bde3-4c59-b46d-7ef233cd8803)
![image](https://github.com/user-attachments/assets/364152b4-7555-4adb-ba5b-e61b012b4236)
![image](https://github.com/user-attachments/assets/f09e8b34-cf84-4ba0-bdfd-98d519aeaa49)
![image](https://github.com/user-attachments/assets/046948f9-dc73-461a-9700-411e6ed37034)









     

