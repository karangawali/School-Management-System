# School Management System
## Features :
   ### User Roles: 
   The system accommodates three distinct user roles: Admin, Teacher, and Student, each with its own specific functionalities and access privileges.

   ### Admin Dashboard:
   Administrators have the ability to add new students and teachers, create classes and subjects, manage user accounts, and oversee system settings.

   ### Attendance Tracking:
   Teachers can effortlessly take attendance for their classes, mark students as present or absent, and generate attendance reports.

   ### Performance Assessment:
   Teachers can evaluate students' performance by assigning marks and giving feedback. Students can view their marks and monitor their progress over time.

   ### Data Visualization:
   Students can visualize their performance data through interactive charts and tables, helping them understand their academic performance at a glance.

   ### Communication:
   Users can communicate effortlessly through the system. Teachers can send messages to students and vice versa, promoting effective communication and collaboration.

# installation
Open 2 terminals in separate windows/tabs.

Terminal 1: Setting Up Backend
```sh
cd backend
npm install
npm start
```
Create a file called .env in the backend folder. Inside it write this :
```sh
MONGO_URL = mongodb://127.0.0.1/school
```

If you are using MongoDB Compass you can use this database link but if you are using MongoDB Atlas then instead of this link write your own database link.

Terminal 2: Setting Up Frontend

```sh
cd frontend
npm install
npm start
```

Now, navigate to localhost:3000 in your browser. The Backend API will be running at localhost:5000.


