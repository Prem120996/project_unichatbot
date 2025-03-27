# 🤖 Smart Chatbot for University Grievances

## 📝 Overview
The **Smart Chatbot for University Grievances** is an AI-powered solution designed to streamline the grievance resolution process for students and faculty. It provides an interactive chatbot to submit complaints, track their status, and receive automated responses for common university-related queries.

## ✨ Features
- **AI Chatbot with NLP** – Understands and processes user grievances intelligently.
- **Automated Complaint Registration** – Logs complaints with structured data.
- **Real-Time Query Resolution** – Provides instant responses to frequently asked questions.
- **User Authentication** – Secure login for students, faculty, and administrators.
- **Grievance Tracking** – Allows users to monitor complaint status.
- **Admin Dashboard** – Enables university officials to review and resolve grievances.
- **Firebase Integration** – Stores and retrieves grievance records securely.

## 🔧 Technologies Used
- **Backend**: Python ,Flask
- **Frontend**: HTML, CSS, JavaScript 
- **Chatbot & NLP**:  custom NLP models
- **Database**: Firebase Firestore
- **Authentication**: Firebase Authentication (OAuth/Email-Password)

## 🚀 Getting Started
### 📥 Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Prem120996/project_unichatbot.git
   ```
2. Navigate to the project directory:
   ```sh
   cd project_unichatbot
   ```
3. Install backend dependencies:
   ```sh
   pip install -r requirements.txt  # For Python-based backend
   ```
4. Install frontend dependencies:
   ```sh
   cd frontend
   npm install
   ```
5. Set up Firebase:
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
   - Enable Firestore Database and Authentication.
   - Download the `serviceAccountKey.json` file and place it in the backend directory.
   - Configure Firebase settings in `.env` or `firebase-config.js`.
6. Train the chatbot with predefined university-related queries.
7. Run the backend server:
   ```sh
   python app.py  # For Flask
8. Run the frontend server:
   ```sh
   npm start
   ```

## 📌 Usage
1. **User Login** – Authenticate using Firebase.
2. **Submit a Grievance** – Use the chatbot to register a complaint.
3. **Receive Updates** – Get automatic responses and track complaint status.
4. **Admin Review** – University staff can access and manage grievances.

## 🔮 Future Enhancements
- Voice recognition support for chatbot interaction.
- AI-powered complaint classification for faster resolution.
- Mobile app for enhanced accessibility.

## 🤝 Contribution
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`
3. Commit your changes: `git commit -m "Add new feature"`
4. Push to the branch: `git push origin feature-branch`
5. Open a Pull Request.

## 🛡️ License
This project is licensed under the MIT License.


