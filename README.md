# E-Patient Management System

A full-stack React application for managing patient profiles, education, skills, and work experience. Built with React, Tailwind CSS, and Vercel deployment. User data is stored locally and can be extended to a backend.

---

## Features

- **User Profiles**
  - View and edit basic information (name, email, phone, address, etc.)
  - Dynamic country and state selection
- **Education & Skills**
  - Add and edit education details
  - List skills and projects
- **Work Experience**
  - Add multiple experiences with domain, sub-domain, and years
  - Upload LinkedIn profile and resume (PDF)
- **Interactive UI**
  - Profile cards, editable forms, and tab navigation
  - Responsive design using Tailwind CSS
- **Persistent Storage**
  - Uses `localStorage` for user data
  - Can be extended to a backend API

---

## Tech Stack

- **Frontend:** React, Tailwind CSS, React Router
- **Icons:** Lucide React
- **Deployment:** Vercel
- **State Management:** React Context API (UserContext)

---

## Project Structure

/src
/components
- ProfileCard.jsx
- ProfileTabs.jsx
- EducationSkills.jsx
- ExperienceSection.jsx
/context
- UserContext.jsx
/pages
- Profile.jsx
App.js

yaml
Copy code
