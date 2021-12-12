# Groceries Server

### Express based REST server for serving MongoDB content using Mongoose node module

### Steps to run this code

1. Run `npm install` to install all required modules
2. Run `npm start` to start the server

### Dev Notes
```
// Add Paste
curl --header "Content-Type: application/json" --request POST --data {\"content\":\"www.target.com\"} http://localhost:8101/api/Paste_Board
// Get Pastes
curl --header "Content-Type: application/json" --request GET http://localhost:8101/api/Paste_Board
// Delete Paste
curl --header "Content-Type: application/json" --request DELETE http://localhost:8101/api/Paste_Board/:id
// Update Paste
curl --header "Content-Type: application/json" --request PUT --data {\"content\":\"www.amazon.com\"} http://localhost:8101/api/Paste_Board/:id
```
