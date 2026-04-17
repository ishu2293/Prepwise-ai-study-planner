# PrepWise: AI-Powered Study Planner 🚀
<img width="1836" height="908" alt="Screenshot 2026-04-17 180654" src="https://github.com/user-attachments/assets/8ce702be-0896-4024-8f13-70360737f62d" />
<img width="987" height="682" alt="Screenshot 2026-04-17 171858" src="https://github.com/user-attachments/assets/6e014e87-bff9-4b88-b704-c38ca7214b9a" />
<img width="1377" height="862" alt="image" src="https://github.com/user-attachments/assets/7583369b-c0d2-470e-826e-115a2b0cfb6c" />


**PrepWise** is an intelligent, full-stack study planning application designed to help students and professionals optimize their learning schedules. By leveraging the power of AI, PrepWise transforms generic study goals into highly detailed, day-by-day actionable plans, ensuring you stay organized and focused on your academic or professional journey.

## ✨ Key Features

- **AI-Powered Task Generation**: Simply describe your study goal in natural language (e.g., "I need to study Physics for 5 hours"), and our AI will break it down into a precise, hour-by-hour schedule.
- **Dynamic 30-Day Schedule**: Get a realistic, auto-generated study schedule that adapts to your needs, helping you pace your learning over a month.
- **Smart Reminders**: Receive timely notifications for upcoming study sessions and deadlines, ensuring you never fall behind.
- **Progress Tracking**: Monitor your completed study hours and visualize your progress with intuitive charts.
- **Customizable Study Blocks**: Block out specific times in your day (e.g., classes, work, meals) to ensure the AI creates a schedule that fits your life.
- **Dark Mode**: A sleek, eye-friendly dark theme for comfortable late-night study sessions.

## 🛠️ Tech Stack

### Frontend
- **HTML5**: Structure and semantics.
- **CSS3**: Custom properties (variables), glassmorphism effects, and responsive design.
- **JavaScript (Vanilla)**: Client-side logic, API integration, and DOM manipulation.
- **Chart.js**: Data visualization and progress charting.

### Backend
- **Node.js**: Server-side runtime environment.
- **Express.js**: Web framework for building the API.
- **MongoDB**: NoSQL database for storing user data and study plans.
- **Groq API**: Integration with the Groq AI service for intelligent task generation.

## 📂 Project Structure

```
PrepWise---AI-Study-Planner/
├── backend/                # Server-side application
│   ├── config/             # Database configuration
│   ├── models/             # Mongoose schemas (User, StudyTask)
│   ├── routes/             # API endpoints (auth, study, user)
│   ├── server.js           # Application entry point
│   └── .env                # Environment variables (API keys, DB URI)
├── frontend/               # Client-side application
│   ├── css/                # Stylesheets
│   ├── js/                 # JavaScript logic (auth.js, dashboard.js, api.js)
│   ├── index.html          # Login/Signup page
│   └── dashboard.html      # Main study dashboard
└── README.md               # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v14 or higher)
- [MongoDB](https://www.mongodb.com/) (local or cloud-based like MongoDB Atlas)
- [Groq API Key](https://groq.com/)

### Installation & Setup

1.  **Clone the repository** (or download the source code).

2.  **Backend Setup**:
    - Navigate to the backend directory: `cd backend`
    - Install dependencies: `npm install`
    - Create a `.env` file in the `backend` directory with the following credentials:
      ```env
      MONGODB_URI=your_mongodb_connection_string
      GROQ_API_KEY=your_groq_api_key
      PORT=5000
      ```
    - Start the server: `node server.js`

3.  **Frontend Setup**:
    - Open the `frontend/dashboard.html` file in your web browser.
    - (Optional) If running locally with a backend, you may need to adjust the API base URL in `frontend/js/api.js` to match your backend server address (e.g., `http://localhost:5000`).

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, create a feature branch, and submit a pull request.
