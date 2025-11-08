# System Architecture - Chop Rush

## Overview
Chop Rush uses a three-tier architecture:
1. **Frontend** – The mobile app interface users interact with.
2. **Backend** – The server that handles orders, payments, and meal listings.
3. **Database** – Stores user profiles, vendor menus, and order history.

## Frontend
- Built with **React Native** for cross-platform use.
- Communicates with the backend using REST APIs.
- Displays real-time meal availability and order status.

## Backend
- Built using **Node.js** and **Express**.
- Handles authentication, payments, and meal listings.
- Sends push notifications for new meal availability.

## Database
- **MongoDB** for flexible storage of user and vendor data.
- Includes collections for:
  - Users
  - Vendors
  - Meals
  - Orders
  - Payments

## Communication Between Components
1. User opens the app (frontend) → requests meal data via API.
2. Backend processes the request → fetches from MongoDB.
3. Data sent back → frontend displays meals available.
4. On order, backend updates the order status → rider gets notified.

## Why This Architecture is Feasible
- Scalable: Each layer (frontend, backend, database) can grow independently.
- Reliable: Using cloud-based hosting ensures uptime.
- Fast: REST API design supports real-time data.
