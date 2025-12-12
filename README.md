# CodeSyncer 🚀

A real-time collaborative code editor that enables multiple developers to write, edit, and sync code together seamlessly. Perfect for pair programming, code reviews, and collaborative development sessions.

## ✨ Features

- **Real-time Collaboration** - Multiple users can edit code simultaneously
- **Live Synchronization** - Changes are instantly synced across all connected clients
- **Room-based Sessions** - Create or join coding rooms with unique Room IDs
- **User Presence** - See who's online and actively coding
- **Code Syntax Highlighting** - JavaScript syntax highlighting with Dracula theme
- **Responsive Design** - Works on desktop and mobile devices
- **Toast Notifications** - Get notified when users join or leave sessions

## 🛠️ Technologies Used

### Frontend

- **React.js** - Modern UI library
- **React Router** - Client-side routing
- **CodeMirror** - Code editor with syntax highlighting
- **React Hot Toast** - Beautiful toast notifications
- **React Avatar** - User avatar generation
- **Socket.IO Client** - Real-time WebSocket communication

### Backend

- **Node.js** - JavaScript runtime
- **Express.js** - Web application framework
- **Socket.IO** - Real-time bidirectional communication
- **HTTP Server** - Serves static React build files

### Development Tools

- **ESLint** - Code linting and quality checks
- **React Scripts** - Build and development tools

## 🚀 Quick Start

### Prerequisites

- **Node.js** (v14 or higher)
- **npm** or **yarn** package manager

### Installation

1. **Clone the Repository**

```bash
git clone https://github.com/shreya-2511/CodeSyncer.git
cd CodeSyncer
```

2. **Install Dependencies**

```bash
npm install
```

3. **Start the Application**

```bash
npm start
```

The application will automatically:

- Build the React frontend
- Start the Express server
- Open your browser to `http://localhost:5001`


## 🏗️ Project Structure

```
CodeSyncer/
├── public/                 # Static assets
├── src/
│   ├── components/        # React components
│   │   ├── Client.js     # User avatar component
│   │   └── Editor.js     # CodeMirror editor wrapper
│   ├── pages/            # Page components
│   │   ├── Home.js       # Landing/room creation page
│   │   └── EditorPage.js # Collaborative editor page
│   ├── Actions.js        # Socket.IO event constants
│   ├── socket.js         # Socket.IO client configuration
│   └── App.js           # Main React application
├── server.js             # Express + Socket.IO server
└── package.json         # Dependencies and scripts
```

### Environment Configuration

Create a `.env` file for custom configurations:

```env
REACT_APP_BACKEND_URL=http://localhost:5001
```

## 👨‍💻 Author

**Shreya** - [GitHub Profile](https://github.com/shreya-2511)

---
