# 🤝 FriendlyDev Frontend

A modern developer social network application built with **React** and **TypeScript**. This repository contains the client-side interface, which is fully integrated with a custom-built headless CMS.

> **Note:** This is the frontend repository. The backend code (Strapi & PostgreSQL) can be found here: [friendly-dev-backend](https://github.com/elenista/friendly-dev-backend)

## 🏗️ Architecture & Integration

This frontend is part of a decoupled Full-Stack ecosystem:
* **Backend:** Powered by [Strapi Headless CMS](https://strapi.io/), providing a robust RESTful API.
* **Database:** Data is persisted in a [Neon Serverless PostgreSQL](https://neon.tech/) database.
* **Integration:** Seamless communication between React and Strapi, handling dynamic content delivery and API synchronization.

## 🚀 Current Features (In Progress)

* **UI Foundation:** Implementation of core components like Navigation, Hero sections, and Profile layouts.
* **Dynamic Content:** Real-time rendering of developer profiles and posts fetched directly from the Strapi API.
* **Responsive Design:** Mobile-first, professional interface tailored for the developer community.
* **TypeScript Integration:** Strict typing for API responses, props, and component states.

## 🛠️ Tech Stack
* **Framework:** React 18
* **Language:** TypeScript
* **Routing:** React Router DOM
* **API Communication:** REST API with JSON data exchange

## 📈 Roadmap
- [ ] Implement User Authentication (Strapi JWT integration)
- [ ] Add Global State Management (Redux/Context API)
- [ ] Create User Dashboard for profile management
- [ ] Implement Post, Comment, and Like functionality

---

### 🎓 Acknowledgments
This project is being developed as part of the **"Modern React from the Beginning"** course by **Brad Traversy** on **Udemy**.
