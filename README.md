AI Mock Interviews
An AI-powered interview preparation platform built with Next.js, React, TypeScript, and Firebase.
Features
- User authentication
- Interview practice
- Interview feedback
- Responsive user interface
Features may depend on the services and configuration enabled in your deployment.

Tech Stack
- Frontend: Next.js, React, TypeScript
- Styling: Tailwind CSS
- Backend services: Firebase
- Package manager: npm
Getting Started
Prerequisites
- Node.js
- npm
- The environment variables required by this application
1. Clone the repository
git clone https://github.com/prashant1039/Ai-interview.git
cd Ai-interview
2. Install dependencies
npm install
3. Configure environment variables
Create a .env.local file in the project root and add the environment variables required by your local setup.
Security: Never commit .env.local, API keys, service-account credentials, or other secrets to GitHub.
4. Start the development server
npm run dev
Open http://localhost:3000 in your browser.
Project Structure
app/          Application routes and pages
components/   Reusable UI components
constants/    Application constants
firebase/     Firebase configuration
lib/          Utilities and server actions
public/       Static assets
types/        TypeScript type definitions
Available Scripts
Command	Description
npm run dev	Start the development server
npm run build	Build the application for production
npm run start	Start the production server
npm run lint	Run lint checks if configured in package.json


Author
Prashant Singh
GitHub: @prashant1039
