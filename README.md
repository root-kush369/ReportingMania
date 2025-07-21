# Reportify - Reporting Engine

Welcome to **Reportify**, a sleek reporting tool designed to generate and export detailed reports for systems like finance, HR, and CRM. Perfect for tracking and sharing insights with ease!

## Features
- **Dynamic Filters**: Filter reports by date, category, user, and region.
- **Report Table**: View data in a clean, pivot-like table.
- **PDF Export**: Download filtered reports as PDFs.
- **Email Scheduling**: Schedule and send reports via email.

## Tech Stack
- **Frontend**: React with Vite and Tailwind CSS for a modern UI.
- **Backend**: Node.js with Express for API handling.
- **Database**: Supabase for storing report data.
- **Tools**: jsPDF for PDF generation, Nodemailer for emails.

## Getting Started

### Prerequisites
- Node.js installed
- A Supabase account
- A Gmail account for email setup

### Installation
1. Clone the repo:
   ```bash
   git clone https://your-repo-url.git
   cd reportify

2. Set up the backend:
   - Go to backend folder
     ```bash
     npm install
   - Create a .env file in backend with your Supabase and Gmail credentials (see .env.example if provided).

3. Set up the frontend:
   - Go to frontend folder:
     ```bash
     npm install
4. Run the project:
   - Start backend:
     ```bash
     cd backend
     node index.js
   - Start frontend:
     ```bash
     cd ../frontend
     npm run dev
         
   - Open http://localhost:5173 in your browser.

## Usage
-  Add new reports using the form.
-  Apply filters to view specific data.
-  Export to PDF or schedule an email with the filtered reports.

## Deploying
  This project can be deployed on platforms like Netlify (for frontend) and a backend service. Check deployment docs for details.

## Credits
  Built with love by [Kush Bhardwaj] using simple, powerful tools!
   
