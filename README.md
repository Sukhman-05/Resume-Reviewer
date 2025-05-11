# 📄 Resume Reviewer App

An intelligent web app built with **Streamlit** that uses **OpenAI's GPT model** to provide instant, AI-powered feedback on resumes. Designed to help job seekers improve clarity, structure, and relevance in their resumes—based on real-world best practices.

---

## 🚀 Features

- 🧠 **GPT-Powered Review**: Uses OpenAI's large language model to analyze and suggest improvements for uploaded resumes.
- 💬 **Detailed Feedback**: Highlights strengths, weaknesses, and missing keywords based on job descriptions.
- 🔍 **Job Description Matching**: Compare resume content to a specific job posting for better alignment.
- 🖼️ **Streamlit UI**: Clean and interactive interface that runs locally or can be deployed via Streamlit Cloud.
- 📄 **PDF or Text Support**: Accepts resumes in `.pdf`, `.txt`, or `.docx` formats.

---

## 🧰 Tech Stack

- **Frontend & Hosting**: [Streamlit](https://streamlit.io/)
- **AI Model**: [OpenAI GPT (e.g., GPT-3.5, GPT-4)](https://platform.openai.com/)
- **Backend Logic**: Python
- **Optional**: `PyPDF2`, `python-docx`, `dotenv`, `requests`

---
## Important
Get your own API key from [here](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbVVFU2ZtU1AxRE1YaHlvaUZpZFc2eWJvaThDZ3xBQ3Jtc0tsZzNpMGwyVzNIRi1SRGtaY2NCNmFvZkluWS1ZNWxGV1F5QzFjRjgtMlVORXdNcFlvUktGQzZ0dnRkeVpOYm0wcDJMVU5VcUVnWFdUaDk1T2lwQ0lpLThDTFJucUN6MFNOdzRXQmY4QlUzSDc1V2s4Zw&q=https%3A%2F%2Fplatform.openai.com%2Fapi-keys&v=XZdY15sHUa8) and paste it into the .env file

---

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/Sukhman-05/resume-reviewer.git
cd resume-reviewer

# Install dependencies
pip install uv
uv init .
uv install openai streamlit PyPDF2 python-dotenv

# Set your OpenAI API key
echo "OPENAI_API_KEY=your-api-key-here" > .env

# Run the app
uv streamlit run main.py
```

## 🔒 Security

Your resume is processed locally and via OpenAI's secure API.
No personal data is stored or shared.
