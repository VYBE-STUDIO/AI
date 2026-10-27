# FROHEN AI — real AI setup

This project has one frontend file (`public/index.html`) and one backend (`server.js`).
The browser NEVER receives the AI API key.

## Local run
1. Install Node.js.
2. Open this folder in a terminal.
3. Run `npm install`
4. Copy `.env.example` to `.env`
5. Put your AI provider key in `AI_API_KEY`.
6. Run `npm start`
7. Open `http://localhost:3000`

## Deploy
Deploy the whole folder to a Node-capable host such as Render/Railway.
Set the environment variables in the host dashboard:
- AI_API_KEY
- AI_BASE_URL
- AI_MODEL

Do NOT put the API key inside `public/index.html` or commit `.env` to GitHub.
GitHub Pages alone cannot run `server.js`.
