# ViBo - Virtual Bookshelf Web App
A React + Vite application for discovering, saving, and managing books using live data from the Open Library API and NOVI’s authentication backend.

<p align="left">
  <img src="https://img.shields.io/badge/React-18-blue" />
  <img src="https://img.shields.io/badge/Vite-Frontend_Project-purple" />
  <img src="https://img.shields.io/badge/REST_API-Open_Library-green" />
  <img src="https://img.shields.io/badge/Auth-NOVI_Backend-yellow" />
</p>


![ViBo Screenshot](./src/assets/ViBoSearch.png)
---

## About this Project

ViBo (Virtual Bookshelf) is a multi-page React app that allows users to:
	•	create an account
	•	log in/out
	•	browse 25 random books on login
	•	search books by title, author, subject, keyword, or exclude an author
	•	view detailed book information
	•	search for authors and view their biographies + published works
	•	save books to a personal reading list
	•	remove saved books from their bookshelf
	•	update their account password
	•	explore books directly from the Open Library API

Originally built during my Frontend module of the NOVI Hogeschool Full Stack Developer bootcamp, the project was designed from scratch using Adobe XD for the UI/UX flow and is now refined into a polished portfolio piece.

### UI & Interaction Flow Design
[Adobe XD design files](https://xd.adobe.com/view/c8248d74-c1a0-4a77-994c-a5f5009ac048-9d77/) <br>

### Backend Services
NOVI Educational Backend: https://novi.datavortex.nl
(No API keys required.)

### Book Data Source
Open Library API: https://openlibrary.org/developers/api
(No keys required.)

---

## Tech Stack

### **Frontend**
	•	React 18
	•	Vite
	•	React Router
	•	Context API (AuthContext for global authentication state)
	•	CSS Modules for styling
	•	Async fetch calls to REST APIs

### **APIs & Services**
	•	Open Library API — book + author search, metadata
	•	NOVI Educational Backend — authentication, password updates

### **Dev Tools & Configuration**
	•	npm
	•	ESLint
	•	Vite dev server
	•	Component-based architecture

 ---

## What This Project Demonstrates
	•	Building a multi-page Single Page Application (SPA)
	•	Implementing authentication, registration, and protected routes
	•	Managing global auth state with React Context
	•	Integrating multiple public REST APIs
	•	Designing UI flows + layouts from Adobe XD prototypes
	•	Error handling, loading states, and conditional rendering
	•	Working with dynamic search parameters and large JSON responses
	•	CRUD-like interactions in a frontend app (save/remove books)

 ---

## Features
### User Authentication
Create an account, log in/out, update your password.

### Random Book Display
Shows 25 new books every time a user logs in.

### Flexible Search System
Search by title, keyword, subject, author, or exclude an author.

### Author Search
View biographies, author photos (when available), and book lists.

### Detailed Book View
Title, author, publication date, description, subjects, pages, languages.

### Personal Bookshelf
Save or remove books from your reading list.

### UI from Adobe XD
Exact layout and design system prototyped before development.

---

## Project Structure
```
vibo/
│
├── public/                 # Static files
├── src/
│   ├── pages/              # Login, Register, Profile, Search, BookDetail, etc.
│   ├── Components/         # Reusable UI components
│   ├── authContext.jsx     # Global authentication state
│   ├── bookApi.js          # All Open Library API calls
│   ├── global.module.css   # Global styling
│   ├── App.jsx             # Main routing setup
│   └── main.jsx            # App entry point
│
├── package.json
└── README.md
```
---
## Requirements 

### **Runtime**
Install Node.js:
https://nodejs.org/en/download

ViBo uses:
	•	Node.js
	•	npm

Both are required to install dependencies and run the app.

### **APIs**
	•	Open Library API — no key required
	•	NOVI backend — no key required
(If you want to use your own backend, integrate your API in `authContext.jsx`.)

---

## Installation
	1.	Install Node.js + npm
	2.	Clone the repository:


 git clone https://github.com/lauren-haan-gilbert/vibo.git

 or 

 git@github.com:lauren-haan-gilbert/vibo.git

 3. Install Dependencies

npm install

4. Optional: update npm

npm install -g npm@latest

---

## Getting Started 
### **Available npm commands**
`npm run dev`
Start the development server.

`npm run build`
Create a production build.

`npm run lint`
Run ESLint for code consistency.

`npm run preview`
Preview the production build locally.

---

## Test Account
You can create your own account or use:

username: ViboTest
password: ViboTest1234!

---

## Acknowledgements
	•	NOVI Hogeschool (Frontend module + backend service)
	•	Open Library API
	•	Adobe XD for prototyping
	•	Everyone who tested early versions of the app

