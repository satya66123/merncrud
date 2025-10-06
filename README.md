# merncrud
# 🧠 MERN CRUD Application

A simple **MERN Stack (MongoDB, Express, React, Node.js)** application that performs **CRUD (Create, Read, Update, Delete)** operations with a clean UI and tabular data display.

---

## 🚀 Features

- Create, Read, Update, and Delete user records
- Email field is **unique** (no duplicate emails)
- Responsive table layout
- Error handling for duplicate email
- RESTful API backend using Express and MongoDB

---

## 🧩 Technologies Used

| Stack | Technology |
|--------|-------------|
| **Frontend** | React (Create React App), Axios |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB / Mongoose |
| **Styling** | Inline CSS (can be extended with Bootstrap or Tailwind) |

---

## 📁 Folder Structure

mern-crud/
│
├── backend/
│ ├── server.js
│ ├── package.json
│ └── .env
│
├── frontend/
│ ├── src/
│ │ ├── App.js
│ │ └── index.js
│ ├── package.json
│ └── public/
│
└── README.md

yaml
Copy code

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/mern-crud.git
cd mern-crud
2️⃣ Setup Backend
bash
Copy code
cd backend
npm install
Create .env file inside backend/:

ini
Copy code
MONGO_URI=mongodb://127.0.0.1:27017/merncrud
PORT=5000
Then start the backend:

bash
Copy code
node server.js
or (for auto restart)

bash
Copy code
npm install -g nodemon
nodemon server.js
3️⃣ Setup Frontend
bash
Copy code
cd ../frontend
npm install
npm start
Frontend runs on 👉 http://localhost:3000
Backend runs on 👉 http://localhost:5000

🧠 API Endpoints
Method	Endpoint	Description
GET	/items	Fetch all records
POST	/items	Create a new record
PUT	/items/:id	Update record by ID
DELETE	/items/:id	Delete record by ID

💻 Usage
Open the app in your browser at http://localhost:3000

Add a user with name and unique email

View records in a table

Use Edit or Delete buttons to manage records

Duplicate emails will show an error message in red

📸 Screenshot (Example)
sql
Copy code
| No | Name       | Email              | Actions           |
|----|-------------|--------------------|-------------------|
| 1  | John Doe    | john@example.com   | [Edit] [Delete]   |
| 2  | Jane Smith  | jane@example.com   | [Edit] [Delete]   |
🧱 Future Improvements
Add Toast Notifications for success/error messages

Integrate Bootstrap or Tailwind for better UI

Connect to MongoDB Atlas for cloud database

Add pagination & search functionality

👨‍💻 Author
Your Name
📧 SatyaSrinath
🌐 GitHub: satya66123

🪪 License
This project is licensed under the MIT License — you’re free to use, modify, and distribute it.

yaml
Copy code

---

Would you like me to make a **customized version with your actual GitHub username and project name** (so you can copy-paste and push directly)?







