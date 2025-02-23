# Multi-Chat Server

A simple chat application that allows users to send messages and files between connected clients.

## Features

- Real-time messaging between connected clients
- File transfer capabilities
- Persistent connections
- Custom username support

## Installation

1. Clone the repository or download the source files
2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage

### Starting the Chat

1. Open a terminal and start the first chat instance:
```bash
python chat.py [YOUR_NAME]
```
Note: `[YOUR_NAME]` is optional. If not provided, the program can run without a custom name.

2. Open another terminal and start the second chat instance:
```bash
python chat.py
```

3. Follow the console instructions to establish connections and send/receive messages

### Important Notes

- The first chat program needs to be running for the second to send files or messages
- The program continues running even after connections are closed
- File transfers are processed in 1KB segments for efficient handling
