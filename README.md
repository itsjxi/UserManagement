# User Details Management App

This is a React Redux application for managing user details. It allows users to view, add, edit, and delete user information.

## Features

### 1. Viewing User Details
   - Users can view a list of existing user details.

### 2. Adding User Details
   - Users can add new user details by providing necessary information such as name, email, etc.

### 3. Editing User Details
   - Users can edit existing user details by clicking on the edit button, which opens a modal with pre-filled information. Upon editing and saving, the changes are reflected in the application state.

### 4. Deleting User Details
   - Users can delete user details by clicking on the delete button, which prompts a confirmation modal before permanently removing the user details from the list.

### 5. Updating Details in State
   - User details are stored in the Redux state, ensuring a single source of truth for the application data. Updates made to user details are reflected across the application.

### 6. Like Functionality
   - Users can like or favorite specific user details, providing a way to mark certain users as favorites.

## Technologies Used

- React: v18.2.0
- Redux: v9.1.0
- React Redux Toolkit: v2.0.1
- React Icons: v5.0.1

## Installation

1. Clone the repository "https://github.com/itsjxi/UserManagement.git"
2. Install dependencies using `npm install`.
3. Start the development server with `npm start`.

## How to Use

- Upon launching the application, you will be presented with a list of user details.
- Use the provided buttons and modals to perform actions such as liking, editing, and deleting user details.
- Like specific user details by clicking on the like button.