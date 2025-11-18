# Job Tracker

## Project Overview
The Job Tracker is a comprehensive application designed to help users efficiently manage and monitor their job application progress. In today's competitive job market, it's easy to lose track of applications, interviews, and follow-ups. This tool provides a centralized platform to keep all job-related activities organized, ensuring users never miss an important step in their job search journey.

## Features
- **Application Tracking:** Log and track the status of each job application (e.g., Applied, Interview, Offer, Rejected).
- **Progress Monitoring:** Visualize your job search progress with an intuitive dashboard.
- **Email OTP Verification:** Secure user authentication using email-based One-Time Passwords (OTP).
- **User-Friendly Interface:** A modern and responsive design built with Shadcn UI.

## Technologies Used

### Frontend
- **Framework:** Next.js
- **UI Library:** Shadcn UI
- **Language:** TypeScript
- **Hosting:** Vercel

### Backend
- **Framework:** FastAPI
- **Database:** PostgreSQL
- **Email Service:** Brevo (for OTP)
- **Hosting:** Render

## Setup and Installation
To get a local copy up and running, follow these simple steps.

### Prerequisites
- Node.js (for frontend)
- Python (for backend)
- PostgreSQL (database)

### Backend Setup
1. Navigate to the `Rolio-backend` directory.
2. Install dependencies: `pip install -r requirements.txt`
3. Configure your PostgreSQL database connection and Brevo API keys in the environment variables.
4. Run the application: `uvicorn main:app --reload`

### Frontend Setup
1. Navigate to the `Rolio-frontend` directory.
2. Install dependencies: `npm install` or `pnpm install`
3. Configure your backend API endpoint in the environment variables.
4. Run the development server: `npm run dev` or `pnpm dev`

## Deployment
- The frontend is deployed on **Vercel**.
- The backend is deployed on **Render**.

## Screenshots
*(Add screenshots of the application here to showcase its features and UI)*

## Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
Distributed under the MIT License. See `LICENSE` for more information.
