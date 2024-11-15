# Contact Management Application 
## [ -> Live Link Here  ](https://contact-app-xpkw.vercel.app/)
<img src="./frontend/src/images/Screenshot (60).png" alt="Contact List View">

This Contact Management Application is built using **React**, **Material-UI**, and a backend hosted on **Render**. The frontend is deployed on **Vercel**, offering seamless contact management functionalities. Users can add, view, edit, delete, search, and sort contact information with a user-friendly interface.

## Features

- Display a list of contacts with details like name, phone number, email, company, and job title.
- Add new contacts with validation for required fields and proper formats.
- Edit existing contact details with pre-filled forms.
- Delete contacts with a single click.
- Search contacts by name with real-time filtering.
- Sort contacts alphabetically by name (ascending/descending).
- Responsive UI built using Material-UI for an optimized experience across devices.

## Technologies Used

- **React**: Frontend framework for building the user interface.
- **Material-UI**: UI library for a clean and responsive design.
- **Node.js**: Runtime environment for the backend server.
- **Express.js**: Framework for handling backend APIs.
- **MongoDB**: Database for storing contact information.
- **Render**: Hosting service for the backend server.
- **Vercel**: Deployment platform for the frontend.
- **React Toastify**: For displaying notifications.

---

## Getting Started

To run the Contact Management Application locally, follow these steps:

### Backend Setup

1. Clone the repository:

   ```bash
   git clone [https://github.com/username/Contact_Management_App.git](https://github.com/Amitdahiya08/ContactApp)
   ```

2. Navigate to the backend directory:

   ```bash
   cd backend
   ```

3. Install backend dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file in the backend directory with the following contents:

   ```env
   MONGO_URI=<Your MongoDB Atlas Connection URL>
   PORT=8080
   ```

5. Start the backend server:

   ```bash
   npm start
   ```

   The backend server should now be running on `http://localhost:8080`.

### Frontend Setup

1. Navigate to the frontend directory:

   ```bash
   cd frontend
   ```

2. Install frontend dependencies:

   ```bash
   npm install
   ```

3. Start the frontend development server:

   ```bash
   npm start
   ```

   The frontend application should now be running on `http://localhost:5173`.

---

## Folder Structure

```
contact-management-app/
├── backend/                  # Backend server
│   ├── controllers/          # API controllers
│   ├── models/               # Mongoose models
│   ├── routes/               # API routes
│   ├── server.js             # Express server setup
│   └── ...
├── frontend/                 # React frontend
│   ├── public/               # Public assets
│   ├── src/
│   │   ├── components/       # React components
│   │   ├── services/         # API calls
│   │   ├── App.js            # Main application
│   │   ├── index.js          # Entry point
│   │   └── ...
│   ├── package.json
│   └── ...
├── .gitignore
├── README.md
└── ...
```

---

## API Endpoints

- **GET** `/api/contacts`: Retrieve all contacts.
- **POST** `/api/contacts`: Create a new contact.
- **PUT** `/api/contacts/:id`: Update an existing contact.
- **DELETE** `/api/contacts/:id`: Delete a contact.
- **GET** `/api/contacts/search?name=<query>`: Search for contacts by name.

---

## Deployed Application

The Contact Management Application is live and accessible here:

[Deployed Link](https://contact-app-xpkw.vercel.app/)

---


---

Feel free to explore the application and manage your contacts effortlessly!
