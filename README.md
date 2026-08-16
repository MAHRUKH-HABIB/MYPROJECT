🛍️ Shop Smart

Shop Smart is a full-stack e-commerce backend project developed using Python, FastAPI, SQLAlchemy, Pydantic, and Microsoft SQL Server.

The project provides core e-commerce functionality including user management, product management, shopping cart operations, order processing, and database-driven REST APIs.

This project was developed as part of a Final Year Project (FYP) and as a practical application of backend development and database management concepts.

🚀 Features
👤 User registration and management
🔐 Secure password hashing
👨‍💼 Admin management
📦 Product creation, updating, deletion, and listing
📊 Product stock management
🛒 Shopping cart management
🔢 Cart quantity tracking
🧾 Order placement
📜 Order history
🔗 RESTful API architecture
🗃️ Relational database integration
✅ Data validation using Pydantic
🧩 CRUD operations using SQLAlchemy
📡 Interactive API documentation with FastAPI
🛠️ Technologies Used
Backend
Python 3
FastAPI
SQLAlchemy
Pydantic
Database
Microsoft SQL Server Express 2022
SQL Server Management Studio (SSMS)
Libraries
pyodbc — SQL Server database connectivity
passlib — Password hashing
Development Tools
Visual Studio Code
SSMS
Git
GitHub
📂 Project Structure
SHOP-SMART/
│
├── myproject/
│   ├── main.py
│   ├── database.py
│   ├── models.py
│   ├── schemas.py
│   ├── users.py
│   ├── products.py
│   ├── cart.py
│   ├── orders.py
│   └── ...
│
├── requirements.txt
├── README.md
└── ...

Note: The exact file structure may change as the project continues to be developed.

🗃️ Database

Shop Smart uses Microsoft SQL Server Express 2022 as its relational database.

The database contains entities for managing:

Users
Admins
Products
Shopping Cart
Orders

Relationships between related entities are maintained using database keys and SQLAlchemy relationships.

🔌 API

The backend is implemented using FastAPI and provides RESTful API endpoints for managing different parts of the e-commerce system.

Main API Operations
Module	Operations
👤 Users	Create, Read, Update, Delete
📦 Products	Create, Read, Update, Delete
🛒 Cart	Add, Update, Remove, View
🧾 Orders	Place and View Orders
👨‍💼 Admin	Administrative operations

FastAPI also provides automatically generated interactive API documentation.

After starting the server, the documentation can be accessed through:

/docs

and the alternative API documentation through:

/redoc
📦 Installation
1. Clone the Repository
git clone https://github.com/SHOP-SMART123/MYPROJECT.git
2. Navigate to the Project
cd MYPROJECT
3. Create a Virtual Environment
python -m venv venv
4. Activate the Virtual Environment
Windows
venv\Scripts\activate
5. Install Dependencies
pip install -r requirements.txt
🗄️ Database Configuration

Before running the application, make sure SQL Server Express 2022 is installed and running on your system.

Configure the SQLAlchemy database connection according to your local SQL Server setup.

The connection configuration should contain the required:

SQL Server instance
Database name
Driver
Authentication details

⚠️ Do not upload passwords, database credentials, API keys, or other sensitive information to GitHub.

▶️ Running the Application

Start the FastAPI development server using:

uvicorn main:app --reload

If main.py is inside a package/folder, use the appropriate module path, for example:

uvicorn myproject.main:app --reload

Once the server is running, open the API documentation in your browser:

http://127.0.0.1:8000/docs
🧪 API Testing

The API can be tested using:

FastAPI Swagger UI
ReDoc
Postman
Other REST API testing tools

Swagger UI allows API endpoints to be tested directly from the browser.

🔐 Security

The project includes password hashing using Passlib rather than storing passwords as plain text.

Database credentials and other sensitive configuration values should be kept outside the public repository.

🎯 Learning Objectives

This project helped me practice and understand:

Backend development with Python
REST API development
FastAPI
CRUD operations
SQLAlchemy ORM
Pydantic data validation
Relational database design
SQL Server database integration
Password hashing
API testing
Git and GitHub
Debugging database and backend issues
🔄 Project Status

🚧 Project Status: Under Development

The core backend and database functionality has been implemented, while the project can continue to be improved with additional features, testing, security enhancements, and frontend integration.

🔮 Future Improvements

Add frontend interface

Implement user authentication with JWT

Add advanced product search

Add product categories and filtering

Add payment integration

Improve API validation and error handling

Add automated tests

Improve authentication and authorization

Deploy the application online

📌 Disclaimer

Shop Smart is an educational project developed for learning and academic purposes. It is not affiliated with or endorsed by any existing e-commerce company.

👩‍💻 Author

Mahrukh Habib

BS Information Technology Student
Backend & Web Development Learner

⭐ If you find this project useful or interesting, feel free to explore the repository.
