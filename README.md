# Stock Trading App

This repository contains a full-stack stock trading application with three main components:
- **backend**: Node.js/Express API server
- **dashboard**: React-based dashboard for trading and analytics
- **frontend**: Landing page and marketing site (React)

---

## Prerequisites
- Node.js (v16 or above recommended)
- npm (comes with Node.js)

---

## 1. Clone the Repository
```bash
git clone <repo-url>
cd "Stock Trading App"
```

---

## 2. Install Dependencies

### Backend
```bash
cd backend
npm install
```

### Dashboard
```bash
cd ../dashboard
npm install
```

### Frontend
```bash
cd ../frontend
npm install
```

---

## 3. Environment Variables

Set up environment variables as needed for each part (e.g., database connection, secret keys). Create a `.env` file in each folder if required. Example for backend:

```
MONGO_URI=your_mongodb_connection_string
```

---

## 4. Running the Applications

### Start Backend Server
```bash
cd backend
npm start
```

### Start Dashboard (React App)
```bash
cd dashboard
npm start
```

### Start Frontend (Landing Page)
```bash
cd frontend
npm start
```

---

## 5. Folder Structure

- `backend/` - Express API, models, controllers, routes, schemas, and utilities
- `dashboard/` - React dashboard for users to trade and view analytics
- `frontend/` - React landing page and marketing site

---

## 6. Testing

- Place your tests in the `test/` directory inside each project (if applicable).
- Run tests using:
  ```bash
  npm test
  ```
  (from the respective folder)

---

## 7. Additional Notes
- Make sure MongoDB is running if using a local database.
- Update API endpoints in the dashboard/frontend as needed to match your backend server URL.
- For production, build the React apps using `npm run build` and serve them with a static server or integrate with the backend.

---

## 8. Contact
For any issues, please open an issue in this repository.
