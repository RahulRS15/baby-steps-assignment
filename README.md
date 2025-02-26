BabySteps Appointment Booking System
A modern appointment booking system for prenatal care services built with React, TypeScript, and Vite. This system allows patients to book appointments with doctors through an intuitive interface.

Features
Interactive doctor selection interface with doctor cards
Appointment booking system with:
Calendar-based date selection (weekends and past dates disabled)
Time slot selection in 30-minute intervals
Patient information form with validation
Real-time feedback using toast notifications
Responsive design for all screen sizes
Modern UI using shadcn/ui components
Project Structure
babysteps-appointment-system/
├── src/
│   ├── pages/            # Main application pages
│   ├── components/       # Reusable UI components
│   ├── hooks/           # Custom React hooks
│   ├── lib/             # Utility functions
│   └── App.tsx          # Root component
└── README.md            # Project documentation
Tech Stack
Framework: React with TypeScript
Build Tool: Vite
UI Components:
shadcn/ui (based on Radix UI)
Lucide React for icons
Styling: Tailwind CSS
Date Handling: React Day Picker with date-fns
Routing: React Router DOM
State Management: React Query
Form Handling: React Hook Form
Design Decisions & Assumptions
Authentication is not implemented in the current version
Working hours are set to:
Monday to Friday
Morning: 9:00 AM - 12:00 PM
Afternoon: 2:00 PM - 5:00 PM
Appointments are fixed at 30-minute intervals
All times are handled in 24-hour format
The system uses local timezone for simplicity
Appointment slots are currently handled in-memory (no backend persistence)
Development Setup
Clone the repository:
git clone https://github.com/RahulRS15/baby-steps-assignment.git
Install dependencies:
npm install
Start the development server:
npm run dev

Usage
Browse the list of available doctors on the home page
Click "Book Appointment" for your chosen doctor
Select an available date from the calendar
Choose a time slot from the available options
Fill in your personal information
Submit the booking form
Receive confirmation via toast notification
Project Status
This is the frontend implementation of the BabySteps Appointment Booking System. Currently, the application stores data in-memory and provides a complete user interface for booking appointments. Backend integration for data persistence can be implemented in future iterations.

