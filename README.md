# career-assistant-ai

An AI-powered digital twin that represents my professional background
and answers questions about my career, experience, projects, and
technical skills.

Features

💬 Conversational AI interface with Gradio

👨‍💻 Career and professional profile context

📄 LinkedIn and career summary as knowledge sources

🔔 Pushover notifications for contact interactions

Tech Stack

Python

Gradio

OpenAI API

Pushover

Render

Project Structure

career-ai-twin/
├── app.py
├── context.py
├── tools.py
├── styles.py
├── requirements.txt
├── summary.txt
└── linkedin.pdf

Run Locally

pip install -r requirements.txt
python app.py

The app runs locally through Gradio.

Deployment

The app can be deployed on Render using:

Build: pip install -r requirements.txt
Start: python app.py

API keys should be stored as environment variables and never committed
to GitHub.

Author

Niraj Shaw

Software Test Engineer | QA Automation | AI Testing

LinkedIn: www.linkedin.com/in/niraj-shaw-b32994335
