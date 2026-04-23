# ⏰ Smart Deadline Reminder Pipeline

An AI-powered pipeline that reads ANY file you drop in — PDF, Word, Excel, or CSV — automatically extracts deadlines using Google Gemini AI, and sends you an email reminder 2 days before each deadline.

## 🔍 What it does
- Reads PDF, Word, Excel and CSV files automatically
- Uses Google Gemini AI to intelligently extract deadlines from any text
- Sends automated email reminders exactly 2 days before each deadline
- Scans your folder daily for new files

## 🛠️ Tech Stack
- Python
- Jupyter Notebook
- pdfplumber — read PDFs
- python-docx — read Word files
- pandas — read Excel/CSV
- Google Gemini AI — extract deadlines intelligently
- SMTP — automated email reminders
- python-dotenv — secure credentials

## 💡 Real World Use Case
Drop in your course syllabus, assignment sheet, or any document with deadlines — the pipeline finds every deadline automatically and reminds you 2 days before so you never miss anything.

## 🚀 How to Run
1. Clone the repo
2. Install dependencies: `pip install pdfplumber python-docx pandas google-genai schedule python-dotenv openpyxl`
3. Create a `.env` file with your credentials
4. Add your Gemini API key in the notebook
5. Drop any file with deadlines into the folder
6. Open `deadlineReminder.ipynb` in Jupyter Notebook
7. Run all cells: `Kernel → Restart & Run All`
