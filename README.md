# Rolio

<img width="1470" height="833" alt="image" src="https://github.com/user-attachments/assets/607c48aa-c801-4edd-8856-695945f41914" />

## Project Overview
Rolio is a comprehensive application designed to help users efficiently manage and monitor their job application progress. In today's competitive job market, it's easy to lose track of applications, interviews, and follow-ups. This tool provides a centralized platform to keep all job-related activities organized, ensuring users never miss an important step in their job search journey.

Link - https://rolio-frontend.vercel.app/auth

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
- **Language:** Python
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
<img width="1470" height="829" alt="image" src="https://github.com/user-attachments/assets/3f485af0-60a0-46ac-b08f-76ba54c8888e" />

<img width="1470" height="833" alt="image" src="https://github.com/user-attachments/assets/607c48aa-c801-4edd-8856-695945f41914" />

<img width="1470" height="831" alt="image" src="https://github.com/user-attachments/assets/8b162ae6-a187-40f5-8c2f-a812110bfbc4" />



## Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
Distributed under the MIT License. See `LICENSE` for more information.
