# Localhost Hot Reloader

Automatically reloads your **localhost** tabs in Chrome when they gain focus, easing your web development workflow.

NOTE: This is a Chrome extension.

## Description

**Localhost Auto-Reloader** is designed to streamline web development by automatically reloading tabs that are running on `localhost` or `127.0.0.1` when they gain focus. This eliminates the need to manually refresh your browser after making changes to your code, allowing for an easier development workflow.

## Features

- **Automatic Reloading**: Reloads localhost Chrome tabs when they gain focus from any other application.
- **Supports Multiple URL Patterns**: Works with `http://localhost`, `https://localhost`, `http://127.0.0.1`, and `https://127.0.0.1`, including any port or subpath.
- **Toggle Reloading On/Off**: Easily enable or disable the reloading behavior using the toolbar button or keyboard shortcut.
- **Keyboard Shortcut**: Use `Ctrl+Shift+R` (Windows/Linux) or `Command+Shift+R` (macOS) to toggle reloading.
- **Debounce Mechanism**: Prevents multiple reloads from overlapping events with a cooldown period.

## Installation

Since this extension is in beta, you need to manually install it in Chrome:

1. Download this repository by clicking in this page's **`<> Code`** (green button) --> **`Download ZIP`**
2. Extract the ZIP file to some location in your computer
2. Open Chrome and navigate to **chrome://extensions/**
3. Enable **Developer mode** by toggling the switch in the upper-right corner
4. Click **`Load unpacked`** button and select the extracted folder
