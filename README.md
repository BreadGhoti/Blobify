---
# Blobify

An experimental unblocker utilizing HTML, CORS proxies, JS Fetch, and a dream.

## Introduction

Blobify is a web application designed to fetch and process web content through various CORS proxies. It takes a user-provided URL, fetches the source, processes the references, and generates blob URLs for the resources, allowing for easier access to web content that might be blocked by CORS policies.

## Features

- Fetch web content through multiple CORS proxies.
- Process and replace references to scripts, stylesheets, and images with blob URLs.
- Display processed source code and blob URLs.
- Console output for logging progress and errors.

## Installation

To run Blobify locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/BreadGhoti/Blobify.git
   ```
2. Open the `index.html` file in your preferred web browser.

## Usage

1. Enter the URL you want to fetch in the input field.
2. Click the "Blobify" button to start the fetch and processing.
3. View the progress and results in the displayed sections:
   - Blob URLs: Lists the generated blob URLs for the resources.
   - Source Code: Displays the processed HTML source code.
   - Console: Logs the progress and any errors encountered.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push the branch.
4. Create a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
