# python_projects_grocery_webapp
In this python project, we have built a grocery store management application. It is a 3 tier application,
1. Front end: UI is written in HTML/CSS/Javascript/Bootstrap
2. Backend: Python and Flask
3. Database: mysql

![alt text](image.png)


🚀 Features
Product Management
1. Add, update, and delete grocery products
2. Assign unit of measurement (UOM) to each product

Order Management
1. Create and manage customer orders
2. Automatic total price calculation

Interactive UI
1. Responsive layout with Bootstrap
2. Sidebar navigation menu

Database Integration
1. MySQL backend for persistent data storage
2. DAO (Data Access Object) pattern for clean database interactions


⚙️ Installation & Setup
1. Clone the repository
    git clone https://github.com/bh-trishna/Grocery-Store-Management-System.git
    cd grocery_app

2. Set up a Python virtual environment  
   (optional but recommended)
    python -m venv venv
    source venv/bin/activate   # On Mac/Linux
    venv\Scripts\activate      # On Windows

3. Install dependencies
    pip install -r requirements.txt

4. Set up the MySQL database
    Create a database in MySQL (e.g., grocery_db)
    Update sql_connection.py with your database credentials
    Run SQL scripts to create required tables (products, orders, uom)

5. Run the backend server
    python backend/server.py

6. Open the frontend
    Open ui/index.html in a browser, or set up Flask to serve static files.
