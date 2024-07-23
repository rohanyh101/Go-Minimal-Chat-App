# Simple ChatApp in Go

Welcome to the Simple ChatApp, a lightweight chat application built using the TCP protocol in Go. This application allows users to connect, join rooms, and send messages in real-time.

## Features

- **User Nickname**: Assign a nickname to your connection with the command `/nick <name>`.
- **Room Management**: Create or join chat rooms using `/join <room_name>`.
- **Room Listing**: Display all existing chat rooms with the command `/rooms`.
- **Messaging**: Send messages to the current room with `/msg <message>`.
- **Exit Room**: Leave the current room using `/quit`.

## Getting Started

You can follow these instructions to set up and run the ChatApp on your local machine.

### Prerequisites

- Go (version 1.16 or higher) installed on your machine. You can download it from [golang.org](https://golang.org/dl/).

### Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/chatapp.git
   cd chatapp
   ```

2. Build the application binary:
   ```bash
   go build .
   ```

3. Run the application:
   ```bash
   ./main
   ```

### Connecting to the ChatApp

To connect to the chat application, open another terminal window and use the following command:

```bash
telnet localhost 8080
```

### Usage Instructions

Once connected, you can use the following commands:

- **Set Nickname**: 
  ```
  /nick <name>
  ```
  Example: `/nick Alice`

- **Join a Room**: 
  ```
  /join <room_name>
  ```
  Example: `/join general`

- **List Rooms**: 
  ```
  /rooms
  ```

- **Send a Message**: 
  ```
  /msg <message>
  ```
  Example: `/msg Hello everyone!`

- **Quit the Room**: 
  ```
  /quit
  ```

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please feel free to submit a pull request.

## License

This project is licensed under the MIT License. Please take a look at the [LICENSE](LICENSE.txt) file for details.

## Acknowledgments

Thank you for using the Simple ChatApp! We hope you enjoy chatting with your friends and colleagues.
