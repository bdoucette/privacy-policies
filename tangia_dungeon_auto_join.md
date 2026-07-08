# Privacy Policy for Tangia Dungeon Auto Join

Last updated: July 8, 2026

Tangia Dungeon Auto Join is a Chrome extension that helps users automatically join Tangia dungeon and boss fight events in Twitch chat.

## Single Purpose

The extension’s single purpose is to automatically join Tangia dungeon and boss fight chat events on Twitch when enabled by the user.

## Data Collected

The extension uses the minimum data needed to work:

- Twitch authentication token
- Twitch user identity returned by the Twitch API
- Extension settings saved by the user

The extension does not collect names, email addresses, payment information, browsing history, or personal communications.

## How Data Is Used

The extension uses this data to:

- Sign in with Twitch
- Verify the signed-in Twitch user
- Connect to Twitch chat
- Detect Tangia dungeon or boss fight events
- Send the required Twitch chat message to join the event
- Save extension settings locally

## Data Storage

The Twitch authentication token and extension settings are stored locally using Chrome extension storage.

Data is not sent to any server owned or operated by the extension developer.

## Data Sharing

The extension does not sell, rent, transfer, or share user data with third parties.

The extension communicates only with Twitch services as needed for authentication, user verification, and Twitch chat functionality.

## Remote Code

The extension does not execute remote code.

All executable JavaScript is included in the extension package. Network requests are used only to communicate with Twitch services.

## Permissions Used

### Identity

Used to let the user sign in with Twitch OAuth.

### Storage

Used to save the user’s Twitch authentication token and extension settings locally.

### Offscreen

Used to keep a Twitch chat connection running in the background because Chrome Manifest V3 service workers cannot maintain a persistent WebSocket connection.

### Host Permissions

The extension requests access to:

```text
https://id.twitch.tv/*
https://api.twitch.tv/*
```

These are used only for Twitch OAuth sign-in and Twitch user verification.

User Control

Users can disable or remove the extension at any time from Chrome’s Extensions page.
Users can revoke Twitch authorization from their Twitch account settings.

Contact

For privacy questions, contact:
contact.iffydev@gmail.com
