# 📑 AI-Powered Applicant Tracking System (ATS) — Google Gemini Pro

An intelligent Applicant Tracking System (ATS) designed to streamline your hiring process by leveraging cutting-edge Generative AI (Google Gemini Pro), flexible workflows, and robust PDF parsing.

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository  
Clone the repository and change into the project directory:

git clone https://github.com/krgau020/ATS_Application_Tracking_System_usingGEMINI.git  
cd ATS_Application_Tracking_System_usingGEMINI

---

### 2️⃣ (Optional) Create a Virtual Environment  
It’s recommended to create and activate a virtual environment.

Create:  
python -m venv venv

Activate it:  
**Linux/Mac:**  
source venv/bin/activate

**Windows:**  
venv\Scripts\activate

---

### 3️⃣ Install Dependencies  
Install the required Python packages:

pip install -r requirements.txt

---

### 4️⃣ Add Your Google Gemini Pro API Key  
Create a `.env` file in the project root and add your API key like this:

GOOGLE_API_KEY=YOUR_GEMINI_API_KEY

---

## 🚀 Usage  
Run the app or notebook:

- Use the provided notebooks or scripts to process resumes.
- Upload PDF resumes — the system will:
  - Extract skills, experience, and qualifications using Google Gemini Pro’s NLP.
  - Parse and manipulate PDFs with PyPDF2.
  - Use LangChain to run modular, customizable automation workflows.
  - Return structured data for candidate evaluation.

---

## ✅ Requirements  
- Python 3.8+  
- Google Gemini Pro API key

---

## 🌟 Features  
- **Resume Extraction & Analysis:** Extract key details from resumes with Gemini Pro’s advanced NLP.  
- **Flexible Automation Workflows:** Use LangChain to create modular pipelines for different hiring processes.  
- **PDF Parsing & Manipulation:** Integrate and manage PDF resumes easily with PyPDF2.

---

## 📈 Example Use Case  
Upload multiple candidate resumes → extract and analyze key information → automate screening → shortlist top candidates.
