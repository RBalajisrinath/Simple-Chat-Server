# Simple Chat Application

This is a simple chat application using Flask, Flask-SocketIO, and a web-based interface. It allows multiple users to join chat rooms and exchange messages in real-time.

## Requirements

- Python 3.6 or higher
- Flask
- Flask-SocketIO

## Installation

1. Clone this repository or download the source code.
2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## How to Run

1. Navigate to the project directory in your terminal.
2. Run the following command:
   ```
   python app.py
   ```
3. Open a web browser and go to `http://localhost:5000`.

## Functionality

- Users can join a chat room by entering a username and room name.
- Multiple users can join the same room and exchange messages.
- Users can leave the chat room at any time.
- The application displays join/leave messages for all users in the room.

## Project Structure

- `app.py`: The main Flask application file containing the server-side logic.
- `templates/index.html`: The HTML template for the chat interface, including embedded CSS and JavaScript.
- `requirements.txt`: List of required Python packages.

## Customization

You can customize the appearance of the chat interface by modifying the CSS in the `<style>` tag of `index.html`. To add new features or change the behavior of the chat application, you'll need to modify both `app.py` and the JavaScript in `index.html`.

## Limitations and Potential Improvements

- This is a basic implementation and lacks advanced features like user authentication or persistent message storage.
- For production use, you should use a production-ready web server and ensure proper security measures are in place.
- The current implementation uses in-memory storage for rooms and messages, which isn't suitable for large-scale applications.

