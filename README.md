# Chatbot Web Application

An interactive, responsive React chat application built with Vite, featuring message history persistence, real-time message timestamps, auto-scrolling conversation feeds, and simulated AI chatbot responses.

## Features

- **Interactive Chat Interface**: Send and receive messages with user avatar and chatbot avatar presentation.
- **Asynchronous Chatbot Response Simulation**: Simulated asynchronous bot responses with loading indicators while waiting for response generation.
- **Persistent Message Storage**: Save chat messages locally using browser `localStorage` so conversation history is retained across sessions.
- **Timestamping & Formatting**: Date and time formatting powered by `dayjs`.
- **Auto-Scrolling Chat Feed**: Automatically scrolls to the newest message whenever new interactions occur.
- **Clear Conversation**: Easily clear current session messages with one click.

## Tech Stack

- **Frontend Library**: React 18
- **Build Tool / Bundler**: Vite
- **Utilities**: Day.js (date and time formatting)
- **Deployment**: Static Web Hosting (configured for GitHub Pages base path)

## Project Structure

```text
.
├── index.html           # Main HTML entry point
├── vite.svg             # Project Vite logo icon
├── assets/              # Built JavaScript, CSS, and image assets
│   ├── index-CZGIrnRX.js   # Application JS bundle
│   ├── index-Bw3neSCD.css  # Application stylesheet
│   ├── bedru-BGfpzO3k.jpg  # User profile avatar
│   ├── robot-C7KxgfIL.png  # Chatbot avatar
│   └── loading-spinner-BauQUFIa.gif # Loading spinner asset
└── README.md            # Project documentation
```

## Running Locally

To serve the application locally using any standard static web server:

1. Clone the repository:
   ```bash
   git clone https://github.com/bedrumekiyu/chatbot-project.git
   cd chatbot-project
   ```

2. Start a local HTTP server:
   ```bash
   python3 -m http.server 8000
   ```

3. Open `http://localhost:8000` in your web browser.

## CI/CD Workflow

The repository includes GitHub Actions automated workflows (`.github/workflows/ci.yml`) to validate repository structure, HTML integrity, and asset presence on every commit and pull request.
