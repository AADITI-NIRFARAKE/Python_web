# Python_web


# Simple Python Web Browser

This is a basic demonstration of socket communication between a web browser and a server, implemented in Python.

## Overview

This project consists of two Python files:

- `server.py`: This file contains the server-side code. It listens for incoming connections from clients (web browsers) and serves HTML content upon request.
- `browser.py`: This file contains the client-side code. It establishes a connection with the server and sends HTTP requests to retrieve and display web pages.

## Usage

### Server

1. Run `server.py` using Python 3: `python server.py`.
2. The server will start listening for incoming connections on a specified port (default is port 8080).

### Browser

1. Run `browser.py` using Python 3: `python browser.py`.
2. The browser will establish a connection with the server and prompt you to enter a URL.
3. Enter the URL of the web page you want to retrieve (e.g., `http://example.com`).
4. The browser will send an HTTP request to the server, which will then fetch the web page and display it in the terminal.

## Dependencies

- Python 3.x
- No additional dependencies required.

## Notes

- This project is intended for educational purposes only and may not be suitable for production use.
- The browser implementation is very basic and lacks many features found in modern web browsers.
- The server implementation is also minimal and may not handle all edge cases or HTTP methods.
