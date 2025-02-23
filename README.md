# PDF Merger Tool

A simple web application built with **Node.js**, **Express**, and **Multer** to merge PDF files.

## Features
- Upload two PDF files and merge them.
- Uses `pdf-merger-js` for merging.
- Frontend built with Bootstrap for a clean UI.

## Installation
### 1. Clone the Repository
```sh
git clone https://github.com/your-username/pdf-merger.git
cd pdf-merger
```

### 2. Install Dependencies
```sh
npm install
```

### 3. Run the Server
```sh
node server.js
```

The server will start at: `http://localhost:3000`

## Usage
1. Open `http://localhost:3000` in your browser.
2. Select two PDF files and click **Merge PDF**.
3. The merged file will be available for download.

## Project Structure
```
/pdf-merger
├── public/          # Merged PDF files (accessible via /static)
├── uploads/        # Temporary file uploads
├── templates/
│   ├── index.html  # Frontend UI
├── server.js       # Express server
├── merge.js        # PDF merging logic
├── package.json    # Project dependencies
├── README.md       # Documentation
```

## Dependencies
- `express` - Web framework
- `multer` - File upload middleware
- `pdf-merger-js` - PDF merging library
- `path` - File path utilities

## Contributing
Pull requests are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch (`feature-name`).
3. Commit your changes.
4. Open a pull request.


---
### Author
Developed by [Ramadugu Dhanush Karthikeya](https://github.com/RDK7159357)

