💰 AI-Powered Finance Assistant

A Flask-based **AI Finance Assistant** that helps users manage personal finances through **machine learning**, **data visualization**, and an **NLP-powered chatbot**.  
It classifies expenses, recommends personalized budgets, and provides detailed insights using interactive charts and reports.
 🧠 Features
✅ **Expense Classification** — Uses ML models to automatically categorize your transactions.  
✅ **Budget Recommendations** — Suggests smart budgets based on your spending patterns.  
✅ **Spending Analysis** — Visual dashboards (pie, bar, and trend charts) for better understanding.  
✅ **AI Chatbot** — NLP-based chatbot for financial advice and queries.  
✅ **PDF Report Generation** — Creates downloadable AI-based financial reports.  
✅ **Secure File Uploads** — Validates and processes CSV/Excel financial data safely.  
🧩 Technologies Used
- **Backend:** Python, Flask  
- **Machine Learning:** Scikit-learn, NumPy, Pandas  
- **Visualization:** Matplotlib, Seaborn  
- **Natural Language Processing:** TextBlob, NLTK  
- **Frontend:** HTML, CSS, Bootstrap  
- **Reporting:** ReportLab (for PDF generation)  
📂 Project Structure
financial-assistant/
│
├── app.py # Main Flask app
├── config.py # App configuration
│
├── ml_models/
│ ├── expense_classifier.py
│ ├── budget_recommender.py
│ └── nlp_chatbot.py
│
├── utils/
│ ├── data_processor.py
│ ├── visualization.py
│ ├── report_generator.py
│ ├── security.py
│ └── error_handler.py
│
├── static/ # CSS, JS, uploaded files
├── templates/ # HTML templates
│
├── requirements.txt # Python dependencies
└── Financial_Assistant_Project_Report.pdf
⚙️ Installation & Setup
1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/finance-assistant.git
cd finance-assistant
2️⃣ Create Virtual Environment
python -m venv env
source env/bin/activate  # (Linux/Mac)
env\Scripts\activate     # (Windows)
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Run the Application
python app.py
Visit http://127.0.0.1:5000
 in your browser to launch the dashboard.
OUTPUT:-
<img width="1920" height="1080" alt="Screenshot (128)" src="https://github.com/user-attachments/assets/5405643e-3ae9-49ff-8b72-13faff8f4a1a" />
<img width="1920" height="1080" alt="Screenshot (129)" src="https://github.com/user-attachments/assets/42cd8d1e-a623-4e4a-adab-f321f74f7bad" />
🧾 Project Report

A detailed project report including code explanation, architecture, and results can be found here:
📈 Future Enhancements
🚀 Integrate real-time expense APIs (like bank statements).
💬 Add speech-based financial query input.
📱 Build a mobile-friendly React frontend.
☁️ Deploy using AWS / Render / Railway.
👩‍💻 Author
Pudari Vyshnavi
AI & Machine Learning Enthusiast | Full Stack Developer
📧 Email:pudarivyshnavi@gmail.com
🌐 GitHub: pudarivyshnavi
⭐ If you like this project, don’t forget to star it on GitHub!
