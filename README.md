# Roblox‑Style Chat (Open Source)

A simple, open‑source web chat inspired by the classic Roblox chat UI.  
Messages are stored on a PythonAnywhere backend and can be viewed or sent through public API endpoints.

This project includes:

- A Roblox‑style web chat interface (HTML + CSS + JavaScript)
- A PythonAnywhere Flask backend
- Persistent message storage
- Public API endpoints for sending and reading messages

---

## 📡 API Endpoints

### 🔹 Read chat history  
Returns the latest 50 messages.
https://boom2002.pythonanywhere.com/history
POST https://boom2002.pythonanywhere.com/chat
Content-Type: application/json
 {
  "username": "YourName",
  "message": "Hello world!"
}
 

