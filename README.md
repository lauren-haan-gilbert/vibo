#  ViBo – Virtual Bookshelf Web App
A React + Vite application for discovering, saving, and managing books using live data from the Open Library API and NOVI’s authentication backend.

<p align="left">
  <img src="https://img.shields.io/badge/React-18-blue" />
  <img src="https://img.shields.io/badge/Vite-Frontend_Project-purple" />
  <img src="https://img.shields.io/badge/REST_API-Open_Library-green" />
  <img src="https://img.shields.io/badge/Auth-NOVI_Backend-yellow" />
</p>

##  Preview
![ViBo Screenshot](./src/assets/ViBoSearch.png)

---

##  About this Project

**ViBo** (Virtual Bookshelf) is a multi-page React app that allows users to:

- create an account  
- log in/out  
- browse 25 random books at login  
- search books by title, author, subject, keyword, or exclude an author  
- view detailed book info  
- search for authors and view biographies + published works  
- save books to a personal reading list  
- remove books from their bookshelf  
- update account password  
- explore books using the Open Library API  

Originally built during the **NOVI Hogeschool Full Stack Developer bootcamp (Frontend module)**, ViBo was fully designed in Adobe XD before implementation.

###  UI & Interaction Flow Design  
https://xd.adobe.com/view/c8248d74-c1a0-4a77-994c-a5f5009ac048-9d77/

###  Backend Services  
NOVI Educational Backend (no API keys needed):  
https://novi.datavortex.nl

###  Book Data Source  
Open Library API: https://openlibrary.org/developers/api  
(No keys required.)

---

##  Tech Stack

### Frontend
- React 18  
- Vite  
- React Router  
- Context API (AuthContext)  
- CSS Modules  
- Fetching REST APIs  

### APIs & Services
- Open Library API — search + metadata  
- NOVI backend — authentication, password updates  

### Dev Tools
- npm  
- ESLint  
- Vite dev server  

---

##  What This Project Demonstrates

- Building a multi-page **Single Page Application (SPA)**  
- Implementing **authentication, protected routes, registration**  
- Global state management via **React Context**  
- Working with **multiple REST APIs**  
- UI prototyping with **Adobe XD**  
- Handling loading states + API errors  
- Dynamic search and filtering  
- CRUD-like bookshelf interactions  

---

##  Features

###  User Authentication  
Register, log in, log out, change password.

###  Random Book Display  
25 random books shown at every login.

###  Book Search  
Search by:
- title  
- keyword  
- subject  
- author  
- exclude author  

###  Author Search  
View author bio, photo, and published works.

###  Book Details  
Includes:
- title  
- author  
- publication date  
- pages  
- subjects  
- languages  
- description  

###  Personal Bookshelf  
Save or remove books from your reading list.

###  Adobe XD Design  
Interface designed fully before build.

---

##  Project Structure

```
vibo/
│
├── public/                 # Static assets
├── src/
│   ├── pages/              # Route pages
│   ├── Components/         # Reusable UI components
│   ├── authContext.jsx     # Global auth logic
│   ├── bookApi.js          # Open Library API helpers
│   ├── global.module.css   # Global styling
│   ├── App.jsx             # Routing
│   └── main.jsx            # Entry point
│
├── package.json
└── README.md
```
---

##  Requirements

### Runtime  
Install Node.js:  
https://nodejs.org/en/download

Uses:
- Node.js  
- npm  

### APIs  
- Open Library API (no key)  
- NOVI backend (no key)  

To use a different backend, update:  
`authContext.jsx`

---

##  Installation

1. Install Node.js + npm  
2. Clone the repo:
git clone https://github.com/lauren-haan-gilbert/vibo.git

or:
git@github.com:lauren-haan-gilbert/vibo.git

3. Install dependencies:
npm install
4. (Optional) Update npm:
npm install -g npm@latest

---

##  Getting Started

### Commands

#### Start development server
`npm run dev`
#### Build production version
`npm run build`
#### Lint code
`npm run lint`
#### Preview production build
`npm run preview`

---

##  Test Account

You may create your own, or use:
```
username: ViboTest
password: ViboTest1234!
```
---

## ❤️ Acknowledgements
- NOVI Hogeschool  
- Open Library API  
- Adobe XD  
- Early testers  
