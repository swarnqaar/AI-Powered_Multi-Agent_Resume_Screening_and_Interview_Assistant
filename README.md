<div align="center">
  <img src="https://img.icons8.com/?size=150&id=42Lq0rW1rXn4&format=png&color=000000" alt="Robot Logo" width="120" height="120">
  <h1 align="center">🤖 AI-Powered Multi-Agent Resume Screening <br>& Interview Assistant</h1>
  
  <p align="center">
    A next-generation, multi-agent AI system designed to intelligently screen resumes, rank candidates, and conduct automated tailored interviews.
    <br />
    <br />
    <a href="#-features"><strong>Explore the Features »</strong></a>
    <br />
    <br />
    <a href="#">View Demo</a>
    ·
    <a href="#">Report Bug</a>
    ·
    <a href="#">Request Feature</a>
  </p>
</div>

---

## 🌟 Overview

The **AI-Powered Multi-Agent Resume Screening and Interview Assistant** is a cutting-edge platform designed to revolutionize the hiring process. By leveraging the power of Multi-Agent AI frameworks, this tool automatically parses resumes, evaluates them against specific job descriptions, and custom-crafts dynamic, personalized first-round virtual interview questions.

Say goodbye to manual resume filtering and hello to data-driven, unbiased candidate shortlisting! 🚀

---

## ✨ Key Features

- **🧠 Multi-Agent Collaboration**: Distinct AI agents working seamlessly together (Parser Agent, Evaluator Agent, Interviewer Agent, and Decision Agent) to synthesize insights.
- **📄 Smart Resume Screening**: Intelligently extracts key information (skills, experience, and education) from complex PDF and DOCX files.
- **🎯 Precision Matching**: Accurately scores candidates based on their semantic alignment with the given Job Description.
- **💬 Dynamic Interview Generation**: Formulates custom interview questions based on the candidate's unique background and the specific role requirements.
- **📊 Detailed Analytics & Reports**: Generates comprehensive summary reports, evaluation rubrics, and an objective hireability score.
- **🎨 Beautiful UI**: Easy-to-use, dark-mode ready, and intuitive interface crafted for HR professionals and technical recruiters alike.

---

## 🏗️ Architecture Workflow

The inner workings are powered by a robust, autonomous multi-agent architecture:

1. **`Manager Agent`**: Oversees the entire workflow, manages communication between agents, and delegates tasks.
2. **`Parsing Agent`**: Cleans and extracts structured JSON parameters (Skills, Work History, Education) from raw documents.
3. **`Evaluation Agent`**: Analyzes the gap between candidate qualifications and role requirements, assigning weighted match scores.
4. **`Interview Prep Agent`**: Dives deep into the candidate's resume to draft technical and behavioral questions designed to probe specific strengths or weaknesses.

---

## 🚀 Getting Started

Follow these steps to set up the project locally on your machine.

### Prerequisites

* Python 3.9+ or Node.js (depending on your final framework)
* OpenAI API Key (or an alternative LLM provider API key)
* `pip` or `npm` package manager

### Local Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/AI-Powered-Resume-Sceening-Assistant.git
   cd AI-Powered-Resume-Sceening-Assistant
   ```

2. **Set up a Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure Environment Variables**
   Create a `.env` file in the root directory and securely add your API keys:
   ```env
   OPENAI_API_KEY=your_openai_api_key_here
   ```

5. **Run the Application**
   ```bash
   # Replace with your app's start command (e.g., streamlit, uvicorn, etc.)
   python main.py 
   ```

---

## 💡 How It Works

1. **Upload Job Description**: Enter the target job role, responsibilities, and mandatory skills.
2. **Upload Resumes**: Drag and drop a batch of applicant resumes.
3. **Let the Agents Do the Magic**: Watch as the multi-agent orchestration extracts parameters, scores candidates, and creates an intelligent leaderboard.
4. **Generate Interviews**: Select top-tier candidates to generate customized interview questions and practical evaluation rubrics instantly.

---

## 🛠️ Recommended Tech Stack

* **Core AI Logic**: LangChain / CrewAI / AutoGen
* **LLMs**: OpenAI GPT-4o / Claude 3.5 Sonnet 
* **Backend**: Python, FastAPI
* **Frontend**: Next.js / React (with Tailwind CSS) OR Streamlit
* **Data Processing**: PyPDF2, Pandas

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 📫 Contact

Your Name - [@your_twitter_handle](https://twitter.com/) - email@example.com

Project Link: [AI-Powered Multi-Agent Resume Assistant](https://github.com/your-username/project-repo)

<hr>
<div align="center">
  <p>Made with ❤️ by a passionate Developer</p>
</div>
