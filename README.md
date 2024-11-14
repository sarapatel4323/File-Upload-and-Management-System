
# File Upload and Management System

This project is a web application for managing file uploads and viewing files in a gallery. It allows users to upload single or multiple files, fetch random files, and view all uploaded files in a gallery with optional pagination.


## Features
- **Single File Upload**: Allows users to upload one file at a time.
- **Multiple File Upload**: Supports uploading multiple files simultaneously.
- **Fetch Random Files**: Provides options to fetch and view random files from the database.
- **Gallery View**: Displays all uploaded files in a visually appealing gallery format.
- **Pagination**: Supports pagination to navigate through large numbers of files easily.


-- Replace `<your-mongodb-uri>` with your MongoDB connection string.

## Available Endpoints

### Main Routes
| Endpoint                   | Description                           |
|----------------------------|---------------------------------------|
| `/upload`                  | Upload a single file                 |
| `/upload/multiple`         | Upload multiple files                |
| `/fetch-random`            | Fetch a random file                  |
| `/fetch-multiple-random`   | Fetch multiple random files          |
| `/gallery`                 | View gallery of all files            |
| `/gallery-pagination`      | View gallery with pagination         |

### Static Pages
| Endpoint                   | Description                           |
|----------------------------|---------------------------------------|
| `/`                        | Home page with links to features     |

