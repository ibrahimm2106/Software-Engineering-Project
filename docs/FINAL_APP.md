# Final Application Walkthrough

This page shows the finished **Minimise Food Waste** application as presented in the Sprint 4 project documentation. The screenshots focus on the user-facing product rather than the presentation slides around them.

[← Back to the main README](../README.md)

## User journey

The main flow of the application is:

**Sign in → discover available food → receive personalised recommendations → share food → interact with the community**

---

## 1. Login

![Login screen](https://raw.githubusercontent.com/ibrahimm2106/Software-Engineering-Project/Master/docs/screenshots/final-app/login.jpg)

The login screen provides email and password fields, validation and a remember-me option before users enter the main application.

---

## 2. Home page

![Home page](https://raw.githubusercontent.com/ibrahimm2106/Software-Engineering-Project/Master/docs/screenshots/final-app/home.jpg)

The home page acts as the landing point for the platform. It directs users towards sharing surplus food and discovering recommendations, while presenting the food-waste reduction purpose of the application.

---

## 3. Browse available food

![Browse available food](https://raw.githubusercontent.com/ibrahimm2106/Software-Engineering-Project/Master/docs/screenshots/final-app/browse-food.jpg)

The browsing experience presents available food listings with information intended to help users decide whether an item is suitable, including item details, quantity/location information and dietary context.

---

## 4. Personalised recommendations

![Personalised recommendations](https://raw.githubusercontent.com/ibrahimm2106/Software-Engineering-Project/Master/docs/screenshots/final-app/recommendations.jpg)

The recommendations view demonstrates the application's matchmaking concept: surfacing relevant food items based on user preferences and previous activity instead of requiring users to manually search every listing.

---

## Other completed product views

The final Sprint 4 application also included:

- **Smart matchmaking** — recommendation-oriented matching based on user preferences/activity.
- **Tag / share food** — a listing workflow for entering food name, category, quantity/quality, image and location information.
- **User profile** — account information, items shared/received, ratings and the user's food-sharing impact.
- **Messaging** — conversations between users to support coordination around food collection.
- **About page** — explanation of the food-waste problem and the purpose of the platform.

## Product goal

The application was designed around a community-sharing model: people with surplus food can make it available to others, while recipients can discover relevant items nearby. The project combines this user experience with Node.js/Express application logic, Pug templates, recommendation/location/messaging services, database integration scaffolding and Docker-based development tooling.
