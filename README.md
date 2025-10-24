# Character Sheets

![Character Sheets Logo](https://via.placeholder.com/400x200?text=Character+Sheets+Logo) 

## Project Description

**Character Sheets** is a project designed to observe and analyze how **developers respond to alerts and goals** within a system. By tracking and logging these interactions, it aims to provide deep insights into developer behavior, system engagement, and the effectiveness of different alert and goal-setting mechanisms.

---

## Features

Based on the project structure and commit history, the application includes the following capabilities:

* **Real-time Communication:** Implementation of **Websocket P2P messaging** for seamless, real-time data exchange.
* **Local Data Management:** Support for working with **local, editable character sheets**, likely used to configure or manage developer profiles and observed response data.
* **System Health Monitoring:** A dedicated **healthcheck route** to ensure the backend server remains stable and operational.
* **Web Interface Support:** Utilizes a `public/` directory for static assets, suggesting a web-based interface for interacting with or visualizing the data.

---

## Getting Started

### Prerequisites

To set up and run this project locally, you will need:

* **Node.js** (LTS version recommended)
* **npm** (Node Package Manager)

### Installation

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/ernestogeek/character_sheets.git](https://github.com/ernestogeek/character_sheets.git)
    cd character_sheets
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    ```

### Running the Application (Local Development)

Start the server using the designated command:

```bash
npm start 
# NOTE: If 'npm start' doesn't work, check your package.json for the correct script 
# (e.g., 'npm run dev' or 'node server/index.js').
