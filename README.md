# Advanced File Organizer Bot

An intelligent file management tool that automatically organizes files based on type, extension, creation date, or size. Includes a simple GUI for customization and real-time folder monitoring using the `watchdog` library.

## Features

- Automatically sort files into folders by:
  - File type (documents, images, videos, etc.)
  - Extension (`.pdf`, `.jpg`, `.mp4`, etc.)
  - Creation or modification date
  - File size (small, medium, large)
- Real-time monitoring of selected directories
- Configurable GUI toggle panel for organizing preferences
- Logs file operations for review
- Cross-platform support (Windows, macOS, Linux)

## Technology Stack

- **Language**: Python
- **Libraries**:
  - `watchdog` – for real-time file system monitoring
  - `tkinter` – for GUI
  - `os`, `shutil`, `datetime`, `pathlib` – for file operations

