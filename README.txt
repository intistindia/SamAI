Contents README File
Project Title – SamAI
Team ID: TH11655
                                                               
1.Overview: 
SamAI is an AI-powered multilingual chatbot designed to assist pilgrims attending the Ujjain Mahakumbh. 
Integrated seamlessly with WhatsApp, the chatbot provides text and voice-based guidance in the pilgrim’s own 
language, without requiring any additional app installation. The system ensures easy access to authentic information, 
directions, and assistance, making the spiritual journey smooth, inclusive, and more convenient for millions of devotees.

2.Problem & Solution

 • Problem Statement: 
 Pilgrims visiting the Ujjain Mahakumbh often face challenges in finding authentic information, navigating the city, 
 and receiving guidance in their local language. With millions of visitors, traditional helpdesks or physical volunteers
 are unable to serve everyone efficiently, leading to confusion, miscommunication, and inconvenience.

• Solution:  
 SamAI offers an AI-driven WhatsApp chatbot that provides real-time, multilingual assistance through both text 
 and voice. Pilgrims can access directions, event schedules, rituals, facilities, and emergency support directly 
 on WhatsApp—without installing any new application. This ensures accessibility, scalability, and a personalized 
 experience for every pilgrim.

3.Logic & Workflow:
Data Collection:
Information about the Ujjain Mahakumbh (routes, rituals, facilities, schedules, emergency contacts, FAQs) is 
gathered from verified sources such as government portals, local authorities, and event organizers.

Processing:
The collected data is trained and indexed into the AI model. Natural Language Processing (NLP) enables 
understanding of queries in multiple regional languages. Speech-to-Text (STT) and Text-to-Speech (TTS) 
engines are integrated for voice interactions.

Output:
The chatbot generates context-aware responses in the user’s preferred language, delivered via text or 
voice messages directly on WhatsApp.

User Side:
Pilgrims interact through a simple WhatsApp chat or voice message in their own language. They receive 
instant replies for navigation, rituals, event updates, accommodation, or emergency support—without needing 
to install any additional app.

Admin Side:
Administrators can update event data, monitor user interactions, and analyze chatbot usage through a dashboard. 
This ensures real-time content accuracy, better crowd management, and improved service delivery.

4.Tech Stack:
Frontend & Integration: React.js, WhatsApp Business API, Twilio API
Backend: Node.js, Express.js, Python (for AI/NLP models)
Database: MongoDB, Firebase (for real-time data & authentication)
AI & NLP: Natural Language Processing (Multilingual support), Speech-to-Text (STT), Text-to-Speech (TTS)
APIs & Services: Google Maps API (navigation & location services), Cloud Translation API
Hosting & Deployment: AWS / Google Cloud Platform

5.Future Scope:
The prototype can be scaled with advanced AI features like personalized recommendations and predictive crowd management.
Integration with a dedicated mobile app for enhanced accessibility alongside WhatsApp.
Support for multi-user group chats to help families or tour groups plan together.
Expansion to other large-scale religious, cultural, or public events across India.
Addition of offline support via IVR helpline for users with limited internet access.
