# BooRoad — Travel Management WebApp
[![Live Demo](https://img.shields.io/badge/live-demo-brightgreen)](https://booroad-project.netlify.app/)


## Project Overview
BooRoad is a lightweight web application designed for a travel agency to help trip leaders manage journeys and guests. The app lets leaders consult available trips, add and manage individual travelers with their personal information, receive automatic warnings when a trip reaches the maximum capacity (15 guests), and contact guests easily when needed.

This project was developed as a group exercise focused on soft skills: fast project planning, collaborative development, and creating a clear final pitch for instructors acting as clients.

## Key Features
- Browse available trips with basic trip details (dates, destination, capacity).
- Add travelers to a specific trip with personal information (name, contact details, notes).
- Enforce maximum of 15 guests per trip; the app warns and prevents adding beyond this limit.
- Quick-contact features to reach out to travelers (e.g., email link / phone link).
- Simple passenger list view per trip, with quick edit/delete actions.
- Basic validation for traveler data (required fields, contact format).
- Admin/leader view to manage trips and guests (no complex roles in this exercise).

## Tech Stack
  - React 19.0.0
  - Vite 6.2.0
  - React Router DOM 7 (for routing and navigation)
  - React Select 5 (for dropdowns and select inputs)
  - Netlify (for client side deployment)

## How to Run Locally
1. Clone the repository.
2. Install dependencies using `npm install`
3. Start the development server using `npm run dev`
4. Open the application in your browser at the URL provided by Vite.

## Team
This project was implemented as a collaborative group assignment:
- [Willy Mariino](https://github.com/willymariino)
- [Angela Ferraro](https://github.com/AngelaFerraro18)
- [Alessandro Malagni](https://github.com/alemalagni)
- [Michele Didonna](https://github.com/micheledidonna01)

## Live Demo
[BooRoad](https://booroad-project.netlify.app/)

## Project Context: Soft-Skills Exercise
The primary goal of this project was to practice collaborative development and soft skills, rather than advanced technical complexity.
- Rapid team coordination to produce a working prototype in a short timeframe.
- Clear role distribution and time-boxed feature delivery.
- Preparing a concise and persuasive project presentation (final pitch) for instructors acting as clients.
- Explaining the app’s structure, features, and a roadmap of future releases during the pitch.

During the pitch we explained:
- The system architecture and data flow
- Key user journeys (how a trip leader adds guests and contacts them)
- Validation and capacity enforcement (15-guest limit)
- Planned improvements and release priorities

