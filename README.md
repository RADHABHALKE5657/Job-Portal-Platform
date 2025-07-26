# Job Portal

Job Portal is a MERN Stack based web app which helps in streamlining the flow of job application process. It allows users to select three roles (applicant/recruiter), and create an account. In this web app, login session are persistent and REST APIs are securely protected by JWT token verification. After logging in, a recruiter can create/delete/update jobs, shortlist/accept/reject applications, view resume and edit profile. And, an applicant can view jobs, perform fuzzy search with various filters, apply for jobs with an SOP, view applications, upload profile picture, upload resume and edit profile. Hence, it is an all in one solution for a job application system.



---

###  Directory structure of the web app:
backend/

public/

profile/

resume/

frontend/

README.md

---

###  Instructions to initialize the web app:

- Install Node JS and MongoDB.
- Start MongoDB server:

  ```bash
  sudo service mongod start
Move to backend:
cd backend
npm install
npm start
Server will run at http://localhost:4444
Move to frontend:
cd ../frontend
npm install
npm start
Frontend will run at http://localhost:3000

Open the browser at http://localhost:3000 to use the app.

</details>




