---
# Live Chat Web Application

## Overview

This is a simple real-time chat application built using Flask and SocketIO. Users can create or join chat rooms, send and receive messages in real time. The application features basic functionalities such as creating and joining rooms, sending messages, and displaying message history.



https://github.com/user-attachments/assets/a244edc6-4ae2-4fe6-a6de-c9b6db8b875d



## Features

- **Create a Room:** Users can generate a unique room code and create a new chat room.
- **Join a Room:** Users can join an existing chat room using a room code.
- **Real-Time Messaging:** Messages are sent and received in real time using SocketIO.
- **Message History:** Chat history is maintained and displayed when a user joins a room.

## Technologies

- **Flask:** A micro web framework for Python.
- **SocketIO:** A library for real-time web applications.
- **HTML/CSS:** For creating the web interface.
- **JavaScript:** For handling real-time messaging on the client side.

## Setup

### Prerequisites

- Python 3.x
- Flask
- Flask-SocketIO

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/chat-app.git
   cd chat-app
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```bash
   pip install flask flask-socketio
   ```

4. Run the application:
   ```bash
   python main.app
   ```

   The application will start and be available at `http://localhost:5000`.

## Usage

1. **Create a Room:**
   - Enter your name and click the "Create a Room" button.
   - A unique room code will be generated, and you will be taken to the chat room.

2. **Join a Room:**
   - Enter your name and the room code in the respective fields.
   - Click the "Join a Room" button to enter the chat room.

3. **Send and Receive Messages:**
   - Type a message in the input field and press "Enter" or click the "Send" button to send it.
   - Messages from other users will appear in real-time in the chat window.

## Files

- `main.app`: Main application file containing the Flask and SocketIO setup.
- `base.html`: Base HTML template with common layout and styles.
- `home.html`: Template for the home page where users can create or join rooms.
- `room.html`: Template for the chat room interface.
- `style.css`: Stylesheet for styling the application.

## Contributing

Feel free to fork the repository and submit pull requests. Issues and feature requests can be reported via GitHub issues.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
