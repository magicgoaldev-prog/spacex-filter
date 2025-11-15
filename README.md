# SpaceX API - COMP3133 Lab Test 2

## 📌 Project Overview
This is an Angular project developed as part of **COMP3133 Lab Test 2**. The application fetches and displays a list of past SpaceX missions using the SpaceX API.

## 🛠️ Tech Stack
- **Frontend:** Angular
- **Backend API:** SpaceX API (https://api.spacexdata.com/v3/launches)
- **HTTP Client:** Angular `HttpClient`
- **UI Components:** Custom Angular components


## 🚀 Features
- Fetches SpaceX mission data from the API
- Displays mission details in a structured format
- Uses Angular components for modular design

## 🔧 Setup & Installation
### 1️⃣ Install Dependencies
Run the following command to install the required dependencies:
```sh
npm install
```

### 2️⃣ Run the Development Server
Start the Angular development server with:
```sh
ng serve
```
Then, open **http://localhost:4200/** in your browser.

### 3️⃣ Verify Component Integration
Ensure `app-missionlist` is correctly recognized by checking:
- `missionlist.component.ts` has `selector: 'app-missionlist'`
- `app.module.ts` declares `MissionlistComponent`
- `app.component.html` includes `<app-missionlist></app-missionlist>`

## 📝 Author
**MagicGoal Dev**  
**Student ID:** 101418595  
**Course:** Advanced Diploma in Computer Programming and Analysis, George Brown College