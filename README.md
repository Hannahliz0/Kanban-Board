# Employee Tracker
  
  ## Description
 This project extends an existing Kanban board application by adding user authentication through JSON Web Tokens (JWT). The enhancements include a secure login page, authentication handling for API requests, and session management with JWTs. The application ensures secure access to the Kanban board and implements user-friendly error handling and session expiration.

  ## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [contributors](#contributors)
  * [Tests](#tests)
  * [Questions](#questions)

  ## Installation
  1. Clone the repository
  2. Navigate to the project directory
  3. Install the required dependencies
  4. Run the application

  ## Usage
  Once the application is running, you'll interact with it through the command line. Here's how to use the various features:
    1. Access the Application:
        - Navigate to the deployed URL or run the application locally.

    2. Login:
        - Use the login page to enter your credentials (username and password).
        - If valid, you'll be authenticated and redirected to the Kanban board.
        - If invalid, an error message will guide you to retry.
   
    3.Access Kanban Board:
        -Use the board to create, update, and manage tasks.

    4. Session Management:
        - JWTs are stored securely in the browser's local storage after login.
        - On logout, JWTs are removed, and you are redirected to the login page.
        - Inactive sessions automatically expire, requiring a fresh login.



  ## Contributing
  - Hannah Schmidt, Student 
  - Sabrin, Student

  ## Tests
  1. Login Authentication:
        - Enter valid credentials and confirm redirection to the Kanban board.
        - Enter invalid credentials and verify the error message.

  2. JWT Storage:
        - Confirm that the JWT is securely stored in local storage after login.
        - Verify removal of JWT from storage upon logout.

  3. Session Expiry:
        - Simulate inactivity and ensure that the session expires correctly, requiring re-authentication.

  4.Access Control:
     - Attempt to access the Kanban board without a valid JWT and confirm redirection to the login page.



  ## Questions
  If you have any questions, please contact me at hnbright57@gmail.com, find me on GitHub at hannahliz0, or visit my GitHub profile at https://github.com/Hannahliz0


# Repo Link

