Note Taker Application
# Description

This Note Taker application allows users to write, save, and delete notes. The application is built with a back-end using Express.js to handle data storage and retrieval, and a front-end using HTML, CSS, and JavaScript to provide a user-friendly interface.

## Table of Contents

- [File Structure](#file-structure)
- [Installation](#installation)
- [Usage](#usage)
- [API Routes](#api-routes)
- [License](#license)
- [Questions](#questions)

## File Structure
```
note-taker/
├── Develop/
│   ├── db/
│   │   └── db.json
│   ├── node_modules/
│   ├── public/
│   │   ├── assets/
│   │   │   ├── css/
│   │   │   └── js/
│   │   │       └── index.js
│   │   ├── index.html
│   │   └── notes.html
│   ├── .gitignore
│   ├── package-lock.json
│   ├── package.json
│   └── server.js
```

## Installation

1. Clone the repository to your local machine:
    ```
    git clone https://github.com/ElijahWard4/note-taker.git
    ```

2. Navigate to the project directory:
    ```
    cd note-taker
    ```

3. Install the necessary dependencies:
    ```
    npm install
    ```

## Usage

1. Start the server:
navigate to Develop:
    ```
    npm start
    ```

2. Open your browser and navigate to http://localhost:3001 to use the Note Taker application.

## API Routes

### Get All Notes

- URL: /api/notes
- Method: GET
- Description: Retrieves all saved notes.
- Response: JSON array of note objects.

### Save a New Note

- URL: /api/notes
- Method: POST
- Description: Saves a new note.
- Request Body: JSON object with title and text properties.
- Response: JSON object of the saved note.

### Delete a Note

- URL: /api/notes/:id
- Method: DELETE
- Description: Deletes a note by its ID.
- Response: JSON object indicating success.

## License

This project is licensed under the MIT License.

## Questions

If you have any questions, please feel free to contact me at elijah.ward014@gmail.com. Happy Coding!