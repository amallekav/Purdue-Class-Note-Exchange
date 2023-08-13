# Purdue-Class-Note-Exchange
By Ankitha Mallekav

ClassNotes Exchange: Collaborative Note Sharing for Purdue University Students

Create a web platform exclusively for Purdue University students that facilitates the sharing of class notes and valuable tips among students. The platform incentivizes note-sharing by implementing a virtual currency system where students earn coins by sharing their own notes and can use these coins to access notes from other classes. Additionally, students can leave tips and recommendations for specific classes to help future students make informed decisions about their course selections. 

1. User Registration and Login:
- Create HTML templates for user registration and login forms.
- Implement backend routes in Flask for user registration, login, and session management.
- Store user information securely in a database.

2. Note Sharing:
- Develop an HTML form for users to upload and share their class notes.
- Handle file uploads and store the notes securely in the database.
- Implement logic to allocate virtual coins to the user for each uploaded note.

3. Note Access:
- Create HTML templates to display shared notes and allow users to access them.
- Implement logic to deduct virtual coins from the user's account when accessing shared notes.
- Provide filtering and search options to help users find relevant notes.

4. Virtual Currency System:
- Design and create a database schema to store user account details, including virtual coin balances.
- Implement functionality to credit and deduct virtual coins based on user actions (e.g., uploading notes, accessing shared notes).
- Display the user's virtual coin balance on their profile page.

5. Class Tips:
- Develop HTML forms for users to leave tips and recommendations for specific classes.
- Store the tips securely in the database.
- Display the tips on the relevant class pages for future students to access.

6. Database Integration:
- Integrate a database system (e.g., SQLite, PostgreSQL) using SQLAlchemy or Flask-SQLAlchemy.
- Create database models for users, notes, class tips, and any other relevant entities.
- Define relationships between different entities to establish proper data structure.

7. User Profile:
- Design an HTML template for the user profile page.
- Display user information, including their uploaded notes, virtual coin balance, and any other relevant details.
- Implement functionality to update user profiles, such as changing passwords or updating personal information.

8. User Authentication and Authorization:
- Use Flask-Login or similar libraries to handle user authentication and session management.
- Protect routes and functionalities that require user authentication.
- Implement authorization checks to ensure users can only access and modify their own data.

9. Frontend Styling and Layout:
- Create CSS stylesheets to enhance the visual appeal of the platform.
- Design a consistent layout and navigation structure across different pages.
- Apply responsive design principles to ensure a seamless user experience on various devices.
