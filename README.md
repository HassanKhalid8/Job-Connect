# JobConnect 🚀

JobConnect is a modern, serverless recruitment platform designed to bridge the gap between recruiters and job seekers. Built with a focus on speed and user experience, it allows for real-time interaction and automated workflows.

## ✨ Features

### For Job Finders
- **Job Search:** Browse and search through active job listings.
- **Favorites:** Save jobs to view or apply for later.
- **Quick Apply:** Apply for positions by uploading your CV directly through the platform.
- **Real-time Chat:** Once hired or shortlisted, chat directly with HR/Recruiters.
- **Auto-Notifications:** Receive an email immediately when your application is approved or a meeting is scheduled.

### For Recruiters
- **Job Management:** Post new job opportunities with ease.
- **Candidate Review:** Access a dedicated dashboard to check CVs and applicant details.
- **Streamlined Hiring:** Approve candidates and initiate real-time chats.
- **Interview Scheduling:** Schedule meetings directly; an automatic email is sent to the candidate with the details.

## 🛠️ Tech Stack

- **Language:** JavaScript (JSX)
- **Frontend:** [React.js](https://reactjs.org/) (Vite)
- **Styling:** CSS3 (Featuring Glassmorphism and Responsive Timelines)
- **Backend-as-a-Service:** [Google Firebase](https://firebase.google.com/)
- **Database:** Cloud Firestore (NoSQL)
- **Authentication:** Firebase Auth
- **Email Service:** [EmailJS](https://www.emailjs.com/) (Serverless email triggering)

## 🚀 Getting Started

### Prerequisites
- Node.js installed
- A Firebase project set up
- An EmailJS account and templates configured

### 🚀 Installation & Setup
1. **Clone the repo:**
   ```bash
   git clone [https://github.com/HassanKhalid8/Job-Connect.git](https://github.com/HassanKhalid8/Job-Connect.git)

2. **Install Dependencies**
   Run the following command in your terminal to install all necessary packages for the project:
   ```bash
   npm install

3. **Configure Environment Variables**
   Create a file named .env in the root folder of your project and add your specific credentials.
   Note: Since this project uses Vite, all environment variables must start with the prefix VITE_ to be accessible in your code.
   ```bash
   VITE_FIREBASE_API_KEY=your_api_key
   VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
   VITE_FIREBASE_PROJECT_ID=your_project_id
   VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
   VITE_FIREBASE_MESSAGING_SENDER_ID=your_messaging_id
   VITE_FIREBASE_APP_ID=your_app_id
   VITE_EMAILJS_SERVICE_ID=your_service_id
   VITE_EMAILJS_TEMPLATE_ID=your_template_id
   VITE_EMAILJS_PUBLIC_KEY=your_public_key

4. **Start the Development Server**
   Once the dependencies are installed and your environment variables are set, run the following command to start the app locally:
   ```bash
   npm run dev
