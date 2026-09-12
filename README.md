# Spicello 🌶️

Spicello is an e-commerce website for organic spices, built with plain HTML, CSS and JavaScript (no framework this time). You can browse spices, add them to a cart, login/signup, checkout, and track your order.

I built this project to practice core JavaScript - working directly with the DOM, forms, and localStorage, without relying on a framework to handle everything for me.

🔗 **Live Demo:** [spicello.vercel.app](https://spicello.vercel.app/)

## What you can do on this site

- Browse all spice products with a search bar (shows suggestions as you type)
- Click on a product to see full details, price, benefits, and related products
- Add products to cart, change quantity, apply a promo code (try SPICE10)
- Login or create an account
- Checkout with a delivery address and choose a payment method
- Track your order status after placing it

## Tech I used

- HTML, CSS, JavaScript (vanilla, no framework)
- Bootstrap for the layout and components
- localStorage to save cart, user accounts and order history, since there's no backend/database in this project

## Why I built this

This is a frontend-only project, so there's no real backend or database. I used localStorage to simulate one - it's enough to show how the features work, but obviously a real store would need a proper backend and secure payment handling.

I built this alongside my other project (CineNo, which is React-based) to also show that I understand the fundamentals of JavaScript without a framework doing the work for me.

## Things I'd improve with more time

- Right now product info exists both in a JS data file and hardcoded in the HTML - would rather generate everything from one source
- Login/signup and the "forgot password" flow are simplified for a demo - no real email verification
- Would like to move to a real backend at some point for actual security

## Note

I used AI tools (Antigravity) to help build this faster, but I made the decisions on features and structure, and I understand and can explain how the code works.

## Run it locally

Just open `index.html` in your browser, or run it with a live server extension in VS Code.
