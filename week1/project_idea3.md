# 🍽️ Capstone Project Idea: LBI Eats

## 📝 Description
**LBI Eats** is a location-specific restaurant review platform for Long Beach Island, NJ. It helps users explore local dining options, read/write reviews, compare pricing, browse menus, and plan their meals around real user experiences.

---

## 🛠 Tech Stack

- **Frontend**: React + TypeScript + Tailwind CSS or Chakra UI
- **Backend**: Node.js + Express + GraphQL (Apollo Server)
- **Database**: MongoDB with Mongoose
- **Authentication**: JWT-based user login
- **Hosting**: Netlify (Frontend), Render (Backend)
- **Map Integration**: Google Maps API or Leaflet.js
- **Bonus (Stretch)**: Yelp API or OpenTable integration

---

## 🧱 System Architecture

- Frontend SPA that consumes a GraphQL API
- MongoDB stores restaurants, user reviews, and user accounts
- Maps API for showing restaurants by location
- Cloudinary or Firebase for optional photo uploads

---

## ⚙️ System Design

### 📂 Key Models

- **Restaurant**: name, address, type (seafood, Italian, diner, etc.), hours, price range, tags (BYOB, waterfront, takeout, etc.), photos
- **Review**: user, restaurant, rating, comment, date
- **User**: name, email, password, reviews

---

## 👤 User Stories

1. As a user, I can browse all restaurants on LBI.
2. As a user, I can filter by cuisine, price, or tag (e.g., "BYOB").
3. As a user, I can view each restaurant’s profile with reviews, photos, and menus.
4. As a user, I can leave my own review and star rating.
5. As a user, I can bookmark restaurants I want to try.
6. As an admin, I can add or update restaurant listings.

---

## 🎨 Mockup Plan

- **Homepage**
  - Welcome header
  - Search bar: “Find a spot on LBI”
  - Filter dropdowns: Cuisine, Price, Features (BYOB, kid-friendly, etc.)
  - Map view toggle

- **Restaurant Profile Page**
  - Name, image carousel
  - Description, address, hours
  - Reviews section
  - Review form

- **Dashboard (Optional)**
  - My reviews
  - Saved restaurants

---

## 🚀 Future Stretch Goals

- Reservation system or OpenTable integration
- “Now open” indicator (based on hours + current time)
- Wait time tracking (submitted by users)
- Beach proximity filter (“near Beach Haven”, etc.)
- Daily specials or user-submitted menu pics
