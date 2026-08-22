# Final Application Walkthrough

[← Back to the main README](../README.md)

This page presents the finished **Minimise Food Waste** application using the clean screenshots taken from the project's final Sprint 4 documentation.

## User journey

**Sign in → browse available food → receive recommendations → share surplus food → message users → track profile activity**

---

## 1. Login

<p align="center">
  <a href="screenshots/final-app/login.jpg">
    <img src="screenshots/final-app/login.jpg" alt="Login screen" width="420">
  </a>
</p>

The login screen provides email and password entry together with a **remember me** option for returning users.

---

## 2. Home page

<p align="center">
  <a href="screenshots/final-app/home.jpg">
    <img src="screenshots/final-app/home.jpg" alt="Home page" width="720">
  </a>
</p>

The home page introduces the platform's food-waste reduction goal and gives users quick access to the main sharing and recommendation workflows.

---

## 3. Browse available food

<p align="center">
  <a href="screenshots/final-app/browse-available-food.jpg">
    <img src="screenshots/final-app/browse-available-food.jpg" alt="Browse available food" width="720">
  </a>
</p>

Available food is displayed in a card-based layout so users can review individual items, categories and dietary information before opening a listing.

---

## 4. Personalised recommendations

<p align="center">
  <a href="screenshots/final-app/recommendations.jpg">
    <img src="screenshots/final-app/recommendations.jpg" alt="Personalised recommendations" width="760">
  </a>
</p>

The recommendations view presents suggested food matches and filtering controls intended to make relevant listings easier to discover.

---

## 5. Smart matchmaking

<p align="center">
  <a href="screenshots/final-app/smart-matchmaking.jpg">
    <img src="screenshots/final-app/smart-matchmaking.jpg" alt="Smart matchmaking" width="720">
  </a>
</p>

The smart matchmaking screen explains the project's preference-oriented matching concept and shows suggested food matches for the user.

---

## 6. User profile

<p align="center">
  <a href="screenshots/final-app/user-profile.jpg">
    <img src="screenshots/final-app/user-profile.jpg" alt="User profile" width="720">
  </a>
</p>

The profile view brings together account information, items shared and received, ratings, impact information and rewards-related activity.

---

## 7. Messaging

<p align="center">
  <a href="screenshots/final-app/messaging.jpg">
    <img src="screenshots/final-app/messaging.jpg" alt="Messaging page" width="720">
  </a>
</p>

Messaging gives users a dedicated place to manage conversations and coordinate collection of shared food.

---

## 8. Tag food / create listing

<p align="center">
  <a href="screenshots/final-app/tag-food.jpg">
    <img src="screenshots/final-app/tag-food.jpg" alt="Tag food form" width="480">
  </a>
</p>

The listing workflow allows a user to enter information such as the food name, category and sub-category, with additional steps for details, photos and location.

---

## Feature summary

| Feature | User value |
| --- | --- |
| **Food listings** | Share surplus food with useful item information |
| **Browse experience** | Discover available food more quickly |
| **Recommendations** | Surface more relevant listings |
| **Smart matchmaking** | Support better donor/recipient matches |
| **Messaging** | Coordinate collection directly |
| **User profile** | Track participation and food-sharing impact |
| **Rewards** | Encourage continued engagement |
| **Location support** | Help connect food-sharing activity to nearby users/items |

---

## Technical implementation

The final product is supported by a **Node.js / Express** application with server-rendered **Pug** views and separate service modules for recommendations, messaging, location behaviour, user points and database access.

For the engineering view of the project, return to the **[main README](../README.md)** or read the **[architecture notes](ARCHITECTURE.md)**.
