# AMRIT-YATRA

is a web-based application designed to facilitate user interaction with local governance regarding water status, complaints, and emergencies. The platform provides dashboards for both users and government officials, allowing for efficient complaint tracking, emergency reporting, and status monitoring.

Features
User and government login portals

Submission and tracking of complaints

Emergency reporting functionality

Dashboards for users and officials

Water status updates

Complaint management and viewing

Directory Structure
text
├── README.md
├── about.html
├── app.py
├── complaint.html
├── gov_dashboard.html
├── gov_login.html
├── gp.db
├── index.html
├── report_emergency.html
├── reset.js
├── style2.css
├── track_complaint.html
├── user_dashboard.html
├── User_login.html
├── usercredentials.db
├── view_complaint.html
├── view_complaints.html
└── water_status.html
Installation
Clone the repository:

bash
git clone <repository-url>
cd mahi0331-amrit-yatra
Install dependencies:

Ensure you have Python 3.x installed.

Install required packages (e.g., Flask):

bash
pip install flask
Set up the database:

The project uses SQLite databases (gp.db, usercredentials.db). These are included in the repository.

Run the application:

bash
python app.py
Usage
Open your browser and navigate to http://localhost:5000/

Use the login pages (User_login.html, gov_login.html) for respective dashboards.

Users can submit complaints, report emergencies, and track complaint status.

Government officials can view and manage complaints via their dashboard.

Technologies Used
Backend: Python (Flask)

Frontend: HTML, CSS, JavaScript

Database: SQLite
