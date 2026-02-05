# To run frontend:
  - Install **liveserver** extension in VSCode
  - Right click index.html
  - Click "run with liveserver"

# To run backend:
  - Open terminal on VSCode (CTRL + `)
  - Navigate to backend folder:
    ```bash
    # Change directory to the `backend`
    cd backend
  - Install node packages
    ```bash
    npm install
  - Run server:
    ```bash
    npx nodemon server.js

# Copy and paste your MongoDB connection string in the .env file
  - create a copy of the "env.example" file and name it  ".env"
  - paste connection string after "MONGODB_URI="
