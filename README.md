# User Management Dashboard

A simple web application to manage user details, allowing CRUD (Create, Read, Update, Delete) operations. Built using React, Bootstrap, and custom CSS for styling.

---

## **Features**
- View a list of users.
- Add a new user.
- Edit existing user details.
- Delete users from the list.
- Responsive design using Bootstrap.

---

## **Project Setup Instructions**

### Prerequisites
Ensure you have the following installed on your system:
- [Node.js](https://nodejs.org) (version 14 or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Steps to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/user-management-dashboard.git

### Directory Structure
src/
├── components/
│   ├── UserForm.js       # Component for adding/editing user details
│   ├── UserList.js       # Component for displaying the list of users
├── App.js                # Main component that wraps everything
├── index.js              # Entry point of the application
├── index.css             # Global styles for the application

### Components
1. UserList
Displays the user list in a table format.
Fetches user data from https://jsonplaceholder.typicode.com/users.
Handles deletion of users and opening the UserForm component for editing.
2. UserForm
Displays a form for adding or editing a user.
Accepts user data as props for editing existing users.
Sends the updated or new user data back to the parent component via callbacks.