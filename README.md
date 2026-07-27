# File Metadata Microservice

A REST API built with Node.js, Express, and Multer that extracts metadata from an uploaded file.

## Features

- Upload a file using a multipart/form-data request
- Returns the uploaded file's:
  - File name
  - MIME type
  - File size
- Handles file uploads using Multer middleware

## Technologies Used

- Node.js
- Express.js
- Multer
- JavaScript

## API Endpoint

### POST /api/fileanalyse

Uploads a file and returns its metadata.

Example response:

```json
{
  "name": "example.pdf",
  "type": "application/pdf",
  "size": 12345
}
```

## Project Purpose

This project was completed as part of the **freeCodeCamp Back End Development and APIs** certification. It demonstrates how to handle file uploads and extract metadata using Express and Multer.

## Author

**Musapu Nyendwa**
