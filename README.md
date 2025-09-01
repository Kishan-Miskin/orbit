# Orbit - Job/internship Application Tracker

ORBIT is a modern, responsive job application tracker built with React, TailwindCSS, Recharts, and Lucide icons. It allows users to manage, visualize, and analyze all their job applications in one place, making the job search process organized and efficient.

Features
1. Dashboard

View key statistics like:

Total Applications

Applications Applied

Interviews

Offers

Interactive Line Chart showing applications over the last 7 days.

Pie Chart showing status distribution (Applied, Interview, Offer, Rejected).

2. Applications Management

Add, edit, and delete job applications.

Track details such as:

Company Name

Position

Location

Salary

Status (Applied, Interview, Offer, Rejected)

Job Type (Full-time, Part-time, Contract, Internship)

Remote option

Notes

Application Date

Search and filter applications by company, position, or status.

Responsive cards layout for easy viewing.

3. Analytics

Bar Chart showing trends of applications over time.

Success metrics like:

Offer Rate

Interview Rate

Rejection Rate

4. Responsive Design

Mobile-friendly sidebar with toggle menu.

Desktop-ready layout with charts and cards.

Smooth modal transitions for adding and viewing applications.

5. Persistent Storage

All applications are stored in localStorage, ensuring data persists between sessions.

Installation

Clone the repository:

git clone <your-repo-url>


Install dependencies:

npm install


Start the development server:

npm start


Open http://localhost:3000
 in your browser.

Usage

Add Application: Click the Add Application button → fill in details → submit.

Edit/Delete/View: Each application card has Edit, Delete, and View buttons.

Search & Filter: Use the search bar or status filter to quickly find applications.

Dashboard & Analytics: Switch between Dashboard, Applications, and Analytics using the sidebar.

Tech Stack

React - Frontend library for UI

TailwindCSS - Styling and responsive design

Recharts - Charts and data visualization

Lucide-React - Icons

LocalStorage - Persistent storage
