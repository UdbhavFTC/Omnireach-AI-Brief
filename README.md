# OmniReach AI — AI-Powered Accessibility Platform

**Project Focus:** Accessibility Technology | Natural Language Processing | Indian Sign Language (ISL)  
**Developer:** Udbhav Sriramoju

OmniReach AI is an accessibility-focused platform designed to improve communication and learning experiences for Deaf and Hard of Hearing (DHH) students, particularly within robotics education.

The project explores how Natural Language Processing (NLP) and automated sign-language video delivery can help bridge communication barriers between spoken instructions and Indian Sign Language (ISL).

Rather than treating accessibility as an afterthought, OmniReach AI aims to make inclusive learning an integral part of technical education.

## The Problem

During my interactions with DHH students at the Ashrey Akruti Foundation, I recognized a communication barrier that could limit their participation in technical learning environments.

Robotics education often relies on verbal instructions, technical terminology, and programming concepts that may not be readily accessible to students who primarily communicate through sign language.

I wanted to explore whether an AI-powered platform could make these concepts more accessible while allowing educators to adapt the learning experience to their students' needs.

## My Contributions & Development

I independently designed and developed OmniReach AI, working across its frontend, backend, NLP pipeline, and accessibility features.

Key components of my work included:

- **NLP Pipeline:** Developed a text-processing pipeline using OpenAI Whisper, spaCy, and fallback mechanisms to convert spoken or textual instructions into structured commands.
- **Command Recognition:** Implemented command-mapping logic to identify relevant instructions and connect them to corresponding sign-language content.
- **ISL Integration:** Developed a system for delivering Indian Sign Language videos corresponding to recognized commands, incorporating an initial vocabulary of approximately 50 ISL and FTC-related terms.
- **Teacher & Student Interfaces:** Built separate interfaces to support teacher-led content management and student-facing learning experiences.
- **Interactive Learning:** Developed learning and quiz features to help students engage with and reinforce technical concepts.
- **Accessibility-Oriented Design:** Incorporated feedback from DHH students to refine the platform's functionality and prioritize their actual learning preferences.

## System Architecture

OmniReach AI combines a web-based frontend with a backend processing pipeline to interpret instructions and deliver relevant accessibility content.

### Technology Stack

- **React:** Frontend development and interactive user interfaces.
- **Firebase Authentication:** User authentication and role-based access.
- **Firebase Firestore:** Database for storing application data.
- **Firebase Hosting:** Deployment and hosting of the web application.
- **Python & FastAPI:** Backend development and API management.
- **OpenAI Whisper:** Speech recognition and transcription.
- **spaCy:** Natural Language Processing and text processing.
- **Render:** Backend deployment and hosting.

### NLP & Command Processing Pipeline

The core processing workflow follows these stages:

1. **Input:** Receives spoken or textual instructions.
2. **Speech Recognition:** Uses Whisper to convert spoken input into text when applicable.
3. **Text Processing:** Processes the resulting text using spaCy and supporting fallback mechanisms.
4. **Command Mapping:** Identifies and maps relevant instructions to predefined commands.
5. **Sign Language Delivery:** Retrieves the corresponding ISL video content.
6. **User Interaction:** Presents the translated content through the student-facing interface.

## Real-World Validation & Iteration

An important part of developing OmniReach AI was testing the platform in an actual DHH learning environment rather than relying exclusively on theoretical accessibility requirements.

Through interactions with students and educators at the Ashrey Akruti Foundation, I was able to identify limitations in my initial approach and make changes based on their feedback.

Some key developments included:

- **User-Centered Development:** Initially, the platform incorporated features intended for a broader audience, including FTC students. Feedback from DHH students encouraged me to shift the development focus toward their specific accessibility needs.
- **Sign Language Variation:** I recognized that differences in signing preferences and regional variations could affect how students interpret sign-language content. This highlighted the importance of involving educators in content development.
- **Teacher-Guided Content:** I began developing a system that allows teachers to contribute sign-language videos, giving educators greater control over the content presented to their students.
- **Human-Centered Validation:** An experienced DHH educator at the Ashrey Akruti Foundation reviewed the sign-language videos, providing feedback on their suitability for the intended learning environment.

These iterations reinforced the importance of designing accessibility technology around the people who will actually use it.

## Project Impact

OmniReach AI represents an attempt to apply artificial intelligence and software engineering to a practical accessibility challenge.

The project has involved:

- Development of a functional web-based accessibility platform.
- Integration of speech recognition and NLP-based command processing.
- An initial vocabulary of approximately 50 ISL and FTC-related terms.
- Engagement with DHH students and educators at the Ashrey Akruti Foundation.
- Iterative improvements informed by feedback from the intended user community.
- Development of teacher-oriented features to support more adaptable sign-language content.

Rather than measuring success solely through technical functionality, the project emphasizes whether the technology can meaningfully support more inclusive learning experiences.

## Future Development

There are several areas I intend to explore further:

- **Expanded ISL Vocabulary:** Increasing the range of supported technical and everyday terminology.
- **Teacher-Generated Content:** Further developing the ability for educators to contribute and manage sign-language videos.
- **Improved NLP Accuracy:** Refining command recognition to better handle variations in phrasing and natural language.
- **Expanded Accessibility:** Exploring additional features that make technical education more accessible to DHH students.
- **User Feedback & Evaluation:** Conducting further testing with students and educators to assess usability and identify areas for improvement.

## What I Learned

Developing OmniReach AI fundamentally changed how I approach software engineering.

Initially, I approached the project primarily as a technical challenge: building an NLP pipeline, mapping commands, and delivering corresponding sign-language videos.

However, working with the intended user community showed me that a technically functional system is not necessarily an effective accessibility solution.

I learned the importance of user-centered development, iterative design, and incorporating domain expertise into engineering decisions. Most importantly, I realized that meaningful innovation comes not just from building something technically complex, but from understanding the people whose problems the technology is intended to solve.

---

**Project:** OmniReach AI  
**Focus:** AI-Powered Accessibility & Inclusive Education  
**Developer:** Udbhav Sriramoju

**Live Application:**
- Production: https://omniReach-prod.web.app
- Development: https://omniReach-dev.web.app

*This repository serves as a public overview of OmniReach AI, its architecture, development process, and objectives. It does not contain the project's source code.*
