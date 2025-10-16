# 🤖 AI Meme Generator (Spring Boot + Imgflip)

An AI-powered meme generator built with **Spring Boot (Java)** that uses **OpenAI API** for generating witty captions and **Imgflip API** for creating memes. Enter a topic, and get a ready-made meme instantly!

---

## 🚀 Features
- 🤖 AI-generated funny captions using OpenAI
- 🖼️ Meme creation through Imgflip API
- ⚙️ RESTful backend with Spring Boot
- 🔐 Environment variable-based configuration
- 🌐 JSON-based API for easy integration

---

## 🧩 Tech Stack
- **Backend:** Spring Boot (Java)
- **AI Integration:** OpenAI API
- **Meme Creation:** Imgflip API
- **HTTP Client:** RestTemplate / WebClient
- **Build Tool:** Maven

---

## 📸 Workflow
1. User inputs a meme idea/topic.
2. The app calls OpenAI API to generate funny captions.
3. The chosen caption is sent to Imgflip API.
4. The final meme image URL is returned in JSON format.

---

## 📦 API Endpoints
| Method | Endpoint | Description |
|--------|-----------|-------------|
| POST | `/api/generate` | Generate captions using AI |
| POST | `/api/create` | Create meme using Imgflip |
| POST | `/api/ai-meme` | Combine AI + Imgflip |

---

## ⚙️ Setup Instructions

⚙️ Setup Instructions

1. **Clone the repository**

git clone https://github.com/yourusername/ai-meme-generator.git
cd ai-meme-generator


2. **Configure your credentials**

Open the application.properties file and add the following:

openai.api.key=YOUR_OPENAI_API_KEY
imgflip.username=YOUR_IMGFLIP_USERNAME
imgflip.password=YOUR_IMGFLIP_PASSWORD


3. **Run the application**

   mvn spring-boot:run

