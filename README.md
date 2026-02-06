College Admissions Assistant – Gen-AI Chatbot
A Gen-AI powered, Gen-Z friendly chatbot that helps students navigate the college admission process efficiently by providing compressed, clear, and interactive information about courses, fees, hostels, and admission booking.
Built for hackathons, runs locally, and uses open-source LLMs only (no paid APIs).
🚀 Project Overview
The College Admissions Assistant chatbot:
Guides students through course selection
Explains fee structures clearly
Calculates hostel fees based on preferences
Applies admission fee waiver for meritorious students
Generates a final admission bill & slot booking receipt
Uses an LLM (FLAN-T5) for friendly Gen-Z style responses
🧠 Key Features
🤖 Gen-AI Powered Responses (FLAN-T5 – open source)
📚 Multiple Engineering Courses
🏨 Hostel selection:
AC / Non-AC
4-Sharing, 3-Sharing, 2-Sharing, Single
💸 Automatic fee calculation
🎓 Admission fee waiver for students with 80%+ marks
🧾 Final bill generation
📞 Admission office contact details
🖥️ Runs fully in Terminal (CLI)
🍎 Fully compatible with macOS
🛠️ Tech Stack
Python 3
Transformers (HuggingFace)
FLAN-T5 (google/flan-t5-small)
Rule-based logic + lightweight NLP
No paid APIs
No external databases
📁 Project Structure
college_admission_chatbot/
│
├── main.py
├── requirements.txt
│
├── chatbot/
│   └── chatbot.py
│
├── llm/
│   └── llm_loader.py
│
├── data/
│   └── university_data.py
│
├── logic/
│   ├── admission_fee.py
│   ├── hostel.py
│   ├── billing.py
│   └── student.py
⚙️ Installation (macOS)
1️⃣ Clone the Repository
git clone https://github.com/your-username/college_admission_chatbot.git
cd college_admission_chatbot
2️⃣ Create Virtual Environment
python3 -m venv venv
source venv/bin/activate
3️⃣ Install Dependencies
pip install -r requirements.txt
If Torch causes issues on Apple Silicon:
pip install torch --index-url https://download.pytorch.org/whl/cpu
▶️ Run the Chatbot
python main.py
💬 Sample Flow
Welcome message from JAI University chatbot
Select engineering course
Choose hostel (optional)
Select AC / Non-AC
Select sharing type
Enter student details
Admission fee waived automatically if marks ≥ 80%
Final bill generated
Admission slot booked 🎉
📞 Admission Office Contact
Admission Office: 9876543210
Student Help Desk: 9123456780
Email: admissions@jaiuniversity.edu
🏆 Hackathon Ready
✅ No paid APIs
✅ Offline & local execution
✅ Clean modular architecture
✅ Beginner-friendly
✅ Gen-AI + rule-based hybrid design
📌 Future Enhancements
Streamlit Web UI
Chat memory
Multilingual support
Voice assistant
Database integration
👨‍💻 Author
Developed as part of a Gen-AI Hackathon project focused on building practical AI solutions for Gen-Z.
If you want, I can also:
Create a GitHub description
Add screenshots section
Prepare hackathon PPT
Create architecture diagram
