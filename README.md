# WhatsApp Baileys Bot

A simple WhatsApp bot using `@whiskeysockets/baileys` with a web interface.

## Features
- QR code authentication via web UI.
- Simple API to send messages.
- No heavy dependencies (no Puppeteer/Chrome required).

## Installation
```bash
npm install
```

## Running the Server
```bash
npm run dev
```

## API
### Send Message
- **URL**: `/api/send-message`
- **Method**: `POST`
- **Body**:
  ```json
  {
    "number": "60123456789",
    "message": "Hello from Baileys!"
  }
  ```

## UI
Open `http://localhost:2178` to authenticate and test sending messages.