# 🚀 AI Resume Analyzer

An AI-powered Resume Analyzer web application that evaluates resumes, checks ATS compatibility, analyzes skills, and provides career improvement suggestions.

---

## 📌 Features

✅ Resume Upload (PDF/DOCX)  
✅ ATS Score Analysis  
✅ Skill Gap Detection  
✅ AI-Based Suggestions  
✅ Resume Ranking System  
✅ User Authentication  
✅ Dashboard Analytics  
✅ Dark/Light Mode  

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Axios

### Backend
- Node.js
- Express.js

### Database
- MongoDB Atlas

### AI / ML
- Python
- NLP
- Scikit-learn

---

## 📂 Project Structure

```bash
AI-Resume-Analyzer/
│
├── frontend/
├── backend/
├── ai-model/
├── README.md
└── package.json
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/praveen02102005/AI-Resume-Analyzer.git
```

### Install Frontend

```bash
cd frontend
npm install
```

### Install Backend

```bash
cd backend
npm install
```

### Start Project

```bash
npm run dev
```

---

## 📸 Screenshots

export default function ResumeAnalyzerUI() {
  return (
    <div className="min-h-screen bg-gray-950 text-white p-6">
      {/* Header */}
      <div className="flex items-center justify-between mb-8">
        <div>
          <h1 className="text-4xl font-bold">🚀 AI Resume Analyzer</h1>
          <p className="text-gray-400 mt-2">
            Analyze resumes with AI-powered ATS scoring.
          </p>
        </div>

        <button className="bg-blue-600 hover:bg-blue-700 px-5 py-3 rounded-xl font-semibold shadow-lg">
          Upload Resume
        </button>
      </div>

      {/* Dashboard Cards */}
      <div className="grid grid-cols-1 md:grid-cols-3 gap-6 mb-8">
        <div className="bg-gray-900 rounded-2xl p-6 shadow-xl border border-gray-800">
          <h2 className="text-xl font-semibold mb-3">📄 ATS Score</h2>
          <div className="text-5xl font-bold text-green-400">85%</div>
          <p className="text-gray-400 mt-2">Good ATS compatibility</p>
        </div>

        <div className="bg-gray-900 rounded-2xl p-6 shadow-xl border border-gray-800">
          <h2 className="text-xl font-semibold mb-3">🧠 Skills Found</h2>
          <div className="flex flex-wrap gap-2 mt-3">
            <span className="bg-blue-600 px-3 py-1 rounded-full">React</span>
            <span className="bg-green-600 px-3 py-1 rounded-full">Python</span>
            <span className="bg-purple-600 px-3 py-1 rounded-full">MongoDB</span>
            <span className="bg-pink-600 px-3 py-1 rounded-full">Node.js</span>
          </div>
        </div>

        <div className="bg-gray-900 rounded-2xl p-6 shadow-xl border border-gray-800">
          <h2 className="text-xl font-semibold mb-3">⚠ Missing Skills</h2>
          <div className="flex flex-wrap gap-2 mt-3">
            <span className="bg-red-600 px-3 py-1 rounded-full">Docker</span>
            <span className="bg-yellow-600 px-3 py-1 rounded-full">AWS</span>
            <span className="bg-orange-600 px-3 py-1 rounded-full">Kubernetes</span>
          </div>
        </div>
      </div>

      {/* Resume Analysis Section */}
      <div className="bg-gray-900 rounded-2xl p-8 shadow-xl border border-gray-800 mb-8">
        <h2 className="text-2xl font-bold mb-4">📊 Resume Analysis</h2>

        <div className="space-y-4">
          <div>
            <div className="flex justify-between mb-1">
              <span>Technical Skills</span>
              <span>90%</span>
            </div>
            <div className="w-full bg-gray-700 rounded-full h-3">
              <div className="bg-green-500 h-3 rounded-full w-[90%]"></div>
            </div>
          </div>

          <div>
            <div className="flex justify-between mb-1">
              <span>Projects</span>
              <span>80%</span>
            </div>
            <div className="w-full bg-gray-700 rounded-full h-3">
              <div className="bg-blue-500 h-3 rounded-full w-[80%]"></div>
            </div>
          </div>

          <div>
            <div className="flex justify-between mb-1">
              <span>Experience</span>
              <span>70%</span>
            </div>
            <div className="w-full bg-gray-700 rounded-full h-3">
              <div className="bg-yellow-500 h-3 rounded-full w-[70%]"></div>
            </div>
          </div>
        </div>
      </div>

      {/* AI Suggestions */}
      <div className="bg-gray-900 rounded-2xl p-8 shadow-xl border border-gray-800">
        <h2 className="text-2xl font-bold mb-4">💡 AI Suggestions</h2>

        <ul className="space-y-3 text-gray-300">
          <li>✅ Add more cloud computing skills.</li>
          <li>✅ Include internship experience.</li>
          <li>✅ Improve resume formatting for ATS.</li>
          <li>✅ Add GitHub and LinkedIn links.</li>
          <li>✅ Mention final-year projects clearly.</li>
        </ul>
      </div>
    </div>
  );
}

---

## 🔥 Future Enhancements

- AI Interview Preparation
- LinkedIn Profile Analyzer
- Job Recommendation System
- Multi-language Resume Support

---

## 👨‍💻 Author

Praveen Kumar B

GitHub:
https://github.com/praveen02102005

---

## License

MIT License

## ⭐ Support

If you like this project, give it a ⭐ on GitHub.
