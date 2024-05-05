# Admin Panel for MongoDB Management

## Objective

The objective of this project is to create an admin panel that provides features to manage MongoDB instances, databases, users, and their access roles. This admin panel allows administrators to manage multiple MongoDB instances, their databases, and user access efficiently and securely.

## Features

### 1. Login/Signup
- Users can create an account or log in securely to access the admin panel.

### 2. MongoDB Instance Management
- **Add Instances**: Admin can add multiple MongoDB instances.
- **List of Connected Instances**: The admin panel displays the list of connected instances, showing the number of databases and users for each instance.

### 3. Database Management
- **Create Databases**: Admin can create databases and add entries as desired.
- **Remove Databases**: Admin can remove databases from the system.

### 4. User Management
- **Create Users**: Admin can create new users.
- **Assign Access Roles**: Admin can assign access roles to users for specific databases (e.g., Edit access, Read-only access).
- **Change User Passwords**: Admin can change user passwords.
- **Remove Users**: Admin can remove users from the system.
- **Assign Users to Databases**: Admin can assign new users to specific databases.

### 5. Authentication Restrictions
- **Apply Restrictions**: Admin can apply authentication restrictions on users to enhance security.

### Additional Features
- **Change User's Password**: Admin can change a user's password.
- **Remove User**: Admin can remove a user from the system.
- **Remove Database**: Admin can remove a database.
- **Remove Access from Database**: Admin can revoke a user's access to a specific database.
- **Assign New User to Database**: Admin can assign new users to a specific database.

## Technical Considerations
- **Database**: Use MongoDB as the preferred database.
- **Data Security**: Ensure data security and user authentication mechanisms.
- **Frontend Framework**: Use an appropriate frontend framework for a user-friendly interface.
- **Error Handling and Validation**: Implement error handling and input validation mechanisms.
- **Role-Based Access Control**: Implement role-based access control for admin functionalities.

## References
- [MongoDB User Management Documentation] (https://www.mongodb.com/docs/manual/reference/method/db.createUser/)

## Evaluation Criteria
- **Functionality**: Completeness and correctness of implemented features.
- **Security**: Implementation of authentication, authorization, and data protection measures.
- **Code Quality**: Clarity, modularity, and efficiency of code.
- **User Experience**: Intuitiveness and responsiveness of the admin panel interface.
- **Error Handling**: Robustness in handling errors and edge cases.
- **Database Design**: Efficient schema design and data management strategies.
- **Documentation**: Clarity and completeness of code comments and documentation.

## Getting Started

### Prerequisites
- [Node.js] (https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- Frontend framework (e.g., React, Angular, Vue)

### Installation
1. Clone the repository:

    ```bash
    git clone <https://github.com/mohitverma27/flipr>
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

4. Set up MongoDB connection and configure environment variables.

### Running the Application
1. Start the backend server:

    ```bash
    npm start
    ```

2. In another terminal, start the frontend development server:

    ```bash
    npm run start:frontend
    ```

3. Access the admin panel in your browser:

    ```
    http://localhost:3000
    ```


## Contributing
- Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
- This project is licensed under the [MIT License](LICENSE).

## Contact
- For any questions or feedback regarding this project, please reach out to the maintainers mv270302@gmail.com (+91 7828479672).


