Hello,

This the Expense Tracker Project develpoed by RESTful API's using the tool like Node.js with Express.js and SQLite Database.

**Setup and run instructions:**

  1. Get the code into your local device by using the command **"git clone https://github.com/revanth-collab/ExpenceTrackerAPI.git"**
  2. Move to the working directory **"cd .\expense-tracker\"**
  3. To start the server run the command **"node app.js"**
  4. This shows the text in the terminal like **"Server is running on port 3000"**
  5. To check the API Endpoints resposne install the jest by using the command **"npm install --save-dev jest"**
  6. Run the command **"npm test"**  or **"npm jest"**

**API's Documentation:**

  **BASIC URL**: http://localhost:3000/api

  1. Create a New Transaction
       POST http://localhost:3000/transaction

       Request body :
         {
          "type": "income", // or "expense"
          "category": "string",
          "amount": 100.0,
          "date": "YYYY-MM-DD", // e.g., "2024-10-23"
          "description": "string"
        }


  2. Retrive All Transaction
       GET http://localhost:3000/transaction


  3. Retrieve a Transaction by ID
       GET http://localhost:3000/transactions/:id


  4. Update a Transaction
       PUT http://localhost:3000/transactions/:id

       Request body:
         {
          "type": "expense",
          "category": "entertainment",
          "amount": 150,
          "date": "YYYY-MM-DD",
          "description": "Movie tickets"
        }

  5. Delete a Transaction
       DELETE http://localhost:3000/transactions/:id

  6. Retrieve Summary of Transactions
       GET http://localhost:3000/summary


**Postman screenshots demonstrating each API call:**

  1. Create a New Transaction
       ![Screenshot 2024-10-23 095003](https://github.com/user-attachments/assets/bc3a6027-22a9-403d-ad14-4ef001829aac)

  2. Retrive All Transaction
       ![Screenshot 2024-10-23 095327](https://github.com/user-attachments/assets/51e8065a-5d04-4434-84df-be11609e681c)

  3. Retrive a Transaction by ID
       ![Screenshot 2024-10-23 095450](https://github.com/user-attachments/assets/3be68f92-d6ca-43e8-869d-d24b14a32346)

  4. Update a Transcation
      ![Screenshot 2024-10-23 095833](https://github.com/user-attachments/assets/6a4bd404-cfe1-4380-b075-c3284ff4e563)

  5. Delete a Transaction
       ![Screenshot 2024-10-23 100101](https://github.com/user-attachments/assets/0b949140-28fe-4ef6-9603-7eced0fe7b98)

  6. Retrieve Summary of Transactions
       ![Screenshot 2024-10-23 100217](https://github.com/user-attachments/assets/d896f284-81fd-4aaa-990d-e31fc10d83a8)




       
     
