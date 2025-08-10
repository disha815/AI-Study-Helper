# AI Study Helper

A web-based tool to assist with AI study tasks. This project includes a Python backend and a HTML,JS, and CSS frontend. The tool will allow users to input their AI study tasks and track their progress.

## Why Built This Project

The idea behind building AI Study Helper was to simplify and enhance the study process using AI. Many students and professionals struggle with information overload, time management, and organizing study materials. This project aims to provide quick summarization, instant Q&A, and automated note/flashcard generation, making learning more efficient, interactive, and accessible for everyone.

AI Study Helper was created to make studying more efficient and interactive by leveraging AI for summarization, Q&A, and note generation. The goal is to help students and professionals save time, improve retention, and make learning more engaging.

## Tech Stack

- **Backend:** Python (Flask framework)
- **Frontend:** HTML, CSS, JavaScript
- **AI/ML:** Hugging Face Transformers, NLTK
- **Other:** Git, GitHub for version control

## Key Features

- User-friendly web interface for easy interaction
- AI-powered study assistance (summarization, Q&A, or note generation)
- Fast search and retrieval of study materials
- Customizable backend logic for different AI tasks
- Responsive design for desktop and mobile

## Use Case

**AI Study Helper** is ideal for students and professionals who want to:

- Summarize large documents or notes quickly
- Get instant answers to study-related questions
- Organize and retrieve study materials efficiently
- Generate study notes or flashcards using AI

## Usage Examples

### Example 1: Summarize Notes

Upload a PDF or paste your notes, and the AI will generate a concise summary.

### Example 2: Ask Questions

Type a question related to your study material and get an instant AI-generated answer.

### Example 3: Generate Flashcards

Provide a topic or document, and the app will create flashcards for revision.

<!-- You can add screenshots here by placing images in the static/ folder and referencing them, e.g.:
![Screenshot](static/screenshot1.png)
-->

## Project Structure

```
example.py           # Main Python backend
requirements.txt     # Python dependencies
static/              # Static files (JS, CSS)
templates/           # HTML templates
```

## Setup

1. Clone the repository:
   ```
   git clone https://github.com/disha815/AI-Study-Helper.git
   cd AI-Study-Helper
   ```
2. (Recommended) Create a virtual environment:
   ```
   python -m venv venv
   venv\Scripts\activate   # On Windows
   # source venv/bin/activate   # On macOS/Linux
   ```
3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
4. Run the app:
   ```
   python example.py
   ```
5. Open your browser and go to `http://localhost:5000` (or the port specified in your app).

## Customization

- Edit `example.py` to change backend logic.
- Update files in `static/` and `templates/` for frontend changes.

## Future Work

- Integrate more advanced AI models for better summarization and Q&A
- Add user authentication and personalized dashboards
- Support for more file formats (e.g., DOCX, PPTX)
- Mobile app version
- Collaboration features for group study

## Contribution Guidelines

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch for your feature or bugfix
3. Make your changes and commit them with clear messages
4. Push to your fork and submit a pull request
5. Describe your changes in detail in the PR

## License

MIT License
