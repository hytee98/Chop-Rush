# CHOP RUSH

## What the product does
Chop Rush is a food delivery/hyper local app that connects users or customers  with meals already being prepared nearby. 
Instead of waiting for restaurants to start preparing food after an order, users can instantly order from a list vof ready to go meals.
Traditional delivery wait until an order is placed to start cooking, Chop rush lists ready or nearly ready dishes
from local vendors, reducing wait times, lowering waste, and increasing vendor revenue.

## Problem
Busy people face long delivery waits and decision fatigue; local vendors often have surplus prepared food with low visibility.

## Solution
By showing "ready now" meals and short ETA options, Chop rush connects customer who wants fopod fast with vendors who have meals ready to go turning overlooked opportunities into immediate orders. 

## Who it is for
- Busy professionals who wants fast meals 
- Food vendors looking to reduce waste and increase sales
- Riders who want more frequent deliveries and tips.
  
## Main key Features:
- Real time list of meals already prepared nearby.
- Smart recommendation based on past orders
- In-app order tracking and secure payment
- Vendor dashboard for meal upload and analytyics
- Rider delivery tracker and earning summary

The Chop Rush system is built using a three-tier architecture consisting of the frontend, backend, and database layers.

1. **Frontend:** 
   - Built with React for web and Flutter for mobile apps.
   - Provides interfaces for customers, restaurants, and delivery riders to interact with the system.
2. **Backend:** 
   - Developed using Node.js 
   - Handles authentication, order management, payment processing, and communication between users, restaurants, and riders through RESTful APIs.
3. **Database:**
   - MYSQL stores user data, menus, restaurant information, and order details.
4. **Paypal Payment:**
   - Integrated with Paypal for securing online payment.

**Communication Flow:**
- Customers place orders through the frontend.
- The backend processes the order and stores details in the database.
- Restaurants receive order notifications.
- Once food is ready, a rider is assigned.
- After delivery, order status is updated and visible to the customer
