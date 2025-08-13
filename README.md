# SushiBox
SushiBox is a complete voice and text chat program with a modern UI, client and server. It features encrypted voice chat, text chat, and avatar support with a straightforward launcher.

Key Features: Dual Operation:

Server Mode: Hosts voice chats, client management, audio mixing.

Client Mode: Instances the servers to participate in voice/text communication

Key Features:

Secure real-time voice communication with AES-256 encryption

Text chat with message history

User avatars with image support (PNG/JPG)

Client management (view associated users, traffic stats)

Server-side audio mixing for multi-user chats.

Tech Highlights:

PyAudio for processing audio

Threaded socket networking.

AES-CBC encryption with cryptography library

Numpy audio mixing

JSON messaging protocol

UI/UX Features:

Several color schemes (Dark, Light, Blue, Green)

Bilingual support (Eng/Rus)

System tray notifications

Developer info panel with logs

Draggable update box

Responsive interface with hover effects

Update System:

Automatic update checks

Progress-tracking downloader

One-click installation

Version control with GitHub

Additional Parts:

Launcher with mode options

Settings manager (language/theme)

Error logging with crash reports

Traffic monitoring

Personalizing avatars

Tech Stack:

Tkinter GUI with custom themes

Networking: Python sockets

Audio: PyAudio, NumPy

Encryption: AES-256-CBC (cryptography)

Image Processing: PIL/Pillow

Updates: Requests, Zipfile, Tempfile

Usage Flow:

Start the app via LauncherUI.

Choose to run as server or client

Server: Hosts on port 12345 by default

Client: Define server IP/port and username

Voice/text chat with encryption The app employs robust error handling, extensive logging, and modular architecture with segregation of UI, business logic, and network modules. Flat UI is minimalistic and in accordance with contemporary standards for chat applications with low system resource usage.
