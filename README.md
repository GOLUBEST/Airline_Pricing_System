Airline Pricing System ✈️💰
An end-to-end Airline Pricing System built with a Python/Django backend and a React frontend to simulate and analyze flight fare behavior.

This project focuses on dynamic pricing concepts using flight schedules, airport data, and pricing logic to help evaluate ticket pricing trends and decisions.

📌 Table of Contents
Project Overview
Key Features
Tech Stack
Project Structure
Getting Started
Prerequisites
1) Clone Repository
2) Backend Setup (Django)
3) Frontend Setup (React)
How to Run the Project
Available Frontend Scripts
Data Files Used
Troubleshooting
Future Improvements
Contributing
License
🚀 Project Overview
The Airline Pricing System is designed to model and visualize airline pricing workflows.
It combines:

backend APIs and business logic (Django),
data processing for flights/airports,
frontend dashboards and UI components for interaction and visualization.
It can be extended into a full production-grade pricing intelligence platform.

✨ Key Features
Flight and airport data integration
Pricing engine module for fare-related calculations
Django-based backend project organization
React-based frontend interface
Data visualization dependencies (e.g., chart libraries)
SQLite database for local development
🧰 Tech Stack
Backend
Python
Django
SQLite (local DB)
Frontend
React (Create React App)
Material UI (MUI)
Axios
Nivo / Chart.js-based charting libraries
jsPDF (for export/report functionality)
🗂 Project Structure
Text
Airline_Pricing_System/
├── README.md
├── package.json
├── package-lock.json
├── airline_pricing/
│   ├── manage.py
│   ├── db.sqlite3
│   ├── Airports.csv
│   ├── flightsSchedule.csv
│   ├── airline_pricing/      # Django project settings module
│   └── pricing_engine/       # Core pricing logic
├── frontend/
│   ├── package.json
│   ├── package-lock.json
│   ├── public/
│   ├── src/
│   └── README.md
🛠 Getting Started
Prerequisites
Make sure these are installed on your machine:

Python 3.10+ (recommended)
pip
Node.js 18+
npm 9+
Git
1) Clone Repository
bash
git clone https://github.com/GOLUBEST/Airline_Pricing_System.git
cd Airline_Pricing_System
2) Backend Setup (Django)
Run these commands from the repository root:

bash
cd airline_pricing
python -m venv .venv
Activate virtual environment:

Windows (PowerShell):

bash
.venv\Scripts\Activate.ps1
Windows (CMD):

bash
.venv\Scripts\activate.bat
macOS / Linux:

bash
source .venv/bin/activate
Install backend dependencies:

bash
pip install -r requirements.txt
If requirements.txt is not present yet:

bash
pip install django
Apply migrations:

bash
python manage.py migrate
Start backend server:

bash
python manage.py runserver
Backend runs at: http://127.0.0.1:8000/

3) Frontend Setup (React)
Open a new terminal and run:

bash
cd frontend
npm install
npm start
Frontend runs at: http://localhost:3000/

▶️ How to Run the Project
To run full stack locally:

Start backend:
bash
cd airline_pricing
python manage.py runserver
Start frontend in another terminal:
bash
cd frontend
npm start
Ensure both servers are running simultaneously.

📜 Available Frontend Scripts
From frontend/ directory:

npm start → Run in development mode
npm run build → Build for production
npm test → Run tests
npm run eject → Eject CRA configuration
🧾 Data Files Used
Current data-related files in backend:

airline_pricing/Airports.csv
airline_pricing/flightsSchedule.csv
You can replace or extend these datasets to test different pricing scenarios.

🧯 Troubleshooting
Port already in use
Backend:
bash
python manage.py runserver 8001
Frontend: React will prompt for another port.
Module not found (frontend)
bash
cd frontend
npm install
Django not found
bash
pip install django
Virtual environment issues
Delete and recreate .venv, then reinstall dependencies.

🔮 Future Improvements
Add requirements.txt / pyproject.toml for reproducible Python setup
Dockerize backend + frontend
Add environment variable management (.env)
Implement authentication/role-based access
Add CI/CD pipeline (GitHub Actions)
Add unit/integration tests for pricing engine
Add API documentation (Swagger/OpenAPI)
🤝 Contributing
Contributions are welcome.

Fork the repository
Create a feature branch
Commit changes
Push branch
Open a Pull Request
📄 License
No license is currently specified in this repository.
Consider adding an open-source license (e.g., MIT) for clearer usage terms.

👤 Maintainer
GOLUBEST
GitHub: https://github.com/GOLUBEST

