# Python-REST-FLASK

A robust RESTful API built using Flask and connected to a SQLite database via SQLAlchemy. This API allows users to perform CRUD operations on two models: PERSON and NOTE. It comes with SwaggerUI for easy API documentation and Marshmallow for data validation and serialization.

Table of Contents
API Endpoints
Database
Configuration
Contributing

## API Endpoints
SwaggerUI: Access the API documentation and test endpoints interactively at http://localhost:5000/api/ui.

### PERSON Endpoints
- GET /api/people: Retrieve a list of all people.
- GET /api/people/{person_id}: Retrieve a specific person by ID.
- POST /api/people: Create a new person.
- PUT /api/peopple/{person_id}: Update a person by ID.
- DELETE /api/people/{person_id}: Delete a person by ID.

### NOTE Endpoints
- GET /api/notes: Retrieve a list of all notes.
- GET /api/notes/{note_id}: Retrieve a specific note by ID.
- POST /api/notes/{person_id}: Create a new note with person id.
- PUT /api/notes/{note_id}: Update a note by ID.
- DELETE /api/notes/{note_id}: Delete a note by ID.

## Database
This project uses SQLite as the database system. You can find the database file at people.db. You can customize the database settings in the config.py file.

## Configuration
You can configure the API by modifying the settings in the config.py file. You may need to set database URLs, secret keys, and other environment-specific configurations.

## Contributing
Contributions are welcome! If you'd like to contribute to this project
