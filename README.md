# 🧠 ChatDoc AI – Chat with Your Documents
An AI-powered Spring Boot app to chat with your uploaded PDF or DOCX files

# 📌 Description
ChatDoc AI is a full-stack Java application that allows users to upload documents and interact with them through an AI-powered chat interface. It extracts the document's content using Apache Tika and uses basic Natural Language Processing (NLP) and Cosine Similarity to generate relevant answers from the file.

# 💡 Features
📤 Upload PDF or DOCX documents

📄 Extracts and displays document text using Apache Tika

💬 Ask questions about the document content

🤖 AI generates answers based on sentence similarity (TF-IDF + Cosine Similarity)

🧾 Clean chat-like interface using Thymeleaf + Bootstrap

# 🛠️ Tech Stack
Layer	Tools
Backend	Java 17, Spring Boot, Maven
Frontend	Thymeleaf, HTML/CSS, Bootstrap
AI/NLP	Apache Tika, Cosine Similarity
Build Tool	Maven
Optional	MySQL (for saving chat history)


# 📁 Folder Structure
cpp
Copy
Edit
ChatDoc-AI/
├── controller/
├── service/
├── model/
├── templates/
├── static/
├── resources/
├── application.properties
└── pom.xml
⚙️ How to Run
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/chatdoc-ai.git
cd chatdoc-ai
Import into IntelliJ/Eclipse

As a Maven project

Set Java version to 17+

Run the Spring Boot App

# 📚 Future Improvements
Integrate OpenAI or Gemini API for deep question understanding

Save chat history in MySQL

Support for multilingual documents

Add user authentication


# 👤 Divyaa Ranjani V E
# 🎓 Passionate about AI, Java Full Stack & building smart tools.
# 🔗 LinkedIn https://www.linkedin.com/in/divyaaranjanive/

