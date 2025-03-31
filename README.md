Testing the Project
Backend Testing
Run the server: python manage.py runserver

Test API endpoints using Postman:

GET http://localhost:8000/api/items/ → Should return a list of items.

POST http://localhost:8000/api/items/ with JSON body:

json
Copy
Edit
{
  "name": "Laptop",
  "category": "Electronics",
  "description": "A powerful laptop"
}
PUT http://localhost:8000/api/items/1/ → Update an item.

DELETE http://localhost:8000/api/items/1/ → Delete an item.

Frontend Testing
Run the frontend: npm start

Check the UI:

The table should list items fetched from the API.

Newly added items should appear without refreshing.
