# Bi-Lingual BankerBOT Chatbot

## 🚀 Introduction
Building a chatbot that truly connects with people isn’t just about code—it’s about understanding their needs. That’s exactly what I set out to do with Bi-Lingual BankerBOT. This chatbot helps users navigate their banking needs effortlessly, supporting both English and African languages for a smoother and more inclusive experience.

## 📌 Table of Contents
- [About Amazon Lex](#about-amazon-lex)
- [Project Setup](#project-setup)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Epic User Story](#epic-user-story)
- [Use Cases](#use-cases)
- [Intents Configuration](#intents-configuration)
- [Fallback Mechanism](#fallback-mechanism)
- [Testing and Iteration](#testing-and-iteration)
- [Conclusion](#conclusion)

## 🤖 About Amazon Lex
Amazon Lex is the engine that powers BankerBOT. It’s a cloud-based AI service that makes it incredibly easy to build chatbots. With its built-in speech recognition and natural language processing, I was able to focus on crafting the best user experience instead of wrestling with complex AI models.

## ⚙️ Project Setup
![Amazon Lex Setup](![image](https://github.com/user-attachments/assets/0f764f90-aef5-447b-88f9-bdd6303c6ff5)
)
### Step 1: Creating the Chatbot
Getting BankerBOT up and running took just 3 minutes. The interface is intuitive, making it simple to create a functional chatbot without breaking a sweat.

### Step 2: Assigning Permissions
Security is key, so I created a role with basic permissions to ensure the bot has just enough access to function—nothing more, nothing less.

### Step 3: Setting Confidence Threshold
I stuck with the default confidence threshold of 0.40, which helps the bot balance between accurate responses and reducing false positives. This ensures smoother interactions and fewer frustrating moments for users.

## 🌟 Key Features
- **🗣️ Bilingual Support**: Handles conversations in both English and African languages.
- **🔍 Smart Intent Recognition**: Accurately understands user queries and provides meaningful responses.
- **🛡️ Robust Fallback System**: Ensures that even unrecognized inputs receive helpful guidance.
- **💬 Natural Conversation Flow**: Uses multiple variations to make interactions feel human-like.

## 🛠️ Tech Stack
- **Amazon Lex**: Brain of the chatbot, responsible for understanding and responding to users.
- **AWS IAM**: Ensures secure role-based permissions.
- **A/B Testing Tools**: Helps optimize responses based on user feedback.
- **Feature Prioritization Framework**: Used the RICE method (Reach, Impact, Confidence, Effort) to refine the chatbot’s most valuable features.
- **Logging & Analytics**: Amazon CloudWatch provides real-time tracking of user interactions and chatbot performance.

## 📖 Epic User Story
### Title: Making Banking Support Instant and Accessible
#### As a
Banking customer who needs quick, hassle-free assistance,
#### I want
A chatbot that can help me check my balance, track transactions, and resolve issues in my preferred language,
#### So that
I don’t have to wait in long queues or struggle with language barriers when I need support.

## 🔍 Use Cases
### **Pain Point: Long Wait Times for Support**
- **Scenario**: A customer needs to check their account balance but doesn’t want to wait on hold.
- **Solution**: BankerBOT instantly provides the balance, eliminating the need for a human agent.

### **Pain Point: Language Barriers in Customer Service**
- **Scenario**: A user who is more comfortable speaking an African language struggles to communicate their banking issue.
- **Solution**: BankerBOT understands and responds in their preferred language, making communication smooth and stress-free.

### **Pain Point: Delayed Transaction Tracking**
- **Scenario**: A customer wants to confirm if their money transfer went through successfully.
- **Solution**: BankerBOT fetches transaction details instantly, removing the guesswork.

## 🎯 Intents Configuration
![Intent Configuration](path/to/intents-image.png)
### WelcomeIntent
BankerBOT starts conversations with a friendly greeting, supporting multiple languages such as:
- "Hello"
- "Hi"
- "Ekaale"
- "Ekaasan"

### FallbackIntent
Whenever BankerBOT encounters an input it doesn’t recognize, it triggers a helpful fallback response instead of leaving users stranded.

## 🔄 Fallback Mechanism
![Fallback Intent Handling](path/to/fallback-image.png)
When a user enters something unexpected, BankerBOT gracefully handles the situation by offering guidance rather than just saying, "I don’t understand."

## 🧪 Testing and Iteration
![Testing and Iteration Process](path/to/testing-image.png)
Building a chatbot isn’t just about getting it live—it’s about making it better over time. Here’s how I refined BankerBOT:
- **📊 A/B Testing**: Ran multiple tests on different responses to see which ones felt the most natural and engaging.
- **🛠️ Intent Matching Validation**: Tested various phrasing styles to fine-tune accuracy.
- **🛡️ Fallback Effectiveness**: Kept track of how often users hit the fallback and adjusted training data to improve recognition.
- **🎯 Feature Prioritization**: Applied the RICE method to focus on high-impact features first.
- **📈 User Feedback Implementation**: Analyzed chatbot logs via CloudWatch to identify user pain points and iterated accordingly.

## ✅ Conclusion
This journey of creating BankerBOT has shown how AI can make banking support more accessible and user-friendly. Amazon Lex made the technical side easy, allowing me to focus on creating a chatbot that truly helps people. Next steps? Expanding language support and integrating additional financial services!
