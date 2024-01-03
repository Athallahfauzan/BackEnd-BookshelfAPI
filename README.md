# Documentation: Running the Bookshelf API

Requirements
1. Node.js (latest version recommended)
2. NPM (Node Package Manager)
3. Postman or similar software for testing the API

## Setup and Installation
1. Clone the repository:
git clone [repository URL]

2. Navigate to the project directory:
cd Backend-BookshelfAPI

3. Open terminal in the project root directory, then run `npm install` to install the dependencies.

## Usage
1. Run the server:
`npm start`
This will start a local server. Typically, the server runs on http://localhost:9000, unless a different port is specified.

2. Accessing Endpoints
- Use Postman or similar software to access the API endpoints.
- Example endpoints: GET /books, POST /books, PUT /books/{bookId}, DELETE /books/{bookId}.

## Testing
1. Conducting Tests
- Open Postman.
- Create a new request for each endpoint.
- Example: To add a new book, use POST /books with the appropriate request body.

2. Validating Responses
- Ensure the API returns the appropriate response for each action.
- Example: For POST /books, ensure the new book is added to the list.

Additional Notes
-Be sure to check the configuration files and set up the appropriate environment.
-If using a database, configure your database connection.

Troubleshooting
-If you encounter errors, check the logs for more detailed information.
-Ensure all dependencies are correctly installed.
