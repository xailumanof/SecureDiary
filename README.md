# SecureDiary
Description
Personal Encrypted Diary is a secure, encrypted personal diary app that lets you create, edit, and view entries, add images, mark moods and tags, and view weather via the OpenWeatherMap API.

Main functions
🔐 Encryption of all data using Fernet (AES-128)
📝 Create and edit records with formatting
🌦️ Display current weather (OpenWeatherMap API key required)
📷 Add images from the clipboard (Ctrl+V)
🔍 Search and filter records by date, tags and content
📅 Calendar with marks of days when records were made
🎨 Customizable interface (design themes)
🔄 Backup and restore data
📤 Export records to a text file
🚨 Emergency delete function for all data

**First launch**
When you first launch the program:
Will ask you to select a folder to store data
Will ask you for the OpenWeatherMap API key (can be skipped)
Will ask you to create a password to access the diary

**Usage**
Main elements interface:
New entry - create a new diary entry
All entries - view, search and filter existing entries
Settings - change password, theme, backup
Hot keys:
Ctrl+V - paste image from clipboard
Esc - close full-screen image view

**Security**
All data is stored encrypted using:
Scrypt algorithm for generating a key from a password
AES-128 encryption via Fernet
Salts to protect against rainbow table attacks

**License**
This project is distributed under the MIT license. 

