# ResumeIQ

# .NET Interview Question Generator using Azure OpenAI

## 📌 Project Overview
This project generates customized technical interview questions for candidates with 3–6 years of experience in Microsoft .NET technologies. It uses Azure OpenAI to analyze resume content and produce relevant, role-specific questions tailored to each candidate’s background.

## 🚀 Features
- Resume-driven question generation
- Focused on mid-level .NET professionals
- Covers technologies like:
  - C#
  - Object-Oriented Programming (OOP)
  - .NET Core
  - REST APIs & Microservices
  - Azure Cloud
- Token-efficient prompt design
- Easy integration with Azure Functions or web applications

## 🛠 Technologies Used
- Azure OpenAI Service
- C# (.NET 6/7/8 or .NET 9)
- ASP.NET Core / Azure Functions
- OpenAI Chat Completion API

## ⚙️ How It Works
1. A resume is submitted via a form or API.
2. A static `SystemChatMessage` defines the AI's behavior.
3. A concise `UserChatMessage` is dynamically created using the resume content.
4. The prompt is sent to Azure OpenAI's chat completion endpoint.
5. The AI returns tailored interview questions based on the resume.

## 🧰 Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/dotnet-interview-generator.git
   cd dotnet-interview-generator
   ```
