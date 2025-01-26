#  Pizza Restaurants

*Date*: 2025/01/26  
*By*: God'swill Omuka

## Description
 Code Challenge for Pizza Restaurants involves building a Flask API to manage pizza restaurants, pizzas, and their associations. The challenge requires implementing database models, routes, and validations for managing restaurants and pizzas, including the ability to create and delete restaurant-pizza associations.

## Features

- *Restaurant Management*: Create, view, and delete restaurants.
- *Pizza Management*: View all pizzas and manage their associations with restaurants.
- *RestaurantPizza Association*: Create new associations between pizzas and restaurants with price validation.

## Installation

To get started with the Pizza Restaurants API, you need to clone the repository from GitHub.

### Installation Requirements

- GitHub
- Python 
- pyenv
- Node.js (for the React frontend)

### Installation Instructions

1. Clone the repository:
    bash
    git clone https://github.com/Godswillomuka/python-phase-4-code-challenge-pizza.git
    

2. Navigate to the project directory:
    
    cd python-phase-4-code-challenge-pizza
    

3. Install backend dependencies:
    
    pipenv install
    pipenv shell
    

4. Install frontend dependencies:
    
    npm install --prefix client
    

5. Set up the database and migrations:
    
    export FLASK_APP=server/app.py
    flask db init
    flask db migrate
    flask db upgrade head
    

6. Seed the database with sample data:
    
    python server/seed.py
    

7. Run the Flask API on localhost:5555:
    
    python server/app.py
    

8. Run the React app on localhost:4000:
    
    npm start --prefix client
    

## Technologies Used

- Python
- Flask
- SQLite
- React
- GitHub

## Support and Contact Details

For support or inquiries, please contact:

- *GitHub*: [Godswillomuka](https://github.com/Godswillomuka)

## License

The content of this project is licensed under the MIT License. Copyright (c) 2025.