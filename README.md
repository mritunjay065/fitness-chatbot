# **Simple Fitness Chatbot**

A foundational rule-based chatbot designed to provide basic information and guidance on fitness topics, including workouts, nutrition, and sleep. This project serves as an introductory exploration into Natural Language Processing (NLP) concepts and conversational AI using Python.

## **🚀 Live Demo**

Experience the interactive web overview of this project here:  
[https://akki-jaiswal.github.io/fitness-chatbot/](https://akki-jaiswal.github.io/fitness-chatbot/)

## **🌟 Project Highlights**

* **Rule-Based Logic:** Implements a system of predefined rules and regular expressions to respond to user queries effectively.  
* **Basic Context Management:** A simple mechanism remembers the last user intent, allowing for more natural follow-up conversations.  
* **Robust Input Handling:** A dedicated function preprocesses user queries to normalize text for more reliable pattern matching.  
* **Directive User Guidance:** Responses actively guide the user on what questions they can ask next, improving interaction and discoverability of features.

## **✨ Features**

* **Interactive Console Interface:** Engage with the chatbot directly through your terminal.  
* **Flexible Keyword & Pattern Matching:** Utilizes re module with word boundaries (\\b) and OR operators (|) to understand single-word queries and varied phrasing.  
* **Supportive & Guiding Responses:** Provides helpful answers and proactively suggests related topics the user can explore.  
* **Handles Common Queries:** Designed to address questions like:  
  * "What's a good workout plan?"  
  * "Tell me about healthy breakfast ideas."  
  * "How much sleep do I need?"  
  * "How can I stay motivated?"  
  * Responds to single words like "workout", "meals", "sleep", "strength", "cardio", etc.

## **💻 How to Run the Python Chatbot Locally**

1. **Prerequisites:**  
   * Python 3.x installed on your system.  
2. **Clone the Repository:**  
   git clone https://github.com/Akki-jaiswal/fitness-chatbot.git  
   cd fitness-chatbot

   (If you downloaded the files manually, simply navigate to your project folder.)  
3. Run the Chatbot:  
   Navigate to the directory containing chatbot.py in your terminal and execute:  
   python chatbot.py

4. Interact:  
   Type your fitness-related questions in the terminal, and the chatbot will respond\! Type bye or exit to end the conversation.

## **💡 Future Enhancements (Roadmap for Growth)**

This project lays the groundwork for exploring more advanced AI concepts. Future improvements could include:

* **Intent Recognition with Machine Learning:** Transition from rigid rules to ML models for more intelligent understanding of user intent.  
* **Entity Extraction:** Develop capabilities to identify and extract key pieces of information (e.g., specific exercises, food types) from user queries.  
* **Advanced Context Management:** Implement a robust system to remember and utilize conversational history for more coherent and personalized interactions.  
* **Integration with APIs:** Connect to external fitness APIs for real-time data, such as calorie databases or detailed exercise instructions.  
* **Web Interface:** Build a full-fledged web application (e.g., using Flask or a frontend framework) to make the chatbot accessible via a browser.  
* **Database Integration:** Incorporate a database to store user preferences, progress, or custom fitness plans.

## **🤝 Contribution**

Feel free to fork this repository, suggest improvements, or open issues. Any feedback is welcome\!