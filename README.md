# 📌 Trello-API-Testing-Project


This project showcases practical API testing skills using Postman with Trello’s RESTful API. The test flow simulates a basic task management scenario involving the creation and manipulation of boards, lists, cards, labels, and checklists.
Key features tested:

✅ Creating, updating, retrieving, and deleting boards (POST, PUT, GET, DELETE)

📋 Managing lists and cards

🏷️ Adding and verifying labels

✔️ Handling checklists and check items

🧪 Asserting response status codes, data types, response times, and data integrity


The tests use collection and environment variables, pre-request scripts, and dynamic JavaScript assertions to ensure robust and maintainable API validation.
EndFragment

## 🚀 How to Use This Project

Follow these steps to get started with the Trello API Testing project using Postman:
#### 1. ✏️ Create a free trello account at the [Trello website](https://trello.com/)
#### 2. 🔑 Log in, go to the [Trello developer API key generation page](https://trello.com/app-key) and create your personal key and token.
#### 2. 📂 Clone the Repository or simply  download the ZIP file and extract it
#### 3. 🔄 Import the Collection into Postman
#### 4. ⚙️ Set Up Environment Variables
  - base_url: 	https://api.trello.com/1
  - key: 	<i>your Trello API key</i>
  - token: 	<i>your Trello API token</i>
![image](https://github.com/user-attachments/assets/51ce0add-3df3-460e-96ca-000431935a30)

#### 4. 📤 Send Requests
  - Make sure your Trello environment is selected.
  - Run the requests in order: start with Create Board, then Create List, Create Card, etc.
  - Some variables like board_id are automatically saved after requests.

#### 5. ✅ Run Tests
Each request includes built-in tests (under the Tests tab). After sending a request, scroll down to the Tests section in Postman to see the results (green = pass ✅, red = fail ❌).

#### 6. 🧪 Optional: Use Postman Collection Runner
  - Click the Run button.
  - You can add nuber of iteration or deley in Run configuration section
  - Click Run Trello API Testing project to run the whole test suite automatically!
  ![image](https://github.com/user-attachments/assets/fdcfcf77-1f66-4426-8875-7a0c6ecac16b)

  - You can also create a Monitor to automatically run the collection at scheduled intervals.
