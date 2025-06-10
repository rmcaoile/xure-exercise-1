# User Form App

A simple React application for submitting, editing, viewing, and deleting user information.

## Features
- Add new user information 
- Edit existing user data
- Validate inputs
- Confirming before submitting data
- Delete individual users or all users with confirmation


## Walkthrough 

- **Add New User**  
  Opens a modal form where users can enter new user details.  
  Input validation ensures data is properly formatted and logically consistent before submission.

- **Edit User**  
  Loads the selected user's data into the form for editing.  
  Upon submitting changes, the original entry is updated with the new data.

- **Delete Individual User**  
  Clicking the delete button prompts for confirmation.  
  If confirmed, the selected user is removed from the list.

- **Delete All Users**  
  A delete-all option is available and requires confirmation.  
  Once confirmed, all user data entries are cleared.

- **Input Validation**  
  - Names must begin with a letter and may include apostrophes, spaces, and hyphens.  
  - Suffixes are optional and limited to 5 characters.  
  - Age must match the calculated age based on the entered birthdate.



## What I learned
- Modal handling and conditional rendering in React.
- I learned more about proper error handling and validating in form submission.
- Importance of input validation, especially when dependent fields like age and birthdate must correlate.

## Challenges Faced
- Ensuring the birthdate-to-age logic accurately matched.
- Managing multiple modals (form, confirm delete, confirm clear).
- Reusing Form modal for editing user information.
