# health
A React front end that sends user entered symptoms to a low code  backend running a Hugging Face LLM model. The model returns  possible diagnoses and next step recommendation
PPT presentation: https://1drv.ms/p/c/677618621d3781d1/Eeac1FlRyNxFv8RQ-e5sP70B7dt-qjCbYeWr3z5Cyn27iA?e=REKBn4



Report and Documentory : 

AI-POWERED HEALTH RECOMMENDATION SYSTEM

TITLE PAGE
Project Title: AI-Powered Health Recommendation System
Student Name: [Neha Sharma , Krish Choudhary , Priyanshu , Anuroop
Gupta ] Roll Number: [2415500309 , 2415500243,2415500364,2415500094] Course/Semester: [B.Tech(AI&ML) - 3rd Sem] 
ABSTRACT


This project presents the development of an AI-powered health recommendation system designed to provide preliminary health guidance based on user-reported symptoms. The system is implemented as a Reactbased web application that facilitates user input of symptoms. These symptoms are then transmitted to a Hugging Face Large Language Model (LLM) backend for intelligent analysis. The LLM processes the symptom data and returns potential diagnoses along with actionable health recommendations. This system aims to offer accessible and immediate preliminary health information, empowering users to make informed decisions about their well-being.


1.	INTRODUCTION
1.1 Background of Healthcare Challenges
Access to timely and accurate healthcare advice is a persistent global challenge. Long waiting times for doctor's appointments, geographical barriers, and the cost of medical consultations can hinder individuals from seeking initial medical guidance. This often leads to delayed diagnosis and treatment, potentially worsening health outcomes.
1.2 Need for AI-Powered Preliminary Symptom Checking
Artificial Intelligence, particularly Large Language Models (LLMs), offers a promising solution to bridge this gap. AI can process vast amounts of medical information and patient-reported symptoms to provide preliminary assessments. Such systems can serve as an initial point of contact for individuals experiencing mild to moderate symptoms, guiding them on whether to seek professional medical attention or manage symptoms at home.
1.3 Scope of the Project
This project focuses on developing a user-friendly web application that leverages an LLM to interpret user-provided symptoms and generate potential diagnoses and corresponding health recommendations. The system is designed for preliminary assessment and educational purposes, not as a substitute for professional medical diagnosis or treatment.

2.	OBJECTIVES
This project aims to achieve the following key objectives:
Build a Web Application for Symptom Input: Develop an intuitive and interactive web interface using React for users to easily input their health symptoms.
Utilize Hugging Face LLM for Intelligent Diagnosis: Integrate a Hugging Face LLM to process the collected symptom data and generate plausible diagnostic suggestions.
Provide Next-Step Health Recommendations: Offer clear and actionable health recommendations based on the AI-generated diagnosis, guiding users on appropriate actions.
Deploy System on Cloud (Vercel): Successfully deploy the developed web application to a cloud platform, such as Vercel, to ensure accessibility and scalability.

3.	SYSTEM DESIGN & ARCHITECTURE
The system follows a client-server architecture, with the React frontend communicating with a backend API that interfaces with the Hugging Face LLM.
System Flow: 1. User Input: The user enters their symptoms through the React web application. 2. React Frontend: The frontend captures the user input and sends it as a request to the backend API. 3. Backend API: A backend service receives the request, formats the data, and forwards it to the Hugging Face LLM API. 4. Hugging Face LLM: The LLM analyzes the provided symptoms and generates a potential diagnosis and corresponding
recommendations. 5. Output: The LLM's response is sent back to the backend API, which then relays it to the React frontend. 6. Display Results: The frontend displays the AI-generated diagnosis and recommendations to the user.

4.	IMPLEMENTATION
4.1 Technologies Used
Frontend: React.js for building a dynamic and responsive user interface. Backend/LLM Integration: Hugging Face API to access a powerful LLM for natural language processing and medical knowledge inference. Deployment: Vercel for seamless and efficient deployment of the web application.
4.2 Features
User-Friendly Symptom Input Form: An intuitive form designed for easy and clear input of symptoms.
AI-Generated Results: Real-time display of potential diagnoses and health recommendations powered by the LLM.
Real-time Backend Connection: Efficient communication between the frontend and the backend API for prompt results.

5.	RESULTS & DISCUSSION
During testing, the system demonstrated its ability to process symptom descriptions and provide relevant feedback. For instance, when a user inputted symptoms such as "fever, cough, and body aches," the system, leveraging the Hugging Face LLM, accurately identified potential diagnoses like "flu" or "viral infection." Consequently, it provided recommendations such as "get plenty of rest, stay hydrated by drinking fluids, and consult a doctor for a definitive diagnosis and treatment plan."
The effectiveness and reliability of the results are largely dependent on the quality of the LLM's training data and its ability to interpret nuanced symptom descriptions. The preliminary results indicate that the system can provide valuable initial guidance.

6.	LIMITATIONS
While this system offers significant benefits, it is crucial to acknowledge its limitations:
Not a Replacement for Professional Medical Advice: The system's output is for informational purposes only and should not be considered a substitute for professional medical diagnosis or treatment from a qualified healthcare provider.
Limited Accuracy and API Dependency: The accuracy of the diagnoses is contingent on the LLM's capabilities and the comprehensiveness of its training data. Reliance on external APIs also means potential downtime or changes in service.
No Patient History or Lab Report Integration: The system currently does not integrate with patient medical histories, previous diagnoses, or laboratory test results, which are critical for a complete medical assessment.

7.	FUTURE ENHANCEMENTS
To further improve the system's utility and accuracy, several enhancements can be considered:
Personalized Diagnosis with Patient History: Integrate secure mechanisms for users to input or link their medical history for more personalized recommendations.
Multilingual Support: Extend the system's reach by incorporating support for multiple languages.
Mobile App Development: Create a dedicated mobile application for enhanced accessibility and user experience.
Telemedicine Integration: Explore integration with telemedicine platforms to facilitate seamless transitions to professional medical consultations.

8.	CONCLUSION
This project highlights the transformative potential of AI in revolutionizing healthcare accessibility. The AI-Powered Health Recommendation System provides users with a convenient and informative tool for preliminary symptom checking and guidance. By leveraging advanced LLMs and modern web technologies, the system offers immediate insights, empowering individuals to take proactive steps towards managing their health. While it serves as a valuable assistive tool, it underscores the indispensable role of professional medical expertise.

9.	REFERENCES
Hugging Face API Documentation. (n.d.). Retrieved from https:// huggingface.co/docs/api-inference/index
React Official Documentation. (n.d.). Retrieved from https://reactjs.org/docs/
Vercel Deployment Guide. (n.d.). Retrieved from https://vercel.com/docs
