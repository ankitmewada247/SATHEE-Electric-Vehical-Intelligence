
## ⚡SΛTHEE 
SATHEE : Smart AI-powered Transportation & High-efficiency EV Ecosystem
 “Predict. Optimize. Charge. Power the Future.”

 ## Project Banner
<img width="1672" height="941" alt="ChatGPT Image Sep 5, 2026, 11_24_02 PM" src="https://github.com/user-attachments/assets/e9cd59f7-b387-4c73-b4a4-f13e7b2b06f7" />


 ## Sathee Video
https://drive.google.com/file/d/1FTM3-2o3ria9Oid7g-AW96baQeMGevsr/view?usp=drivesdk


# 🚀 About SΛTHEE
**SΛTHEE** is an AI + GIS powered EV charging and grid intelligence platform designed for the growing Electric Vehicle ecosystem in India.
The platform provides two major experiences:
### 🚗 EV Users
Users can:
- Find nearby EV charging stations
- Check charger availability
- Check connector compatibility
- Compare charging options
- Book charging slots
- Receive AI-based charging-time recommendations
- View booking details and QR codes
- Simulate charging sessions
- Track charging history
- Save preferred stations

-----
### ⚡ Grid & Utility Operators
Operators can:

- Monitor EV charging demand
- Forecast future demand
- Identify geographical demand hotspots
- Analyze station utilization
- Monitor transformer utilization
- Identify grid-stress zones
- Optimize charging schedules
- Perform what-if simulations
- Analyze potential charging-station locations
------------------------------------------------
  # 🎯 Problem Statement

The rapid adoption of EVs is increasing the demand for charging infrastructure.

Uncoordinated EV charging can result in:

- Peak electricity demand
- Transformer overloading
- Increased waiting time
- Uneven charging-station utilization
- Higher charging costs during peak periods
- Poor placement of new charging stations
- Additional stress on local distribution networks

Traditional charging systems primarily focus on **where to charge**.

SΛTHEE focuses on:

> **Where to charge + When to charge + How to optimize charging demand + Where to build the next station.**

---

---

# 🎯 Objectives

SΛTHEE aims to:

1. Simplify EV charging-station discovery.
2. Provide charger compatibility information.
3. Enable charging-slot booking.
4. Recommend suitable charging times.
5. Reduce unnecessary peak charging demand.
6. Forecast EV charging demand.
7. Identify EV demand hotspots.
8. Analyze transformer utilization.
9. Optimize charging schedules.
10. Support charging-station site selection.
11. Provide grid and utility analytics.
12. Create a scalable India-wide EV intelligence platform.

---

# 🚗 EV User Features

## 🔐 Registration & Login

Users can create an account using:

- Full name
- Mobile number
- Email
- Password
- Confirm password

The platform can support:

- Mobile OTP verification
- Email OTP verification
- Login using email/mobile
- Password reset
- Profile management

> Development/demo OTPs should be clearly identified as demo functionality unless a real provider is configured.

---


---

## 🚘 Vehicle Management

Users can add their EV details:

- Vehicle type
- Vehicle number
- Brand
- Model
- Battery capacity
- Connector type

Supported vehicle categories can include:

```text
Car
Bike
Bus
Commercial Vehicle
```

---

## 🗺️ Find a Charging Station

Users can search for charging stations across India.

Search options include:

- State
- City
- Area
- Station name
- Current location

The map can display:

🟢 Available  
🟡 Limited availability  
🔴 Occupied

---


## 🔎 Charging Filters

Users can filter stations based on:

- Distance
- Price
- Charging speed
- Connector
- Availability
- Vehicle type

---

## ⚡ Charger Types

SΛTHEE can support charger categories such as:

```text
AC
Slow
Fast
DC Fast
Ultra Fast
```

Example connector types:

```text
CCS2
Type 2
CHAdeMO
Bharat AC
Bharat DC
```

---


## 👉🏻 Quick Start

## 🚀 INSTALLATION
## 1. Clone the repository
git clone https://github.com/ankitmewada247/SATHEE
## 2. Enter the project directory
cd sathee
## 3. Install frontend dependencies
cd frontend
npm install
## 4. Start frontend
npm run dev
Backend Setup
## Open another terminal:
cd backend
npm install

## Start the backend:
npm run dev
or:
npm start



## 🤖 AI CHARGING RECOMMENDATION
```SATHEE recommends suitable charging times based on factors such as:

Grid load
Station utilization
Transformer utilization
Expected waiting time
Electricity tariff
Charging demand
```
## Example
#### 7:00 PM → High Grid Load 🔴
### 10:00 PM → Lower Grid Load 🟢

## 🛠️ TECHNOLOGY STACK
```
. Frontend
. React
. TypeScript
. HTML
. CSS
. Tailwind CSS
. React Router
. Lucide Icons
. Recharts
```
## Maps
. Leaflet
. React Leaflet
. OpenStreetMap

## Backend
```
. Node.js
. Express.js
```
## Database
```
.PostgreSQL / SQLite
```
## AI & ML
```
. Python
. XGBoost
. LSTM
. Prophet
. K-Means
. DBSCAN
```
## Optimization
```
. MILP
. Genetic Algorithm
. Reinforcement Learning
```
## Version Control
```
. Git
. GitHub
```

## 📁 PROJECT STRUCTURE
```text
SATHEE/
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── data/
│   │   ├── services/
│   │   ├── App.tsx
│   │   └── main.tsx
│   │
│   ├── public/
│   ├── package.json
│   └── vite.config.ts
│
├── backend/
│   ├── src/
│   │   ├── routes/
│   │   ├── controllers/
│   │   ├── models/
│   │   └── server.js
│   │
│   └── package.json
│
├── README.md
├── .gitignore
└── .env.example
```
## 🔄 SYSTEM WORKFLOW
EV Users
Charging Stations
Traffic
Weather
EV Registration Data
Charging Sessions
Grid / Utility Data
```text
   GIS Data
        │
        ▼
   Data Ingestion
        │
        ▼
 Data Preprocessing
        │
        ▼
 Timestamp Synchronization
        │
        ▼
    GPS Validation
        │
        ▼
    GIS Mapping
        │
        ▼
 Feature Engineering
        │
        ▼
 AI Demand Forecasting
        │
        ▼
 Spatial Clustering
        │
        ▼
 Smart Charging Optimization
        │
        ▼
 Grid Capacity Analysis
        │
        ▼
 Station Site Selection
        │
        ▼
 SATHEE Decision Support

```





## 🏗️ SYSTEM ARCHITECTURE


                    SATHEE
                       │
          ┌────────────┴────────────┐
          │                         │
      EV USER                 GRID / UTILITY
          │                         │
          ▼                         ▼
    Web Application           Intelligence Dashboard
          │                         │
          └────────────┬────────────┘
                       │
                       ▼
                  Backend API
                       │
                       ▼
                AI / ML Engine
                       │
          ┌────────────┼────────────┐
          │            │            │
       Forecasting  Clustering  Optimization
          │            │            │
          └────────────┼────────────┘
                       │
                       ▼
                    GIS
                       │
                       ▼
                   Database
```

```

## 🗃️ DATA USED
```
SATHEE can work with datasets such as:

EV registrations
Charging station information
Charging sessions
Traffic data
Weather data
Electricity demand
Transformer capacity
Feeder load
Geographic information
Station utilization

```


## ⚠️ DEMO DATA DISCLAIMER
```
This project may use synthetic/demo data for demonstration and development purposes.

Demo data may include:

EV population
Charging station availability
Charging sessions
Grid load
Transformer capacity
Traffic
Weather
Land availability
Utility information

Such data should be clearly labelled:

DEMO DATA

The project does not claim that simulated data represents live grid conditions, real-time DISCOM telemetry, actual land availability, live payment processing, or actual utility tariffs.
```

## 💳 PAYMENT
````

The project can include a demo payment system for demonstrating the booking workflow.

Supported demonstration options may include:

UPI
Card
Wallet

No real card details should be stored in the application.

For production deployment, a secure payment gateway should be integrated.

```
````

## 📱 OTP VERIFICATION
```
The development version can use demo OTP verification.

The architecture can later be integrated with services such as:

Firebase Authentication
Twilio
MSG91
Other authorized SMS providers

Real SMS/email delivery should only be claimed when an actual provider is configured.

```
````

````
### 🔒 SECURITY
```
Security considerations include:

Password hashing
JWT authentication
Environment variables
Input validation
API authentication
Role-based access control
Secure payment integration
Protection of user information

````



