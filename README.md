# Job Portal Be-rojgar

Job Portal is a MERN Stack-based web app that helps streamline the flow of the job application process. It allows users to select their roles (applicant/recruiter), and create an account. In this web app, login sessions are persistent and REST APIs are securely protected by JWT token verification. After logging in, a recruiter can create/delete/update jobs, shortlist/accept/reject applications, view resumes, and edit profiles. And, an applicant can view jobs, perform fuzzy searches with various filters, apply for jobs with an SOP, view applications, upload a profile picture, upload a resume, and edit a profile. Hence, it is an all-in-one solution for a job application system.


The directory structure of the web app is as follows:

```
- backend/
    - public/
        - profile/
        - resume/
- frontend/
- README.md



## Dependencies:

- Frontend
  - @material-ui/core
  - @material-ui/icons
  - @material-ui/lab
  - axios
  - material-ui-chip-input
  - react-phone-input-2
- Backend
  - bcrypt
  - body-parser
  - connect-flash
  - connect-mongo
  - cors
  - crypto
  - express
  - express-session
  - jsonwebtoken
  - mongoose
  - mongoose-type-email
  - multer
  - passport
  - passport-jwt
  - passport-local
  - uuid

