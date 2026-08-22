# Final Application Walkthrough

[← Back to the main README](../README.md)

This page gives a simple overview of the completed **Minimise Food Waste** application from the Sprint 4 project.

## User journey

**Sign in → browse available food → receive recommendations → share surplus food → message other users**

---

## 1. Sign in

<p align="center">
  <a href="screenshots/final-app/login.jpg">
    <img src="screenshots/final-app/login.jpg" alt="Minimise Food Waste login screen" width="430">
  </a>
</p>

Users can enter their email and password and choose **remember me** before accessing the platform.

---

## 2. Home page

<p align="center">
  <a href="screenshots/final-app/home.jpg">
    <img src="screenshots/final-app/home.jpg" alt="Minimise Food Waste home page" width="620">
  </a>
</p>

The landing page explains the food-waste reduction goal and provides quick access to the platform's main features.

> Click either screenshot to open the original image.

---

## 3. Discover and share food

| Feature | What the user can do |
| --- | --- |
| **Browse food** | View available food listings and useful item information |
| **Recommendations** | See suggested listings based on preferences and activity |
| **Smart matchmaking** | Find more suitable donor/recipient matches |
| **Share food** | Create a structured listing for surplus food |
| **Location support** | Use location-aware behaviour as part of discovery and collection |

The original Sprint 4 evidence images are retained in [`screenshots/final-app/`](screenshots/final-app/) for reference.

---

## 4. Community features

| Feature | Purpose |
| --- | --- |
| **Messaging** | Coordinate food collection with other users |
| **User profile** | View account information and food-sharing activity |
| **Points and rewards** | Track engagement and food-sharing impact |
| **About page** | Explain the food-waste problem and platform purpose |

---

## Technical implementation

The product is supported by a **Node.js / Express** application with server-rendered **Pug** views and separate service modules for recommendations, messaging, location behaviour, user points and database access.

For the engineering view of the project, return to the **[main README](../README.md)** or read the **[architecture notes](ARCHITECTURE.md)**.
