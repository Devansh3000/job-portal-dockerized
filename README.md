# Job Portal – Full Stack (Dockerized)

A full-stack **Job Portal application** built using **React (Vite)** for the frontend and **Node.js + Express** for the backend.  
The project is fully **Dockerized** using **Docker Compose**, making it easy to run on any system.

---

## 🚀 Tech Stack

### Frontend
- React (Vite)
- JavaScript
- HTML & CSS
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication

### DevOps
- Docker
- Docker Compose
- Nginx (for serving frontend)

---

## 📁 Project Structure

react-job-portal-main/
│
├── backend/
│ ├── Dockerfile
│ ├── package.json
│ ├── app.js
│ ├── server.js
│ ├── routes/
│ ├── models/
│ └── .env.example
│
├── frontend/
│ ├── Dockerfile
│ ├── package.json
│ ├── vite.config.js
│ └── src/
│
├── docker-compose.yml
├── .gitignore
└── README.md


---

## ⚙️ Prerequisites

Make sure you have the following installed:

- Docker
- Docker Compose
- Git

Check versions:
```bash
docker --version
docker compose version
git --version
🔐 Environment Variables
Create a .env file inside the backend folder.

Example:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
⚠️ Do NOT commit .env to GitHub.
Use .env.example for reference.

▶️ Run the Project with Docker
From the project root directory:

docker compose build
docker compose up
🌐 Access the Application
Frontend: http://localhost:3000

Backend API: http://localhost:5000

🛑 Stop the Application
docker compose down
✨ Features
User authentication using JWT

Job posting and job listing

RESTful backend APIs

Dockerized frontend and backend

Production-ready frontend using Nginx

📌 Future Enhancements
Add MongoDB container to Docker Compose

Role-based authentication (Admin / Recruiter / User)

CI/CD pipeline

Cloud deployment (AWS / Render / DigitalOcean)

👤 Author
Devansh

⭐ Support
If you like this project, please give it a ⭐ on GitHub!


---

## ✅ How to add it to GitHub

After pasting and saving:

```powershell<img width="1481" height="762" alt="Screenshot 2026-02-03 004514" src="https://github.com/user-attachments/assets/a1d04dff-1b1c-4cd0-925a-dce354503ed7" />

git add README.md
git commit -m "Add project README"
git push<img width="1471" height="480" alt="Screenshot 2026-02-03 004505" src="https://github.com/user-attachments/assets/c3f8f4e2-29f7-40aa-8333-f820a1ce5906" />


