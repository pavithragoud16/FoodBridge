# FoodBridge — Smart Food Waste Management & Redistribution Platform

Responsive frontend project built with HTML, CSS and vanilla JavaScript.

## Six separate pages
1. `index.html` — Home
2. `available-food.html` — Available Food
3. `donate-food.html` — Donate Food
4. `dashboard.html` — Impact Dashboard
5. `login.html` — Login
6. `register.html` — Registration

## Run in VS Code
1. Extract the ZIP and open the folder in VS Code.
2. Install/enable the Live Server extension.
3. Right-click `index.html` and choose **Open with Live Server**.

## Features
- Responsive navigation and layout
- Search/filter food listings
- Donation form with browser validation
- Donations and pickup requests saved in browser `localStorage`
- Dashboard counts update from browser activity
- Separate login and registration forms with frontend validation

## Important limitations
This is a frontend prototype. Browser `localStorage` data is not shared with other users. Login and registration do not create real accounts or authenticate users; passwords are not sent or saved by this demo. Dashboard impact estimates and built-in listings are sample data. For a real multi-user service, add a backend API, shared database, secure password hashing/session management, server-side validation, and appropriate privacy/security controls. Verify food safety and local donation requirements before real-world use.

## Deploy the frontend
You can deploy this static site with Netlify Drop at https://app.netlify.com/drop. Extract the ZIP and upload the project folder as the Netlify interface allows. The public deployment remains frontend-only until a backend is added.
