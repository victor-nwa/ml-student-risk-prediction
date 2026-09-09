Victor Nwachukwu
2509494

Student Early Warning Portal

A web-based Student Early Warning Portal developed as part of an MSc Data Science & AI project.

The system uses early learner activity data, including assessment submission behaviour, scores and online learning engagement, to identify learners who may be at risk of failing or withdrawing. The portal presents these predictions to staff as a decision-support tool to help prioritise early intervention.

Running the Project

1. Prerequisites
   
Git

Python 3.x

Node.js and npm

A web browser

2. Clone the Repository

   cd documents

   git clone https://github.com/victor-nwa/ml-student-risk-prediction.git

   cd ml-student-risk-prediction

Backend Setup

3. Create and activate the Python Virtual Environment

   cd documents/ml-student-risk-prediction

   python3 -m venv venv

   source venv/bin/activate

4. Install Backend Dependencies

   python -m pip install --upgrade pip

   python -m pip install -r requirements.txt

5. Start the Backend

   unicorn backend.main:app --reload

   Keep this terminal running.

Frontend Setup

6. Install Frontend Dependencies

   cd documents/ml-student-risk-prediction/frontend

   npm install

7. Start the Frontend

   npm run dev

   The terminal will display the local frontend website link

   Open the displayed address in a web browser

Admin Login

Email: admin@earlywarning.local

Password: Admin@2026Portal!
   
