# 🔬 Research Assistant — Chrome Extension

![Chrome Extension](https://img.shields.io/badge/Chrome-Extension-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)
![Java](https://img.shields.io/badge/Java-Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Gemini AI](https://img.shields.io/badge/Gemini-AI-8E75B2?style=for-the-badge&logo=google&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Frontend-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Maven](https://img.shields.io/badge/Maven-Build%20Tool-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)

> A **Chrome Extension** that instantly summarizes long paragraphs into short, crisp summaries using **Google Gemini AI** and a **Spring Boot** backend.

---

## ✨ Features

- 📄 **One-click summarization** — select any text on a webpage and get an instant summary
- 🤖 **AI-powered** — uses Google Gemini API for intelligent summarization
- ⚡ **Fast & lightweight** — Chrome side panel UI, no page reload needed
- 🔗 **REST API backend** — Spring Boot processes and communicates with Gemini
- 🎨 **Clean side panel UI** — results appear right inside your browser
- 📝 **Save your notes** — save important summaries directly within the extension for future reference

---


---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Chrome Extension** | HTML, CSS, JavaScript |
| **Backend** | Java 17, Spring Boot |
| **AI Model** | Google Gemini API |
| **Communication** | REST API (HTTP/JSON) |
| **Build Tool** | Maven |

---


---

## 🚀 Getting Started

### Prerequisites

- Java 17+
- Maven
- Google Chrome Browser
- Gemini API Key → [Get here](https://makersuite.google.com/app/apikey)

---

### 1️⃣ Backend Setup (Spring Boot)

```bash
# Clone the repository
git clone https://github.com/Shubhamkale1/Research-Assistant.git

# Navigate to backend folder
cd Research-Assistant/research-assistant

# Add your Gemini API key in src/main/resources/application.properties
# gemini.api.key=YOUR_GEMINI_API_KEY

# Build and run
mvn spring-boot:run
```

✅ Backend runs on: `http://localhost:8080`

---

### 2️⃣ Chrome Extension Setup

```
1. Open Chrome → go to:  chrome://extensions/
2. Enable "Developer Mode"  (toggle - top right)
3. Click "Load unpacked"
4. Select the folder:  Research-Assistant/research-assistant-ext/
5. Extension is installed ✅
```

---

### 3️⃣ Using the Extension

```
1. Open any webpage with a long article or paragraph
2. Simply highlight / select the text you want to summarize
3. Click the "Summarize" button in the side panel
4. Get your short summary instantly! 🎉
5. Optionally click "Save" to store the summary as a note for future reference 📝
```

> ✅ **No copy-paste needed** — just select the text on the page and click!

---

## 🔑 Configuration

In `research-assistant/src/main/resources/application.properties`:

```properties
gemini.api.key=YOUR_GEMINI_API_KEY
server.port=8080
```

---

## 📸 Screenshots
<img width="1920" height="1080" alt="Screenshot (337)" src="https://github.com/user-attachments/assets/d9095190-548e-4445-b1f0-fc03274cd7bc" />

<img width="1920" height="1080" alt="Screenshot (338)" src="https://github.com/user-attachments/assets/e3025705-cab0-4d1a-be4c-afd9ca90bfaf" />

<img width="1920" height="1080" alt="Screenshot (339)" src="https://github.com/user-attachments/assets/e609e972-7d8e-4e36-abb0-402cf3858e80" />

---

## 👨‍💻 Author

**Shubham Kale**

[![LeetCode](https://img.shields.io/badge/LeetCode-shubham__96k-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/shubham_96k)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-kale--shubham-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kale-shubham/)
[![GitHub](https://img.shields.io/badge/GitHub-Shubhamkale1-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Shubhamkale1)

---

## ⭐ Support

If you found this project helpful, please give it a **star** ⭐ on GitHub!

---

> *"Work smarter, not harder — let AI summarize for you."*
