# ChebebTN

ChebebTN is a **MERN-Stack mobile application** designed to help job seekers in Tunisia find opportunities and connect with employers.  

## 🚀 Features
- Smooth and a UI friendly Interface for both employers and job seekers.
- Employers can post and manage job opportunities(view , edit, delete).
- Job seekers can search and apply at any open job wanted.

## 🛠️ Tech Stack
- **Frontend:** React Native, Expo  
- **Backend:** Node.js, Express.js, MongoDB  
- **Authentication:** JWT (JSON Web Tokens), bcrypt(for hashing passwords)

## 📸 Screenshots
<p align="center">
<img height="600" alt="1" src="https://github.com/user-attachments/assets/c62016d6-a1b6-4a64-9171-968fd2fd9988" />
<img height="600" alt="2" src="https://github.com/user-attachments/assets/b34d4d29-6a30-438b-8203-81462ceaf7dc" />
<img height="600" alt="3" src="https://github.com/user-attachments/assets/73a14a26-f3af-414f-83e6-e9717c933027" />
<img height="600" alt="4" src="https://github.com/user-attachments/assets/ed1f0a53-8c67-45de-8505-1b48d2d74a1a" />
<img height="600" alt="5" src="https://github.com/user-attachments/assets/879a0baa-5db5-44bc-84d7-a7ed95996e93" />
<img height="600" alt="6" src="https://github.com/user-attachments/assets/b60256c1-f849-4ec4-bacd-ce69b93ada86" />
<img height="600" alt="7" src="https://github.com/user-attachments/assets/0401c2fa-d9ef-4bbe-a7a4-f2107fc12641" />
</p>

## 📂 Project Structure
This repository uses **Git submodules** to manage frontend and backend separately:  

ChebebTN/ <br>
│── frontend/   → React Native app (Expo) <br>
│── backend/    → Node.js + Express.js + MongoDB server  

## 🔧 Installation & Setup

### 1. Clone the repository
```bash
git clone --recurse-submodules https://github.com/Yasmine-Hmida/ChebebTN.git
cd ChebebTN

# Install Dependencies for frontend and Run it
cd frontend
npm install
npx expo start

# Install dependencies for backend and Run it
cd ../backend
npm install
node index.js
