
# 💼 Freelancer Finder

A **Freelancer Finder** web application that connects clients with freelancers based on required **skills**, **budget**, and **timeline**. It allows profile browsing, project posting, bidding, and secure communication between both parties.

🎥 https://drive.google.com/drive/folders/1_o7fKyMsaHVeMXh5BNQH8twcfwmztwk9?usp=sharing 
📦 **Download the ZIP** and run it on your local machine.



## 🛠 Tech Stack

**Frontend:**
- React.js
- Bootstrap
- Material UI
- Axios

**Backend:**
- Node.js
- Express.js
- MongoDB
- Mongoose

**Authentication:**
- JWT
- bcrypt

**Tools:**
- Postman
- MongoDB Compass
- VS Code



## ⚙️ Features

- 📝 **Project Posting & Bidding**
- 🔐 **Secure Authentication (JWT)**
- 👤 **Role-Based Dashboards (Client, Freelancer, Admin)**
- 📬 **In-App Messaging (Basic)**
- 🛡️ **Admin Moderation**



## 📦 Setup Instructions

### 🔧 Prerequisites
Make sure you have the following installed:
- Node.js
- MongoDB
- Git

### 🔌 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/freelancer-finder.git
   cd freelancer-finder


2. **Install frontend dependencies**

   ```bash
   cd client
   npm install
   ```

3. **Install backend dependencies**

   ```bash
   cd ../server
   npm install
   ```

4. **Create environment file**
   Inside the `server/` folder, create a `.env` file:

   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

### 🚀 Run Locally

```bash
# Start backend
cd server
npm start
```

```bash
# Start frontend (in a new terminal)
cd client
npm start
```

Visit the app at: [http://localhost:3000](http://localhost:3000)


## 📌 API Routes

### 🔐 Auth

* `POST /api/auth/register` – Register
* `POST /api/auth/login` – Login

### 📁 Projects

* `GET /api/projects` – View all projects
* `POST /api/projects` – Post a new project

### 💰 Bidding

* `POST /api/bids` – Place a bid
* `GET /api/bids/:projectId` – View bids

---

## 🧪 Testing Tools

* 🔍 **Postman** – for testing APIs
* 🗄️ **MongoDB Compass** – for managing the database
* 🧪 **Chrome DevTools** – for frontend debugging



## 📽️ Demo

A complete demo is available here:
[📂 Google Drive Demo & Source Files](https://drive.google.com/drive/folders/1_o7fKyMsaHVeMXh5BNQH8twcfwmztwk9?usp=sharing)


## 🙌 Contributing

Feel free to fork this repo and contribute by submitting a pull request. For major changes, please open an issue first to discuss what you would like to change.
-




   
