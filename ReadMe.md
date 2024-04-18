# QR Code Generator

This project contains a client-server application for generating QR codes from URLs. The server is responsible for QR code generation, while the client provides a user-friendly graphical interface.

## Installation

1. Clone the repository:

    ```
    git clone https://github.com/your_username/QR-Code-Generator.git
    ```

2. Navigate to the project directory:

    ```
    cd QR-Code-Generator
    ```

## Usage

### Running the Server

1. Open a terminal.
2. Navigate to the project directory.
3. Run the server:

    ```
    python server.py
    ```

4. The server will start running and listening for requests on `localhost:8000`.

### Running the Client

1. Open another terminal.
2. Navigate to the project directory.
3. Run the client:

    ```
    python client.py
    ```

4. The GUI for the QR code generator will open.
5. Enter the URL you want to generate a QR code for.
6. Click on the "Generate QR Code" button.
7. The generated QR code will be displayed in the GUI.
8. Optionally, you can save the QR code by clicking on the "Save QR Code" button and choosing a location on your computer.

## Features

- Generate QR codes from URLs.
- Save generated QR codes to disk.

## Prerequisites

- Python 3.x
- Required Python packages (install using `pip install`):
  - `http.server`
  - `socketserver`
  - `urllib`
  - `qrcode`
  - `PIL`
  - `requests`
  - `tkinter`
