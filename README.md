# getScan - File Sharing Website via QR Codes

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

getScan is a web-based application designed to simplify file sharing using QR codes. Users can easily upload files, and the system generates unique QR codes for each file, enabling quick and convenient downloads.

## Project Overview

This project aims to provide a user-friendly platform for sharing files through the generation of QR codes. QR codes are machine-readable labels that store data, including files, making them efficient for quick data transfer. getScan leverages this technology to streamline file sharing.

## Demo

![Getscan Demo](https://github.com/user-attachments/assets/1bb8e424-a3cc-4dc7-96ad-8b22b4fb2bb8) 

## Features

* **File Upload:** Allows users to upload various file formats (PDF, images, documents, etc.).
* **QR Code Generation:** Automatically generates unique QR codes for uploaded files.
* **Direct Download:** Scanning the QR code directs users to a download page.
* **File Compression:** Files are compressed to reduce size before QR code generation.
* **User-Friendly Interface:** Intuitive and easy-to-navigate design.

## Technologies Used

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Node.js
* **Database:** MongoDB
* **Server Environment:** XAMPP

## Getting Started

1.  **Prerequisites:**
    * Node.js and npm installed
    * MongoDB installed and running
    * XAMPP installed
2.  **Installation:**
    * Clone the repository: `git clone https://github.com/Beast1506/GetScan.git`
    * Navigate to the project directory: `cd getScan`
    * Install dependencies: `npm install`
    * Set up MongoDB connection string in a `.env` file:
        ```
        MONGODB_URI=your_mongodb_connection_string
        PORT=your_desired_port (e.g., 3000)
        ```
3.  **Running the Application:**
    * Start XAMPP server.
    * Run the Node.js server: `npm start`
    * Open your browser and navigate to `http://localhost:[your_desired_port]`

## Usage

1.  Upload a file using the "Choose File" button.
2.  A QR code will be generated automatically.
3.  Share the QR code with others.
4.  Scanning the QR code will direct users to a download page.

## Future Enhancements

* **Batch File Processing:** Allow users to upload and convert multiple files at once.
* **Customization Options:** Provide options to customize QR code appearance (colors, logos).
* **Cloud Storage Integration:** Integrate with cloud services like Google Drive or Dropbox.
* **Improved Security:** Implement password protection and encryption for QR codes.
* **Real-Time Updates:** Enable updating information within QR codes dynamically.

## Contributing

Contributions are welcome! If you find any issues or have suggestions, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
