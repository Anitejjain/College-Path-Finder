# Collge Path Finder

College PathFinder is a comprehensive educational search and recommendation platform designed to assist students in finding suitable college programs based on a wide range of criteria. The platform enhances the user experience and streamlines the college selection process by allowing users to set a specific All India Rank (AIR) range. This feature helps students narrow down their options based on academic performance, ensuring they are presented with colleges that align with their ranking.

Objectives and Benefits:
* Rank-based Selection: Users can choose between available college options based on their rank.
* Program Comparison: Allows students to compare two programs based on their rankings.
* Program Search and Reviews: Users can search for specific programs and view their reviews.
* Latest Updates: Keeps users updated with the latest happenings related to college admissions and entrance exams.
* Discussion Forum: Enables direct communication between users and students studying on campuses.

## Codebase Navigation

### FrontEnd

The Front-end codebase is structured as follows: the "src" directory houses all React source code files, while the "public" directory contains assets and files that are directly rendered within the web browser interface. The client directory serves as the root directory encompassing all frontend development components and assets within the project structure.

### BackEnd

The backend codebase resides within the "/server" directory. It comprises various individual units, each housed within their respective folders. The "index.js" unit serves as the integration point for combining these units into a cohesive whole. The "models" directory encapsulates database schemas, while the "routes" directory hosts controllers responsible for managing interface logic transitions. Authorization functionalities are implemented within the "middleware" directory.

#### Organization of Backend Components

Below is the organization of the backend components within the server directory:

/server
├── index.js
├── models
│ └── (database schemas)
├── routes
│ └── (controllers)
└── middleware
└── (authorization functionalities)


## Deployment

We have deployed our website on the web. Please click the link below to visit the deployed website:

[Visit our Website](https://college-frontend-vert.vercel.app/)

---

## Local Installation Requirements

To host the website on a local system, ensure you have the following installed:

1. Web Browser
2. Node.js
3. npm
4. express
5. mongoose
6. MERN stack
7. react
8. bcrypt

---

## Installation Steps

### Frontend (Website)

1. Navigate to the "/client" directory.
2. Open the Command Line Terminal in this folder.
3. Run the following commands one by one:

* npm install --force
* npm start


The webpage will automatically open in `localhost:3000`. If it doesn't open automatically, you can open it manually in your web browser.

### Backend

1. Navigate to the "/server" directory.
2. Open the Command Line Terminal in this folder.
3. Run the following commands one by one:

* npm install --force
* npm start

If there is an error after running `npm start`, try running:

* npm uninstall bcrypt
* npm install bcrypt


