# My First Web Page

## Overview
A simple Node.js/Express application that serves a static website featuring the phonetic alphabet A-Z with Indian names. The site includes an interactive alphabet grid with different viewing modes (Indian Names and Phonetic).

## Project Structure
- `server.js` - Express server serving static files and API endpoint
- `index.html` - Main landing page
- `letter.html` - Individual letter page
- `letter.js` - Letter page JavaScript
- `script.js` - Main JavaScript
- `style.css` - Styles
- `alphabets.json` - Client-side fallback data

## Running the Application
The server runs on port 5000 and serves:
- Static files from the project root
- API endpoint at `/api/alphabets` returning alphabet data

## Recent Changes
- 2025-01-01: Configured for Replit environment (port 5000, host 0.0.0.0)
