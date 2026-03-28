🧠 Adaptive Memory System using Ebbinghaus Forgetting Curve

An AI-powered study reminder and revision scheduling system built using n8n, Google Sheets, Gmail, and HTML frontend.

This project helps students improve long-term memory retention by sending smart revision reminders based on the Ebbinghaus Forgetting Curve.


---

🚀 Features

👤 Student login / signup frontend

📚 Add study topic and revision time

⏰ Automated reminder scheduling

📧 Gmail reminders for each revision round

📊 Google Sheets as lightweight database

🔁 Multi-round revision flow (R1, R2, R3)

🧠 Based on Ebbinghaus Forgetting Curve

🏆 Perfect for hackathons and student projects



---

🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript

Automation: n8n

Database: Google Sheets

Notifications: Gmail

Logic: Ebbinghaus spaced repetition



---

📂 Workflow Architecture

HTML Form → Google Sheets → Read Rows → IF → Update Row
→ Wait → Gmail → Update Sent1 → Wait → Gmail → Update Sent2
→ Wait → Gmail → Update Sent3


---

📈 Ebbinghaus Revision Schedule

R1: After 30 minutes

R2: After 1 day

R3: After 3 days

R4: After 7 days


This schedule improves recall and reduces forgetting.


---

⚙️ Setup Steps

1. Clone this repository


2. Create Google Sheet with columns:

Name

Email

Topic

R1, Sent1

R2, Sent2

R3, Sent3



3. Import n8n workflow


4. Connect Gmail credentials


5. Update Google Sheets credentials


6. Run workflow




---

💡 Use Cases

Students preparing for exams

Competitive programming revision

Placement interview prep

Flashcard revision systems

Personalized learning assistants



---

🔮 Future Enhancements

Quiz generation after each revision

Email reminders

AI difficulty-based scheduling

Dashboard analytics

Mobile app integration



---

👩‍💻 Team Project Idea

Built as a CSE hackathon project to solve the
