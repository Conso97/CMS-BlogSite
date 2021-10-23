# User Model

- username

# Post Model

- title 
- contents
- post creator username (user_id : One-To-Many : One user can have many posts)
- data created 

# Comment Model

- comment text 
- comment post (ppost_id)
- comment usernme (user_id : One-To-Many : One user will have many comments)

# View 
- homepage
- single blog post page
- dashboard
- add post 
- edit post

{
    "id": 2,
    "product_name": "Running Sneakers",
    "price": 90,
    "stock": 25,
    "category_id": 5,
    "tags": [
      {
        "id": 6,
        "tag_name": "white",
        "product_tag": {
          "id": 4,
          "tag_id": 6,
          "product_id": 2
        }
      }
    ],
    "category": {
      "id": 5,
      "category_name": "Shoes"
    }
  },