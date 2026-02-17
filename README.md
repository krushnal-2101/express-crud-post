
https://github.com/user-attachments/assets/401be13d-6855-4744-b59a-a57faa4d90f2

📌 Express CRUD API – Task Manager

A simple REST API built with Node.js and Express.js to perform CRUD operations on a task list.

🚀 Features

✅ Get all tasks

✅ Get task by ID

✅ Add new task

✅ Update task (PATCH & PUT)

✅ Delete task

✅ Proper status codes

✅ Error handling

🛠️ Tech Stack

Node.js

Express.js

Postman (for API testing)

📂 Project Structure
express-crud/
│
├── middleware/
│   └── HttpError.js
│
├── app.js
├── package.json
├── package-lock.json
└── README.md

📦 Installation

1️⃣ Clone the repository

git clone https://github.com/your-username/express-crud.git


2️⃣ Navigate to project folder

cd express-crud


3️⃣ Install dependencies

npm install


4️⃣ Run the server

node app.js


Server will start on:

http://localhost:5000

📡 API Endpoints
🔹 Get All Tasks
GET /taskList

🔹 Get Task By ID
GET /taskList/:id

🔹 Add Task
POST /addtask


Body (JSON):

{
  "task": "Learn Express",
  "description": "Build CRUD API"
}

🔹 Update Task (Partial Update)
PATCH /updateTask/:id

🔹 Update Task (Full Update)
PUT /updateTasks/:id

🔹 Delete Task
DELETE /deleteTask/:id

📮 Testing with Postman

Open Postman

Use base URL:

http://localhost:5000


Select request method (GET, POST, PUT, PATCH, DELETE)

Send request

📌 Example Response
{
  "message": "Task Data Updated Successfully",
  "task": {
    "id": 1,
    "task": "Learn Express",
    "description": "Build REST API"
  }
}

👨‍💻 Author

Krushnal Bhatti

📄 License

This project is licensed under the MIT License.
