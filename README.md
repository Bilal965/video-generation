=== Instructions to Run this Project ===

1. Navigate to the project directory:
2. git clone https://github.com/Bilal965/video-generation.git
Access the Django admin at http://127.0.0.1:8000/admin/ using the superuser credentials.

Test the "Hello, Django!" route:
Open postman and go to http://127.0.0.1:8000/api/hello/. You should see the "Hello, Django!" message.

Test the RESTful API for managing movies:

Retrieve all items: http://127.0.0.1:8000/api/movie/
Add a new item: Use a tool Postman to send a POST request to http://127.0.0.1:8000/api/items/ with the item data.
Run the Movie Processing Command :
python manage.py video_generate.py

