# freelancer-finder
A Freelancer Finder project connects clients with freelancers based on required skills, budget, and project timeline. It enables easy profile browsing, project posting, and secure communication between both parties.
<br>You can go througth the code links and acces every think about the projest as showen in thw DEMO_VIDEO.mp4 <br>
-> https://drive.google.com/drive/folders/1_o7fKyMsaHVeMXh5BNQH8twcfwmztwk9?usp=sharing
<br>
Download this zip file and access at your local mechine
<br>
🛠 Tech Stack
Frontend: React.js, Bootstrap, Material UI, Axios
Backend: Node.js, Express.js, MongoDB, Mongoose
Auth: JWT, bcrypt
Tools: Postman, MongoDB Compass, VS Code
⚙️ Features
📝 Project Posting & Bidding
🔐 Secure Authentication (JWT)
👤 Role-Based Dashboards (Client, Freelancer, Admin)
📬 In-App Messaging (Basic)
🛡️ Admin Moderation
📦 Setup Instructions
Prerequisites
Node.js, MongoDB, Git

# Install frontend dependencies
cd client && npm install

# Install backend dependencies
cd ../server && npm install
Environment Setup
Create .env in /server:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Run Locally
# Start backend
cd server && npm start

# Start frontend
cd ../client && npm start
Visit: http://localhost:3000

📌 API Routes
POST /api/auth/register – Register
POST /api/auth/login – Login
GET /api/projects – View all projects
POST /api/projects – Post a new project
POST /api/bids – Place a bid
GET /api/bids/:projectId – View bids
🧪 Testing Tools
Postman (API)
MongoDB Compass (DB)
Chrome DevTools (UI)
