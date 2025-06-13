# 🤖 AI Code Reviewer

An AI-powered web application that helps developers review and improve their code with intelligent suggestions. Built using the **MERN stack (MongoDB, Express, React, Node.js)** and integrated with the **OpenAI API**, this tool provides code feedback, bug detection, and optimization tips — instantly.

---

## 🚀 Features

- 🧠 **AI-Powered Feedback**: Uses OpenAI to analyze and suggest improvements to code.
- 🧑‍💻 **Real-time Code Editor**: Write and edit code with syntax highlighting.
- 🐛 **Bug Detection**: Highlights possible bugs and logical issues.
- ✅ **Best Practice Suggestions**: Recommends clean code patterns and refactoring tips.
- 🔐 **Authentication (Optional)**: Secure user login with JWT.
- 🧾 **Review History**: Store and view previously reviewed snippets (if implemented with DB).
- 📱 **Responsive UI**: Fully responsive design for mobile and desktop.

---

## 🛠️ Tech Stack

| Technology    | Purpose                     |
|---------------|-----------------------------|
| **MongoDB**   | Database for storing code reviews & user data |
| **Express.js**| Backend API server          |
| **React.js**  | Frontend user interface     |
| **Node.js**   | Backend runtime             |
| **OpenAI API**| AI code analysis            |
| **Tailwind CSS** | Styling framework        |
| **JWT**       | (Optional) Authentication   |

---

## 📁 Folder Structure
AI-Code-Reviewer/
├── Frontend/
│ └── React app with editor and UI
├── BackEnd/
│ └── Express API with OpenAI integration
├── README.md
├── .gitignore


---

## ⚙️ Getting Started

### 🔧 Prerequisites
- Node.js and npm installed
- MongoDB URI (local or Atlas)
- OpenAI API Key

---

### 📦 Backend Setup

```bash
cd BackEnd
npm install

Create a .env file in /BackEnd:
PORT=5000
MONGO_URI=your_mongodb_connection_string
OPENAI_API_KEY=your_openai_api_key
Run backend:

bash
npm start
💻 Frontend Setup
cd Frontend
npm install
npm start

🔒 Environment Variables
Variable	Description
OPENAI_API_KEY	Your OpenAI API Key
MONGO_URI	MongoDB connection string
PORT	Backend server port

🙋‍♂️ Author
Manish Mahawar
📧 [Your Email or LinkedIn]
🔗 GitHub Profile





