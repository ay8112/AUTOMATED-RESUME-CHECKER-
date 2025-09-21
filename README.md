Automated Resume Screening System

An AI-powered resume screening application that helps recruiters and placement cells automatically parse resumes and match them against job descriptions. This project is built using Streamlit and Natural Language Processing (NLP) to extract skills, education, and experience from resumes, then compare them with job requirements.

🚀 Features

Upload resumes in PDF/DOCX format.

Extract candidate details like:

Name

Email

Skills

Work Experience

Match resumes against a job description.

Generate a match score (0–100%) for quick shortlisting.

User-friendly Streamlit web interface.

🛠️ Tech Stack

Python 3.9+

Streamlit – Web application framework

spaCy – NLP for text extraction & analysis

docx2txt / PyPDF2 – Resume text extraction

scikit-learn / pandas – Data processing

📂 Project Structure
Automated-Resume-Screening-System/
│
├── app.py                # Main Streamlit app
├── requirements.txt      # Dependencies
├── utils/                # Helper functions
├── sample_resumes/       # Example resumes
└── README.md             # Project documentation

⚙️ Installation

Clone the repository:

git clone https://github.com/ay8112/Automated-Resume-Screening-System.git
cd Automated-Resume-Screening-System


Create and activate a virtual environment:

python -m venv venv
venv\Scripts\activate       # On Windows
source venv/bin/activate    # On Mac/Linux


Install dependencies:

pip install -r requirements.txt


Download the spaCy language model:

python -m spacy download en_core_web_sm

▶️ Run the App Locally
streamlit run app.py


Then open the URL shown in terminal (default: http://localhost:8501
) in your browser.

🌐 Deployment
Option 1: Streamlit Cloud (Recommended)

Push your repo to GitHub (AY8112/Automated-Resume-Screening-System).

Go to Streamlit Cloud
.

Connect your GitHub account and select this repo.

Choose app.py as the main file.

The app will deploy automatically with a free shareable URL.

Option 2: Hugging Face Spaces

Create a new Space → Select Streamlit as SDK.

Connect this GitHub repo.

The app will deploy automatically.

📸 Demo

Upload a resume and paste a job description → instantly see parsed details and a match percentage.

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

📜 License

This project is licensed under the MIT License.

✅ With this README, your repo will look professional, installable, and deployable.

