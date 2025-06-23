# 🚘 Capstone Project Idea: WashWise

## 📝 Description
WashWise is a car wash review and comparison platform that helps users find the best local car washes based on price, quality, and services. Users can view detailed listings, read/write reviews, compare prices, and explore service types before visiting.

---

## 🛠 Tech Stack

- **Frontend**: React + TypeScript, Tailwind CSS
- **Backend**: Node.js + Express + GraphQL (Apollo Server)
- **Database**: MongoDB with Mongoose
- **Authentication**: JWT for secure user accounts
- **Hosting**: Netlify (Frontend), Render (Backend)
- **Maps API**: Google Maps or Leaflet for location visualization

---

## 🧱 System Architecture

- GraphQL API serving frontend with queries/mutations
- MongoDB stores user accounts, car wash listings, reviews
- React SPA with dynamic routing and data fetching
- Geolocation for “Find Near Me” functionality

---

## ⚙️ System Design

### 📂 Data Models
- **User**: username, email, password, list of reviews
- **CarWash**: name, location, pricing, services, hours, rating
- **Review**: user, car wash, rating (1–5), text, images

---

### 🧍 User Stories

1. As a user, I can search for car washes near me by zip code or city.
2. As a user, I can view each car wash’s service offerings and pricing.
3. As a user, I can leave detailed reviews with star ratings and comments.
4. As a user, I can filter listings by price, rating, or service type.
5. As a user, I can bookmark favorite locations or write multiple reviews.
6. As an admin, I can add or edit car wash listings in the database.

---

### 🎨 Mockup Plan (Frontend Views)

- **Homepage**:
  - Search bar: "Search by zip, city, or near me"
  - Featured car washes (high rating / trending)
- **Car Wash Profile Page**:
  - Map + images
  - Price breakdown
  - Services list (e.g. exterior, full detail, wax)
  - User reviews section
- **Review Form**:
  - Star rating
  - Text field + optional image
- **Optional Dashboard**:
  - User bookmarks
  - Review history
  - Admin panel

---

## 🚀 Future Stretch Goals

- Appointment scheduling + SMS reminders
- Loyalty rewards system or digital punch card
- Wait time tracking submitted by users
- Promotions or coupon codes from listed businesses
