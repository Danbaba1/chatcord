# ChatCord App

A real-time chat application built with Node.js, Express, Socket.IO, and Moment.js that allows users to join different rooms and communicate with each other.

## Features

- Real-time messaging
- Multiple chat rooms based on programming languages
- User join/leave notifications
- Current active users list
- Clean and responsive UI
- Auto-scroll to latest messages

## Technologies Used

- **Node.js** - Runtime environment
- **Express** - Web application framework
- **Socket.IO** - Real-time communication
- **Moment.js** - Time formatting
- **QS Library** - Parse query strings
- **Font Awesome** - Icons

## Installation

1. Clone the repository
```bash
git clone https://github.com/Danbaba1/chatcord.git
```

2. Install dependencies
```bash
cd chatcord
npm install
```

3. Run the server
```bash
npm start
```

4. Access the application
```
Open http://localhost:3000 in your browser
```

## Usage

1. Enter your username
2. Select a chat room (JavaScript, Python, PHP, C#, Ruby, or Java)
3. Start chatting!

## Features Explanation

- **Real-time Communication**: Uses Socket.IO for instant message delivery
- **Room Selection**: Users can join different programming language rooms
- **User Status**: Notifications when users join or leave the chat
- **Active Users List**: Shows all current users in the room
- **Responsive Design**: Works on both desktop and mobile devices

## Application Structure

```
chatcord/
├── public/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── main.js
│   ├── chat.html
│   └── index.html
├── utils/
│   ├── messages.js
│   └── users.js
├── server.js
└── package.json
```

## Configuration

The server runs on port 3000 by default, but you can modify this by setting the `PORT` environment variable:

```bash
PORT=8000 npm start
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

Twitter - [@iamdanbaba](https://x.com/iamdanbaba)
Project Link - [https://github.com/Danbaba1/chatcord](https://github.com/Danbaba1/chatcord)

## Acknowledgments

- Socket.IO Documentation
- Express.js Documentation
- Font Awesome Icons
