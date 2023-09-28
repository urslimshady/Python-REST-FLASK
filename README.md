# Python-REST-FLASK

A robust RESTful API built using Flask and connected to a SQLite database via SQLAlchemy. This API allows users to perform CRUD operations on two models: PERSON and NOTE. It comes with SwaggerUI for easy API documentation and Marshmallow for data validation and serialization.

Table of Contents
API Endpoints
Database
Configuration
Contributing

## API Endpoints
SwaggerUI: Access the API documentation and test endpoints interactively at http://localhost:5000/api/doc.

### PERSON Endpoints
GET /api/person: Retrieve a list of all people.
GET /api/person/{id}: Retrieve a specific person by ID.
POST /api/person: Create a new person.
PUT /api/person/{id}: Update a person by ID.
DELETE /api/person/{id}: Delete a person by ID.

### NOTE Endpoints
GET /api/note: Retrieve a list of all notes.
GET /api/note/{id}: Retrieve a specific note by ID.
POST /api/note: Create a new note.
PUT /api/note/{id}: Update a note by ID.
DELETE /api/note/{id}: Delete a note by ID.

## Database
This project uses SQLite as the database system. You can find the database file at db.sqlite. You can customize the database settings in the config.py file.

## Configuration
You can configure the API by modifying the settings in the config.py file. You may need to set database URLs, secret keys, and other environment-specific configurations.

## Contributing
Contributions are welcome! If you'd like to contribute to this project
