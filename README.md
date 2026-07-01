# 🐍 Pytutor - AI Python Learning Assistant

![Python](https://img.shields.io/badge/Python-Expert%20Tutor-blue)
![React](https://img.shields.io/badge/React-18-61DAFB?logo=react)
![Node.js](https://img.shields.io/badge/Node.js-Express-339933?logo=node.js)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--3.5--turbo-412991)
![License](https://img.shields.io/badge/License-MIT-green)

> An AI-powered conversational assistant that teaches Python programming with clear explanations, code examples, and interactive guidance.

**INNOVIAST Week 1** • AI Solutions Engineering Track 03

---

## ✨ What is Pytutor?

Pytutor is a **professional-grade chatbot** that specializes in teaching Python fundamentals. It combines intelligent AI, beautiful UI, and smart responses to create an engaging learning experience.

### 🎯 Key Features

- ✅ **Intelligent Responses** - Powered by OpenAI GPT-3.5-turbo
- ✅ **Beautiful Design** - Modern dark mode with glass morphism
- ✅ **Smart Scope** - Recognizes Python topics and redirects out-of-scope
- ✅ **Error Handling** - Graceful fallback for edge cases
- ✅ **Professional UI** - Smooth animations and responsive design
- ✅ **Complete Docs** - Prompt engineering & deployment guides

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| **Frontend** | React 18 + CSS3 |
| **Backend** | Node.js + Express |
| **AI** | OpenAI GPT-3.5-turbo |
| **HTTP** | Axios |
| **Config** | dotenv |

---

## 🚀 Quick Start

### Prerequisites
- Node.js 14+
- OpenAI API Key ([Get here](https://platform.openai.com/account/api-keys))

### Installation & Setup

```bash
# Clone repository
git clone https://github.com/SanaFayyaz12/pytutor.git
cd pytutor

# Install frontend dependencies
npm install

# Setup backend
cd server
npm install express cors dotenv axios
cd ..

# Create .env files
echo REACT_APP_API_URL=http://localhost:5000 > .env
echo OPENAI_API_KEY=sk-YOUR_KEY > server/.env
echo PORT=5000 >> server/.env
```

### Running the App

**Terminal 1 - Backend:**
```bash
cd server
node index.js
# Output: ✅ Pytutor Server running on http://localhost:5000
```

**Terminal 2 - Frontend:**
```bash
npm start
# Opens http://localhost:3000
```

---

## 💬 How It Works

### Example: Learning Python Loops
User: "Explain Python loops to me"
Bot: Python loops let you repeat code! There are 2 types:

for loop - repeat a fixed number of times:
for i in range(5):
print(i)  # Output: 0,1,2,3,4
while loop - repeat based on condition:
count = 0
while count < 3:
print(count)
count += 1

Want to try a practice problem?

### Out-of-Scope Handling
User: "Tell me a joke"
Bot: I'm Pytutor, your Python course assistant! 🐍
I can only help with Python programming.
What Python topic can I help you with?

---

## 📚 What Pytutor Teaches

✅ **Python Basics:**
- Variables & Data types
- Control flow (if/else, loops)
- Functions & Modules
- Data structures (lists, dicts, tuples)
- File handling
- Error handling
- Basic OOP

❌ **Out of Scope:**
- Web frameworks (Django, Flask)
- Machine Learning/Data Science
- System administration
- Non-programming topics

---

## 📁 Project Structure
pytutor/
├── src/
│   ├── App.js              # Chat component
│   ├── App.css             # Professional styling
│   └── index.js
├── server/
│   ├── index.js            # Express server
│   ├── .env                # Configuration
│   └── package.json
├── public/
├── README.md               # This file
├── AI_USAGE.md             # AI documentation
├── QUICKSTART.md           # Setup guide
├── TESTING.md              # Test cases
└── package.json

---

## 🔧 Key Features Explained

### Dark Mode with Glass Morphism
- Modern, professional appearance
- Reduces eye strain
- Smooth animations
- Fully responsive

### Intelligent Fallback
- Recognizes Python topics
- Gracefully redirects non-Python questions
- Helpful error messages
- Multi-level error handling

### Complete Documentation
- System prompt engineering
- Model configuration
- Deployment guide
- Testing checklist

---

## 📊 Performance

| Metric | Status |
|--------|--------|
| Backend startup | <2s ✅ |
| API response | <2s ✅ |
| Frontend load | <3s ✅ |
| Mobile responsive | Yes ✅ |

---

## 📄 Documentation

- **[README.md](README.md)** - Project overview
- **[AI_USAGE.md](AI_USAGE.md)** - AI & prompt details
- **[QUICKSTART.md](QUICKSTART.md)** - Setup guide
- **[TESTING.md](TESTING.md)** - Test checklist

---

## 🚀 Deployment

### Frontend (Vercel)
```bash
npm install -g vercel
vercel
```

### Backend (Render.com)
1. Push to GitHub
2. Create Web Service on Render
3. Connect repository
4. Set environment variables
5. Deploy

---

## 🔒 Security

✅ API keys protected in .env  
✅ Input validation implemented  
✅ Error handling without exposing sensitive info  
✅ CORS configured  

---

## 📈 Project Stats

- **Languages:** JavaScript, CSS
- **Framework:** React + Node.js
- **AI Model:** OpenAI GPT-3.5-turbo
- **Lines of Code:** 2000+
- **Status:** Production Ready ✅

---

## 🎓 Learning Outcomes

This project demonstrates:
- React hooks & state management
- API integration
- Prompt engineering
- Error handling patterns
- Modern UI/UX design
- Full-stack development
- Git workflows

---

## 📞 Support

**Issues?** Check:
- [QUICKSTART.md](QUICKSTART.md) for setup help
- [TESTING.md](TESTING.md) for troubleshooting
- GitHub Issues section

---

## 📄 License

MIT License - See LICENSE file

---

<div align="center">

**Made with ❤️ for Python learners everywhere**

⭐ Star this repo if you find it helpful!

**[🔗 Visit Repository](https://github.com/SanaFayyaz12/pytutor)**

</div>
