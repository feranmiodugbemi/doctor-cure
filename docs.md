# PhD Project Report: Interactive Medical Diagnosis App(Docture-cure)

## [Doctor Cure](https://doctor-cure.onrender.com/)

## Table of Contents

1. **Introduction**
2. **Literature Review**
3. **System Architecture**
4. **Methodology**
5. **Implementation Details**
   - **Backend: Flask Application**
   - **Endpoint Interactions**
   - **Interactive Graphs and User Interface**
   - **3D Medical Doctors**
   - **Bilingual Support: Igbo and English**
6. **Results and Discussion**
7. **Conclusion**
8. **Future Work**

## 1. Introduction

The Interactive Medical Diagnosis App aims to revolutionize the way patients interact with medical professionals and understand their symptoms. By integrating advanced technologies such as 3D avatars, interactive graphs, and natural language processing, the application provides a seamless, user-friendly experience for users seeking medical advice. This report details the methodologies, implementation, and results of this innovative project.

## 2. Literature Review

Existing medical diagnostic applications primarily rely on textual or basic graphical interfaces. Recent advancements in artificial intelligence and 3D modeling have opened new possibilities for enhancing user interaction. This project builds on these advancements by incorporating 3D medical avatars and leveraging large language models (LLMs) to provide accurate and engaging medical advice.

## 3. System Architecture

The system architecture of the Interactive Medical Diagnosis App consists of two primary components:
1. **Backend:** The main application backend developed using Flask.
2. **Endpoints:** Separate services that interact with LLM models via APIs.

### High-Level Architecture Diagram
(Insert diagram here)

## 4. Methodology

### 4.1 Requirements Gathering
The initial phase involved gathering requirements through surveys and interviews with potential users and medical professionals. This helped in understanding user needs and expectations.

### 4.2 System Design
Based on the gathered requirements, a detailed system design was created, outlining the architecture, data flow, and interaction between different components.

### 4.3 Development
The development phase was divided into:
- Backend Development (Flask Application)
- Endpoint Development (Interacting with LLM models)
- User Interface Design (HTML, CSS, JavaScript)
- Integration of 3D Medical Doctors
- Implementation of Bilingual Support (Igbo and English)
- Creation of Interactive Graphs

### 4.4 Testing
Extensive testing was conducted to ensure the reliability and accuracy of the medical advice provided by the application.

### 4.5 Deployment
The application was deployed on a scalable cloud platform to handle high traffic and ensure availability.

## 5. Implementation Details

### 5.1 Backend: Flask Application
The main backend is developed using Flask, a lightweight and flexible web framework for Python. Flask was chosen for its simplicity and ease of integration with other services. The backend handles user authentication, session management, and interactions with the front end.

#### Key Features
- User Authentication
- Session Management
- API Integration with Endpoints
- Data Storage and Retrieval

### 5.2 Endpoint Interactions
Endpoints are hosted separately and are responsible for interacting with the LLM models via APIs. These endpoints receive user inputs, process them using the LLM models, and return the results to the Flask backend.

#### Key Features
- API Requests and Responses
- Interaction with LLM Models
- Data Processing and Analysis

### 5.3 Interactive Graphs and User Interface
The user interface is designed to be intuitive and engaging. Interactive graphs are integrated to show patients their symptoms and the probability of the symptoms as predicted by the model. This visualization helps users understand their health condition better.

#### Key Features
- Interactive Symptom Graphs
- User-Friendly Interface
- Real-Time Data Visualization

### 5.4 3D Medical Doctors
A unique feature of the application is the use of 3D medical doctors. Depending on user preference, either a male or female 3D avatar is displayed. These avatars enhance the user experience by providing a realistic and engaging interaction.

#### Key Features
- Realistic 3D Avatars
- User Selection of Male or Female Doctors
- Integration with User Interface

### 5.5 Bilingual Support: Igbo and English
The application supports both Igbo and English languages, making it accessible to a broader audience. Users can switch between languages seamlessly, ensuring they receive medical advice in their preferred language.

#### Key Features
- Bilingual Interface
- Language Selection Option
- Accurate Translation of Medical Advice

## 6. Results and Discussion

### User Feedback
Positive feedback was received from initial users, highlighting the engaging interface and the helpfulness of the 3D medical avatars.

### Accuracy and Reliability
The application demonstrated high accuracy in symptom prediction and medical advice, thanks to the integration with advanced LLM models.

### Performance
The system performed efficiently under high traffic conditions, with minimal downtime and fast response times.

## 7. Conclusion

The Interactive Medical Diagnosis App successfully combines modern technologies to provide an innovative solution for medical diagnostics. The integration of 3D avatars, interactive graphs, and bilingual support offers a unique and engaging user experience.

## 8. Future Work

Future enhancements could include:
- Expanding language support to more regional languages
- Adding more detailed 3D animations for medical procedures
- Integrating wearable device data for real-time health monitoring
- Enhancing AI models for more accurate diagnosis

---

> **Note:** Doctor Cure is hosted temporarily on Colab, so the URL changes from time to time. Whenever a new URL is generated, it has to be added to the hosted environment variable under `API_ENDPOINT`.
