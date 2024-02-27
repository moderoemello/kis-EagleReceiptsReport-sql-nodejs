## Description

This project is a comprehensive solution designed to fetch, process, and export data from specific API endpoints to a SQLite database and then generate CSV files based on the processed data. It integrates with the KoronaCloud API to retrieve receipts and product details, logs product codes with their last purchase prices, and supports WebSocket communication for real-time data processing and export.

### Features

- Fetch data from KoronaCloud API endpoints.
- Process and log product details into a SQLite database.
- Generate and export processed data as CSV files.
- Real-time data processing and export through WebSockets.

## Getting Started

### Dependencies

- Node.js
- npm or Yarn
- SQLite3

### Installing

1. Clone the repository to your local machine.
   ```bash
   git clone <repository-url>
   ```
2. Install the required dependencies.
   ```bash
   cd <project-directory>
   npm install
   ```
3. Create a `.env` file in the root directory with the necessary environment variables.
   ```
   KORONACLOUD_USERNAME=<your-username>
   KORONACLOUD_PASSWORD=<your-password>
   ```

### Executing program

1. Start the server.
   ```bash
   npm start
   ```
2. Navigate to `http://localhost:3000/index.html` in your web browser to interact with the application.

## Usage

Describe how to use your application with examples of commands or actions that can be performed. Include any relevant URLs, command line examples, or screenshots.

## Help

Any advise for common problems or issues.
```bash
command to run if program contains helper info
```
