# Shutdown Scheduler

An Electron-powered desktop app for scheduling automated shutdown and reboot tasks. Built with Vite, React, and TypeScript, it supports Windows, Linux, macOS, and Unix-like systems. The app uses Task Scheduler on Windows and Cron jobs on Linux/Unix for seamless, platform-specific automation.

## Screenshots

![Main Screen](demo.png)
*Main interface.*

## Features

- **Flexible Scheduling**: Set shutdowns or reboots to occur once, daily, or weekly.
- **Task Management**: Enable, disable, delete individual or all tasks.
- **Cross-Platform**: Compatible with Windows, Linux, Unix-like systems, and macOS.
- **User-Friendly**: Tasks managed via JSON, keeping a record of all scheduled activities.
  
## Technologies

- **Electron** for cross-platform desktop functionality
- **Vite** for fast development and bundling
- **Tailwind** for a modern responsive UI
- **TypeScript** for type safety
- **React** for a fast UI

## Prerequisites

- **Node.js** and **npm**
- **Electron**

## Setup

1. Clone the repository and install dependencies:

   ```bash
   git clone <repo-url>
   cd shutdown-scheduler
   npm install
   ```

2. **Run the app in development mode**:

   ```bash
   npm run dev
   ```

3. **Build for production**:

   ```bash
   npm run build
   ```

## Usage

- **Set up tasks**:
  - Define your task schedule type (once, daily, or weekly), action (shutdown/reboot), and timing options.
- **Enable/Disable**: Manage tasks through the app, adjusting schedules as needed.

## Platform-Specific Details

- **Windows**: Utilizes Windows Task Scheduler to set up shutdown/reboot tasks.
- **Linux/Unix/macOS**: Uses Cron jobs for scheduling tasks.

## License

This project is licensed under the MIT License.

---

Enjoy automated scheduling with customizable options across platforms!