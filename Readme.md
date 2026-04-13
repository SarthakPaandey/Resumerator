# Resumerator

A **web-based Resume Generator** that takes your LinkedIn PDF and automatically generates a professionally formatted HTML resume using AI (OpenAI or Google Gemini).

## 🔗 Live Demo

[resume-website-generator.vercel.app](https://resume-website-generator.vercel.app)

## ✨ Features

- 📎 **LinkedIn PDF Upload** — Upload your LinkedIn profile export PDF
- 🤖 **AI-Powered Parsing** — Uses OpenAI or Google Gemini to extract and format resume data
- 📝 **HTML Resume Generation** — Produces a clean, professional HTML resume
- 🎨 **Template-Based Output** — Consistent styling via pre-defined HTML resume templates
- ⚙️ **API Selection** — Choose between OpenAI or Gemini for generation

## 🛠️ Tech Stack

- **Python** — Core language
- **FastAPI** — Web application framework
- **OpenAI API / Google Gemini** — AI resume generation
- **Jinja2 HTML Templates** — Resume output formatting
- **Vercel** — Deployment

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/SarthakPaandey/Resumerator.git
cd Resumerator

# Create virtual environment
python -m venv myenv
source myenv/bin/activate  # or myenv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run the application
uvicorn app:app --reload
```

Open [http://localhost:8000](http://localhost:8000) in your browser.

## 📄 License

MIT
