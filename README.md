💼 Finance Cockpit – AI-Powered Personal Finance Workflow
A modular web application prototype that helps users plan, track, and optimize their personal finances using guided workflows and AI-driven insights. Built with vanilla HTML, Tailwind CSS, and local JS logic.

🚀 Demo Live at
🔗 https://bharathraj7720/finance-cockpit-poc

📘 Features
🔐 Authentication system with login and registration

🧩 Guided session initialization via personal details or JSON upload

💵 Income, 💸 Expense, 🧾 Loan, 📊 Mutual Fund & 📈 Stock tracking modules

🎯 Corpus planning with SIP/CAGR recommendations

📑 AI-generated financial reports with tone selection

📘 Session summary with export options

🧭 Workflow
Login / Register

Redirect to Session Setup page (personal-details.html)

Either start a new session or resume via uploaded .json

Workflow proceeds through:

module-income.html

module-expense.html

module-loan.html

corpus.html

report-generator.html

summary.html

🔧 Tech Stack
Layer	Tools Used
Styling	Tailwind CSS
Behavior	Vanilla JavaScript
Structure	Modular HTML pages
Storage	LocalStorage (temporary)
Deployment	GitHub Pages (static demo)
🧪 Quick Test Credentials
plaintext
Email: demo@cockpit.com
Password: 123456
Or register a fresh account via register.html

📂 File Structure
bash
finance-cockpit-poc/
├── index.html                  # Public landing page
├── login.html / register.html # Auth system
├── personal-details.html      # Session init/resume page
├── module-income.html         # Income tracking
├── module-expense.html        # Expense tracking
├── module-loan.html           # Loan tracking
├── corpus.html                # Goal planning
├── report-generator.html      # AI Report generation
├── summary.html               # Final overview
├── assets/                    # Charts, icons
├── scripts/                   # Future JS modules
├── README.md                  # You're reading it!
📂 Sample JSON Upload
json
{
  "userName": "Bharath",
  "userAge": "38",
  "userLocation": "Hyderabad, TG",
  "sessionName": "2025Plan"
}
Upload this file in personal-details.html to auto-fill your session

📣 Credits
Crafted by Bharath with financial clarity, technical precision, and user-centric design in mind. Enhanced by Microsoft Copilot ✨
