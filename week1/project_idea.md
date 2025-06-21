# 🎬 Capstone Project Idea: MovieHouse Reviews

## 📝 Description
A movie theater review platform where users can rate and review local theaters — not just movies. It highlights key features like pricing, seating types, discount nights, food options, and more.

## 🛠 Tech Stack
- **Frontend**: React + TypeScript, Tailwind or Chakra UI
- **Backend**: Node.js + Express + GraphQL (Apollo Server)
- **Database**: MongoDB with Mongoose
- **Authentication**: JWT-based login/signup
- **Hosting**: Netlify (Frontend) + Render (Backend) + MongoDB Atlas

## 🧱 Architecture
- **API-first design** with GraphQL endpoints
- **Mongoose models** for Theaters, Reviews, Users
- **Frontend routing** via React Router
- Responsive design for mobile and desktop

## ⚙️ System Design
- Users can search theaters by name or location
- Each theater has a detailed profile with:
  - Film types (indie, mainstream, foreign, repertory, etc.)
  - Pricing breakdown (general admission, matinee, kids/seniors)
  - Discount nights or loyalty programs
  - Special screenings (e.g., 70mm, Q&As, retro nights)
  - Concessions menu
  - Kitchen/dine-in status
  - Seating type (standard, recliners, reserved, couches)

## 👤 User Stories
1. As a user, I can register and log in to leave reviews.
2. As a user, I can search for theaters near me or by name.
3. As a user, I can view detailed profiles of theaters.
4. As a user, I can submit reviews and rate amenities.
5. As a user, I can filter theaters based on dining, pricing, or screening types.
6. As an admin, I can add new theaters and update information.

## 🎨 Client-Side Mockup Plan
- **Home page**: Search bar, featured theaters, map preview
- **Theater profile**: Carousel of photos, amenities table, reviews section
- **Review form**: Star ratings + text + optional photo upload
- **Dashboard (optional)**: Personalized bookmarks or review history

