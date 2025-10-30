# Ride API Dashboard

## Project Overview
This project implements a simple Ride Management API using Node.js, Express, and MongoDB, along with a front-end dashboard generated from a Postman collection using an AI tool.  

The dashboard allows users to:
- Fetch all rides
- Create a new ride
- Delete rides
- Refresh the ride list dynamically

---

## Folder Structure

ride-api/
index.js             # Backend server
package.json         # Dependencies
public/
rides-dashboard.html  # Frontend dashboard
dashboard.js          # Frontend JS
RideAPI_Collection.json   # Postman collection

---

## Installation & Running

1. **Clone the repository**
```bash
git clone <YOUR_REPO_URL>
cd ride-api

 2. Install dependencies

npm install

 3. Start the server

node index.js

 4. Open the dashboard in browser

http://localhost:3000/rides-dashboard.html

Make sure MongoDB is running locally before starting the server.

⸻

API Endpoints

Method Endpoint Description
GET /rides Fetch all rides
POST /rides Create a new ride
PATCH /rides/:id Update ride details/status
DELETE /rides/:id Delete a ride


⸻

Postman Collection
 • Exported collection file: RideAPI_Collection.json
 • Can be imported into Postman to test all API endpoints.

⸻

Dashboard Usage
 1. Create Ride: Fill in form fields and click Create Ride.
 2. Fetch Rides: Click Refresh button to load all rides.
 3. Delete Ride: Click Delete button for a ride.
 4. Table updates dynamically without page reload.

⸻


⸻

Notes
 • Ensure MongoDB is running locally at mongodb://localhost:27017.
 • CORS is enabled in the backend to allow the dashboard to interact with API.
 • Dashboard was generated from Postman JSON using an AI tool.

---
