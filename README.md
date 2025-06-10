# User Form App

A simple React application for submitting, editing, viewing, and deleting user information.

## Features
- Add new user information 
- Edit existing user data
- Validate inputs
- Confirming before submitting data
- Delete individual users or all users with confirmation


## Walkthrough of Features & Functions
- Add New User
    Opens a modal form for entering user details. Input validation is performed to ensure proper formatting and logical consistency 
- Edit User
    Loads the selected user's data into the form for editing. Upon submission, the original entry is updated.
- Delete Individual User
    Prompts for confirmation before removing the selected user from the list.
- Delete All Users
    Deletes all submitted user data after confirmation.
- Input Validation Includes:
    Names must begin with a letter and can include apostrophes, spaces, and hyphens.
    Suffixes are optional, limited to 5 characters.
    Age must match the calculated age based on the birthdate.


## What I learned
- Modal handling and conditional rendering in React.
- I learned more about proper error handling and validating in form submission.
- Importance of input validation, especially when dependent fields like age and birthdate must correlate.

## Challenges Faced
- Ensuring the birthdate-to-age logic accurately matched.
- Managing multiple modals (form, confirm delete, confirm clear).
- Reusing Form modal for editing user information.