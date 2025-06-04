# Samsung-Servy

# 📝 Survey App

A full-stack survey application built with **Express.js**, **PostgreSQL**, and a clean, responsive frontend using **HTML**, **CSS**, and **JavaScript**. This app allows users to submit lifestyle surveys, stores responses in a database, and visualizes the data using charts.


---

✨ Features

- 📋 Submit lifestyle data via a form
- 📊 View all submitted survey responses
- 🌗 Toggle between light and dark mode
- 📈 Interactive chart (Chart.js) to visualize lifestyle categories
- 🔄 Instant updates after submitting a survey

---

 🛠 Tech Stack

**Frontend**
- HTML5 + CSS3
- Vanilla JavaScript
- Chart.js
- Responsive Design

**Backend**
- Node.js + Express.js
- PostgreSQL (with `pg` module)

**Dev & Deployment**
- Local development with Node & Postgres
- Deployed backend on [Render](https://render.com)
- Deployed frontend on [Netlify](https://netlify.com)

---

🚀 Getting Started

#1. Clone the repository


git clone https://github.com/Tony772/samsungservy.git
cd survey-app


2. Install backend dependencies
bash

cd backend
npm install

3. Set up your PostgreSQL database
Create a database named surveydb and run:

sql

CREATE TABLE responses (
  id SERIAL PRIMARY KEY,
  age INTEGER NOT NULL,
  gender TEXT NOT NULL,
  lifestyle TEXT NOT NULL,
  submitted_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

4. Configure .env or hardcode your credentials
env

PGUSER=Tony
PGPASSWORD=
PGHOST=localhost
PGDATABASE=surveydb
PGPORT=5432


5. Start the server
bash

node server.js


🧠 Project Structure
pgsql
📦 survey-app
├── backend
│   ├── server.js
│   └── package.json
├── frontend
│   └── index.html
├── README.md




🙋‍♂️ Author
Tony T Thobakgale
Portfolio Website
| GitHub https://github.com/Tony772/samsungservy.git

📌 License
This project is open-source and available under the MIT License.
