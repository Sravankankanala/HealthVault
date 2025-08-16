🩺 HealthVault – Digital Health Record Manager

HealthVault is a comprehensive digital health record management system designed to connect patients, doctors, and diagnostic centers seamlessly. It simplifies uploading, accessing, and securely sharing medical records — ensuring efficiency and confidentiality.

🚀 Project Overview

HealthVault provides an integrated platform tailored for three user roles:

Patients – Upload, access, and manage their medical records.

Doctors – View patient records via secure OTP-based access and add prescriptions.

Diagnostics – Upload lab reports without viewing patient data, maintaining strict privacy.

💡 Innovation & Key Features

🔐 Role-Based Access Control – Separate permissions for Patients, Doctors, and Diagnostics to protect sensitive data.

📲 OTP-Based Secure Sharing – Doctors receive one-time links to access records safely.

📊 Smart Record Management – Patients can search, filter, and organize their entire medical history.

🌐 Lightweight & Developer-Friendly – Uses JSON Server as a mock backend, removing complex DBMS setup.

🧩 Tech Stack
Frontend

React.js

Tailwind CSS (or Bootstrap, if used)

Axios

Backend

Node.js

Express.js

JSON Server (for development as a fake API)

🏗️ Folder Structure
HealthVault/
├── frontend/ # React frontend
│ ├── public/
│ └── src/
│ ├── components/
│ ├── pages/
│ └── App.js
├── backend/ # Express backend
│ ├── controllers/
│ ├── routes/
│ ├── db.json # Fake JSON database
│ └── index.js # Entry point
