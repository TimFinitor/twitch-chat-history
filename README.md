# Twitch Chat History

A userscript that enhances Twitch chat by allowing you to view a user's recent chat history with Alt+Click on their username.

## Features

- View any user's chat history by Alt+clicking their username
- Draggable history modal with recent messages
- Configurable settings (shortcut key, history size)
- FrankerFaceZ integration for easier configuration

## How It Works

- Captures chat messages in real-time by intercepting Twitch's WebSocket connections
- Stores messages in memory locally (no server interaction)
- Uses DOM observation to detect and process all chat messages
- All data remains in your browser - nothing is sent externally

## Installation

1. Install a userscript manager like [Tampermonkey](https://www.tampermonkey.net/) or [Violentmonkey](https://violentmonkey.github.io/)
2. Install this script from [GitHub](https://github.com/TimFinitor/twitch-chat-history/raw/refs/heads/main/twitch-chat-history.user.js)
3. Visit any Twitch stream

## Usage

- Hold Alt and click on any username in chat to see their message history
- Press Ctrl+H to search for a specific username
- Drag the history window to reposition it
- If you have FrankerFaceZ installed, you can configure settings in FFZ control panel

## Notes

- The script can only capture messages while it's running and on the current stream
- Message history is not saved between page refreshes or streams
