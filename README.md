# jsonserverassign


# App PRODUCT DATA --->   https://jsonserverpage.onrender.com/Phones


# App USER DATA --->   https://jsonserverpage.onrender.com/users


---
# JSON Server for Phones and Users
This JSON Server serves as a mock backend for handling phone products and user data. It's useful for testing and prototyping frontend applications that interact with a server.
---
# Endpoints
# Phones
GET /Phones: Get the list of phones.
GET /Phones/:id: Get details of a specific phone by ID.
GET /Phones/categories: Get all available phone categories.
# Users
GET /users: Get the list of users.


---
# Phones
Get All Phones

curl https://jsonserverpage.onrender.com/Phones
Get a Specific Phone

curl https://jsonserverpage.onrender.com/Phones/1
Get Phone Categories

curl https://jsonserverpage.onrender.com/Phones/categories
# Users
Get All Users

curl https://jsonserverpage.onrender.com/users



# Data Structure
---
# Phones
Each phone object has the following properties:

id: Unique identifier for the phone.
image: URL of the phone image.
title: Title of the phone model.
name: Name of the phone product.
mrp: Maximum Retail Price.
price: Selling price.
color: Color of the phone.
totimg: Total number of images.
brand: Brand of the phone.
category: Category of the phone (e.g., "Smartphones").


# Users
Each user object has the following properties:

id: Unique identifier for the user.
username: User's username.
avatar: URL of the user's avatar image.
email: User's email address.
password: User's password.
Example Requests
Here are some example requests using cURL:

# Get all phones
curl https://jsonserverpage.onrender.com/Phones

# Get details of a specific phone
curl https://jsonserverpage.onrender.com/Phones/1

# Get all users
curl https://jsonserverpage.onrender.com/users

 This README based on the features and functionality of your JSON Server.
