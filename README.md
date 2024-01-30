# Lab 3: Node.js Dynamic Server Implementation

## Welcome to Lab 3
In this lab, you will gain hands-on experience building a simple dynamic server with Node.js. This exercise will enhance your understanding of server-side scripting, handling HTTP requests, and interacting with a database.

## Getting Started

### Prerequisites
- Git: [Install Git](https://git-scm.com) if it's not already installed on your machine.
- Node.js: Ensure you have Node.js installed to use `npm` for managing the project dependencies.

### Clone the Repository
To set up your lab environment, follow these steps to clone the lab repository:

1. Navigate to the lab GitHub page.
2. Click on the "Clone" button.
3. Copy the provided URL.
   ![Clone Button](https://github.com/SWE314/lab3/assets/16814184/8a10905d-1059-47e6-9c8a-04ede4157258)
4. Open your terminal and change to the directory where you want to clone the repository.
5. Execute the clone command with the copied URL:

   ```bash
   git clone [COPIED_REPOSITORY_URL]
   ```
Replace [COPIED_REPOSITORY_URL] with the actual URL you copied.

# Project Setup
1. Open the cloned project in Visual Studio Code (VS Code).
2. Open the integrated terminal in VS Code.
3. Install the project dependencies:
 ```bash
 npm install
```
4. To start the development server, run:
```bash
npm run dev
```

5. Access the application by navigating to http://localhost:3000 in your web browser.

# Installing SQLite Extension for VS Code

The SQLite extension allows you to interact with the database directly from VS Code.

To install the SQLite extension:

1. Open VS Code.
2. Go to the Extensions view by clicking on the square icon on the sidebar or pressing Ctrl+Shift+X.
3. Search for "SQLite".
4. Click on the "Install" button for the SQLite extension.
5. Type in the VS code search show and run command and click on it
<img width="853" alt="image" src="https://github.com/SWE314/lab3/assets/16814184/b4006e51-ebc5-4670-a682-68f6d542b040">

6. Then type SQLight and choose show database.
 <img width="846" alt="image" src="https://github.com/SWE314/lab3/assets/16814184/6f9f9e21-d7e1-4fba-ba19-5a949bdb4a8e">

7. choose the first database in the list.
<img width="863" alt="image" src="https://github.com/SWE314/lab3/assets/16814184/371bbec7-ce1c-41b1-92f7-f93234d85319">

8. Click on user table to see the data that exist in the table:
<img width="1185" alt="image" src="https://github.com/SWE314/lab3/assets/16814184/ae006e29-25a7-420a-8cbe-07d68c5528fa">

# Testing the Application

To ensure the application is running correctly:

1. Use the signup feature to create a new user account.
2. Log in with your new credentials.
3. Verify that the new user data is correctly stored in the database.

