# LexiEase AI - An AI Powered Dyslexic Support System

**LexiEase AI** is an AI-powered system that offers personalized learning support for individuals with dyslexia. The platform provides dyslexia screening, tailored learning paths, and various assistive tools to improve accessibility and enhance learning outcomes for dyslexic individuals. 

## 📑 Table of Contents

| Serial No. | Section Links                                                                                                                                                     |
|------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1          | [Introduction](#introduction)                                                                                                                                    |
| 2          | [What Problems Does LexiEase AI Solve?](#-what-problems-does-lexiease-ai-solve)                                                                                   |
| 3          | [Installation](#installation)                                                                                                                                    |
| 4          | [Key Features](#key-features)                                                                                                                                    |
|            | - [Phonological Awareness Test](#1-phonological-awareness-test)                                                                                                  |
|            | - [Kaufman Assessment Battery Test](#2-kaufman-assessment-battery-test)                                                                                          |
|            | - [Gray Oral Reading Test (GORT)](#3-gray-oral-reading-test-gort)                                                                                                |
|            | - [Personalized Learning Path](#4-personalized-learning-path)                                                                                                    |
|            | - [AI-Powered Document Simplification](#5-ai-powered-document-simplification)                                                                                    |
|            | - [Notes Generation](#6-notes-generation)                                                                                                                        |
|            | - [Mind Map Generation from PDF](#7-mind-map-generation-from-pdf)                                                                                                |
|            | - [AI Chatbot](#8-ai-chatbot)                                                                                                                                   |
|            | - [Reading Aloud Support](#10-reading-aloud-support)                                                                                                            |
|            | - [Reading Comprehension](#11-reading-comprehension)                                                                                                             |
|            | - [Memory Games](#12-memory-games)                                                                                                                               |
|            | - [Phonological Improvement Assistant](#13-phonological-improvement-assistant)                                                                                   |
| 5          | [Project Architecture](#project-architecture)                                                                                                                    |
| 6          | [User Flow](#user-flow)                                                                                                                                          |
| 7          | [How It Works](#how-it-works)                                                                                                                                    |
| 8          | [Snapshots of our Project](#snapshots-of-our-project)                                                                                                            |
| 9          | [Technology Stack](#technology-stack)                                                                                                                            |
| 10         | [Impact and Benefits for Users](#-impact-and-benefits-for-users)                                                                                                 |
| 11         | [Technology Comparison](#-technology-comparison)                                                                                                                 |
| 12         | [Business Relevance & Adoption Model](#-business-relevance--adoption-model)                                                                                      |



## Introduction

Welcome to **LexiEaseAI** – a powerful, AI-driven learning platform designed to enhance cognitive skills, reading abilities, and academic performance through personalized assessments and support tools. Leveraging advanced AI technology, LexiEaseAI offers users tailored tests, interactive learning paths, and engaging resources that cater to their unique learning needs.

Whether you’re aiming to improve phonological awareness, boost reading comprehension, or simplify complex documents, LexiEaseAI is here to make learning accessible, efficient, and enjoyable. With intuitive tools like memory games, mind map generation, and real-time chat assistance, this platform empowers learners of all backgrounds to reach their full potential.


Start your journey with LexiEaseAI today, and unlock the power of personalized, AI-enhanced education!



## 🌟 What Problems Does LexiEase AI Solve?

1. **Limited Access to Dyslexia Screening**  
   Many individuals with dyslexia struggle to get timely and affordable screenings, leading to delayed interventions and missed educational opportunities.

2. **Lack of Personalized Learning Paths**  
   Traditional learning resources are not tailored to the unique needs of dyslexic learners, making it harder for them to achieve their full potential in conventional educational settings.

3. **Insufficient Support Tools for Dyslexic Learners**  
   Dyslexic individuals often lack access to specialized tools, like writing assistants and document simplifiers, that can make reading and learning more accessible and enjoyable.


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

## Key Features

### 1. **Phonological Awareness Test**
   - A cognitive test designed to assess the user's ability to identify and manipulate sounds in spoken words. 
   - Includes various subtests to measure awareness of phonemes, syllables, and rhymes.
     <img width="3964" height="1644" alt="image" src="https://github.com/user-attachments/assets/338a0022-ac5c-4c37-a5ff-0c74a1fb4997" />


### 2. **Kaufman Assessment Battery Test**
   - A comprehensive intelligence test that evaluates both verbal and non-verbal cognitive abilities.
   - Provides insights into cognitive strengths and weaknesses, helping tailor learning paths for individuals.
     <img width="3764" height="1632" alt="image" src="https://github.com/user-attachments/assets/87c72380-5e93-4d76-b435-90bbc3e1ddb4" />


### 3. **Gray Oral Reading Test (GORT)**
   - A standardized test to assess the fluency and comprehension of oral reading.
   - Users read passages aloud, and the system evaluates speed, accuracy, and comprehension.
     <img width="2844" height="1568" alt="image" src="https://github.com/user-attachments/assets/32ce4a78-2681-47a1-b8e1-9768aaae6ec2" />


### 4. **Personalized Learning Path**
   - AI-driven system that creates a custom learning journey for users based on their skill level, preferences, and performance.
   - Adaptive learning that evolves with user progress, helping them improve effectively.
     <img width="2920" height="1604" alt="image" src="https://github.com/user-attachments/assets/89a50dee-fb04-43ca-b767-9c8488b64856" />


### 5. **AI-Powered Document Simplification**
   - Uses AI to simplify complex documents by rephrasing and summarizing content without losing essential meaning.
   - Helps users better understand dense information by breaking it into simpler, digestible chunks.
   - <img width="2284" height="616" alt="image" src="https://github.com/user-attachments/assets/72492cd7-b6e9-4780-986b-269100bc71dc" />


### 6. **Notes & Mind Map Generation from PDF**
   - Converts textual content from PDFs into a structured mind map.
   - Provides a visual representation of concepts, helping users grasp relationships and concepts more effectively.
   <img width="2928" height="884" alt="image" src="https://github.com/user-attachments/assets/0b32bd4a-81ab-4ce1-8537-5436a121ccba" />


### 7. **AI Chatbot**
   - A conversational AI chatbot designed to answer user queries, provide study assistance, or explain concepts.
   - It interacts in real-time, ensuring quick access to information or help as needed.
     <img width="1804" height="964" alt="image" src="https://github.com/user-attachments/assets/f8208a6b-355b-473a-bbcc-2591b5817dd1" />

### 8. **AI Powered Writing Support**
   - The system extracts text from documents or images with a fine-tuned OCR pipeline and runs DistilBERT to automatically identify mistakes so users can see what's wrong quickly.
   - Using DistilBERT again in a refinement loop, the feature improves coherence and fluency—restructuring sentences, fixing errors, and producing a cleaner, more polished version of the original text.
   <img width="1268" height="928" alt="image" src="https://github.com/user-attachments/assets/c3b44b4f-7503-4e2b-a605-c08873f44f52" />


### 8. **Reading Aloud Support**
   - Text-to-speech functionality to read out content for users, particularly those with visual impairments or learning disabilities.
   - Helps improve literacy and comprehension by listening to the content aloud
     <img width="3364" height="1688" alt="image" src="https://github.com/user-attachments/assets/62c9fb16-3eed-4c51-89e8-87c78ccd63f2" />


### 9. **Reading Comprehension**
   - Tests and exercises to assess a user’s understanding of written text.
   - Users answer questions based on passages, helping track and improve their comprehension skills.
     <img width="2244" height="1684" alt="image" src="https://github.com/user-attachments/assets/0f2d0bf5-4829-4851-a42e-47dadffb59c2" />


### 10. **Memory Games**
   - Interactive memory-enhancing games designed to boost cognitive function and memory retention.
   - Games focus on recall, recognition, and matching activities, making learning engaging and fun.
     <img width="2484" height="2048" alt="image" src="https://github.com/user-attachments/assets/4e06049b-0bc4-4ad4-9001-83668c161400" />


### 11. **Phonological Improvement Assistant**
   - A virtual assistant to help users improve their phonological skills.
   - Provides feedback, exercises, and tailored tips to enhance sound recognition and manipulation abilities.
     <img width="2648" height="1788" alt="image" src="https://github.com/user-attachments/assets/f51d5ece-d722-42b3-8cac-5c62573db2df" />


## Impact — Dyslexic Support System for Thales

> **Focus:** how **LexiEase** (dyslexic support) delivers concrete value across Thales’s **Defence & Security**, **Aeronautics & Space**, and **Cybersecurity & Digital Identity** domains.

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

![Dyslexia drawio (2)](https://github.com/user-attachments/assets/d25228c6-15cb-4e62-bd5c-3a922913e14c)

## User Flow
![image](https://github.com/user-attachments/assets/a1a63b5f-5e55-4033-a5ce-711da18bca2f)


## Snapshots of our Project
![image](https://github.com/user-attachments/assets/bb52cd20-16fe-49f6-b95c-e973a44e52fe)
![image](https://github.com/user-attachments/assets/ad438d3c-43c7-4b14-b9a6-f58ab63f38df)
![image](https://github.com/user-attachments/assets/20578bf6-bde3-4c59-b46d-7ef233cd8803)
![image](https://github.com/user-attachments/assets/364152b4-7555-4adb-ba5b-e61b012b4236)
![image](https://github.com/user-attachments/assets/f09e8b34-cf84-4ba0-bdfd-98d519aeaa49)
![image](https://github.com/user-attachments/assets/046948f9-dc73-461a-9700-411e6ed37034)


## 📊 Impact and Benefits for Users

| **Impact/Benefit**                           | **Description**                                                                                                 |
|----------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| **Improved Accessibility**                   | Offers dyslexia-friendly fonts, simplified document views, and multi-language support, enhancing accessibility for diverse users. |
| **Personalized Learning Paths**              | Adapts learning materials and exercises to individual severity levels, improving user engagement and learning outcomes. |
| **Enhanced Learning Support**                | Provides tools like an AI Writing Assistant, phonological improvement activities, and memory games, supporting comprehensive skill development. |
| **Community and Psychological Support**      | Builds a supportive network, connecting dyslexic individuals and psychologists to foster shared understanding and growth. |
| **Time and Cost Efficiency**                 | Reduces dependency on third-party intervention, enabling users to access resources independently and at a lower cost. |


## 🔍 Technology Comparison

| **Feature/Capability**           | **LexiEase AI** (Our Technology)                                     | **Traditional Tools**                          | **Basic Assistive Software**           |
|----------------------------------|-----------------------------------------------------------------------|------------------------------------------------|----------------------------------------|
| **Personalization**              | Tailored learning aids based on user needs                           | One-size-fits-all approach                    | Limited customization options          |
| **Real-Time Adaptability**       | Adapts content and difficulty dynamically in real-time               | Static content; no real-time feedback         | Minimal real-time interaction          |
| **Data-Driven Insights**         | Uses AI to generate insights and track progress                      | No tracking or insights provided              | Basic tracking without analytics       |
| **Seamless Integration**         | Easily integrates with EdTech, healthcare, and corporate platforms   | Standalone; limited integration capabilities  | Integration may require additional setup |


## 🚀 Business Relevance & Adoption Model

LexiEase AI provides a comprehensive solution that can be seamlessly integrated into various business models, making it ideal for companies looking to improve accessibility and inclusivity. Here’s how businesses can adopt and benefit from LexiEase AI:

| **Business Integration**        | **Description**                                                                                                                                                 |
|---------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **👩‍💼 EdTech Platforms**         | Integrate LexiEase AI as a value-added service to offer personalized dyslexia support, attracting a broader user base and fulfilling inclusivity goals.       |
| **🏥 Healthcare Providers**       | Utilize LexiEase AI’s screening and personalized support features to provide early intervention tools for dyslexic patients, adding value to patient care.     |
| **🏫 Educational Institutions**   | Schools and universities can adopt LexiEase AI to support dyslexic students with tailored learning aids, enhancing student engagement and performance.          |
| **📊 Corporates & Employers**     | Implement LexiEase AI within corporate learning management systems to ensure inclusive training resources for employees with dyslexia, fostering diversity.    |
| **💼 Non-Profits & NGOs**         | Leverage LexiEase AI to support initiatives aimed at learning disabilities, increasing outreach effectiveness and empowering communities with dyslexia.       |

### 🌐 Why Businesses Should Integrate LexiEase AI
1. **Boost Corporate Social Responsibility (CSR)**: By supporting dyslexic individuals, businesses can demonstrate their commitment to inclusivity and accessibility.
2. **Enhance Brand Image**: Associating with a forward-thinking, inclusive solution enhances brand value and public perception.
3. **Access New User Segments**: Integration opens opportunities to reach individuals and families affected by dyslexia, expanding the customer base.

**LexiEase AI is designed to not only support dyslexic individuals but also provide businesses with a scalable, impactful solution to enhance inclusivity and meet accessibility standards.**



     

