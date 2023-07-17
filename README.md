# Purdue-Class-Note-Exchange
ClassNotes Exchange: Collaborative Note Sharing for Purdue University Students

Create a web platform exclusively for Purdue University students that facilitates the sharing of class notes and valuable tips among students. The platform incentivizes note-sharing by implementing a virtual currency system where students earn coins by sharing their own notes and can use these coins to access notes from other classes. Additionally, students can leave tips and recommendations for specific classes to help future students make informed decisions about their course selections.  create a decription for this project for my resume- 1 sentence

Plan: 
User Registration and Login:

Created HTML templates for user registration and login forms.
Implemented backend routes in Flask for user registration, login, and session management.
Stored user information securely in a database.

Note Sharing:

Developed an HTML form for users to upload and share their class notes.
Handled file uploads and stored the notes securely in the database.
Implemented logic to allocate virtual coins to the user for each uploaded note.

Note Access:

Created HTML templates to display shared notes and allowed users to access them.
Implemented logic to deduct virtual coins from the user's account when accessing shared notes.
Provided filtering and search options to help users find relevant notes.

Virtual Currency System:

Designed and created a database schema to store user account details, including virtual coin balances.
Implemented functionality to credit and deduct virtual coins based on user actions (e.g., uploading notes, accessing shared notes).
Displayed the user's virtual coin balance on their profile page.

Class Tips:

Developed HTML forms for users to leave tips and recommendations for specific classes.
Stored the tips securely in the database.
Displayed the tips on the relevant class pages for future students to access.

Database Integration:

Integrated a database system (e.g., SQLite, PostgreSQL) using SQLAlchemy or Flask-SQLAlchemy.
Created database models for users, notes, class tips, and any other relevant entities.
Defined relationships between different entities to establish proper data structure.

User Profile:

Designed an HTML template for the user profile page.
Displayed user information, including their uploaded notes, virtual coin balance, and any other relevant details.
Implemented functionality to update user profiles, such as changing passwords or updating personal information.

User Authentication and Authorization:

Used Flask-Login or similar libraries to handle user authentication and session management.
Protected routes and functionalities that required user authentication.
Implemented authorization checks to ensure users could only access and modify their own data.

Frontend Styling and Layout:

Created CSS stylesheets to enhance the visual appeal of the platform.
Designed a consistent layout and navigation structure across different pages.
Applied responsive design principles to ensure a seamless user experience on various devices.

Security Measures:

Implemented user input validation to ensure data integrity and prevent malicious actions.
Protected against SQL injection and cross-site scripting (XSS) attacks.
Secured file uploads to prevent unauthorized access.
