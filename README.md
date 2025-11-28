# Discord Bot Goals

## 1. Core Functionality
- **Translate Messages:**  
  The bot should be able to translate any given text message into **English** using a translation API (e.g., Google Translate, DeepL, or LibreTranslate).

## 2. Command Design
- **Command Name:** `/translate`
- **Parameters:**
  - `text` → The message to translate.
- **Behavior:**
  - The bot translates the provided message into English.
  - The result should be visible **only to the user** who executed the command (ephemeral response).

## 3. Example Flow
1. User types:  
   `/translate text: "Guten Morgen! lang: EN"`
2. Bot responds (ephemeral):  
   `Translation: "Good morning!"`

## 5. Required Libraries / APIs
- `discord.js` v14+
- Translation API:
  - `deepl-node`
