#Todo App

Installation Steps

git clone https://github.com/Vamsibolem10/todo.git
cd todo

Setup Backend

cd backend
npm install
notepad .env

Add the following inside .env:

MONGO_URI=mongodb://localhost:27017/todoapp
PORT=5000

Then start the backend:

node server.js

Setup Frontend

cd ../frontend
npm install

Then start the frontend:

npm start

Running the Application

Backend API: http://localhost:5000

Frontend App: http://localhost:3000

Screenshots

Light Mode
![Light Mode](https://github.com/user-attachments/assets/868770c5-ee10-48c0-b86d-f7da84c1cc12)
Dark Mode
![Dark Mode](https://github.com/user-attachments/assets/777f64e6-94ae-4b91-8976-2daffc2fc5b2)
Add Task
![Add Task](https://github.com/user-attachments/assets/4c39c7c4-5a03-4ecb-ae08-28657b1c4d51)
Checkbox Task
![checkbox](https://github.com/user-attachments/assets/00969b9e-34d6-428c-b21a-ac0bbbf77229)
