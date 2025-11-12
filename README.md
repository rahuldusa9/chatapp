## Realtime Chat App

A real-time chat application whose style is heavily inspired by WhatsApp. Built using the MERN Stack (`MongoDB`, `Express.js`, `React`, `Node.js`) with `Firebase` for file storage and `Socket.IO` for instant messaging.

> [!WARNING]
> Messages sent in direct messages and group chats are **_not encrypted_** and are stored as **_plain text_** in the database. **DO NOT share** sensitive information, such as passwords, financial details, or any private data that you use in other applications or accounts. Use this chat app only for the purpose of previewing a demo application.

````markdown
## Realtime Chat App

This is a live chat demo patterned after the look-and-feel of WhatsApp. It uses the MERN stack (MongoDB, Express, React, Node) with Firebase for file uploads and Socket.IO to power real-time messaging.

> [!WARNING]
> Messages exchanged in direct chats and groups are stored as plain text (they are not end-to-end encrypted). Avoid sharing passwords, bank details, or other private data in this demo — treat it as a preview environment only.

### 🚩 Live demo

Try the deployed app here: [https://realtime-chat-app-one-topaz.vercel.app](https://realtime-chat-app-one-topaz.vercel.app)

> [!NOTE]
> On free hosting plans the first request can be slow because instances may be idle and need to wake up. If the page shows a loader it can take ~30–60s before the site becomes responsive.

### ✨ What it does

- Create an account and sign in
- Populate your profile on first login
- Edit and update your profile later
- Send friend requests to add contacts
- Accept or decline incoming friend requests
- Create group conversations and invite members
- Chat live with friends in 1:1 or group rooms
- Share images and arbitrary files in chats
- Filter the chat list (all / DMs / groups)
- Search your chats and friend requests
- Inspect a contact's info: contact details, mutual groups, and files shared between you
- Inspect group details: creation date, member list, and files shared

### ⚙️ Environment setup

Create a `.env` inside the `server` folder with these variables:

```
PORT=3001
JWT_KEY="YOUR_JWT_KEY"
ORIGIN="http://localhost:3000"
DATABASE_URL="YOUR_DATABASE_URL"
PEPPER_STRING="YOUR_PEPPER_STRING"
```

Then create a `.env` in the `client` folder:

```
VITE_FIREBASE_API_KEY="YOUR_API_KEY"
VITE_FIREBASE_AUTH_DOMAIN="YOUR_AUTH_DOMAIN"
VITE_FIREBASE_PROJECT_ID="YOUR_PROJECT_ID"
VITE_FIREBASE_STORAGE_BUCKET="YOUR_STORAGE_BUCKET"
VITE_FIREBASE_MESSAGING_SENDER_ID="YOUR_MESSAGING_SENDER_ID"
VITE_FIREBASE_APP_ID="YOUR_APP_ID"
VITE_SERVER_URL="http://localhost:3001"
```

### 🏃 Local development

Run the server:

```bash
cd server
npm install
npm run dev
```

Start the client:

```bash
cd client
npm install
npm run dev
```

Open `http://localhost:3000` in your browser to view the app.

### 📷 Screenshots

`SIGNING UP & SIGNING IN:`
![signup](https://github.com/user-attachments/assets/9f656b5b-bdd6-42be-9293-e44f52ca0359)
![signin](https://github.com/user-attachments/assets/7f9e478c-c802-437d-acae-10794bf12392)

`SETTING UP YOUR PROFILE:`
![profile-landing](https://github.com/user-attachments/assets/25656c2d-9dcf-4f11-a242-b8e90745a84f)

`SENDING & VIEWING FRIEND REQUESTS:`
![send-friend-request](https://github.com/user-attachments/assets/3e5d6bd1-5110-4452-8c73-4d159661719d)
![friend-requests](https://github.com/user-attachments/assets/a81c0290-ff62-4f01-9792-de9be3ff30af)

`DIRECT MESSAGING:`
![start-new-chat](https://github.com/user-attachments/assets/95dada0c-b57f-438f-87ec-b7c219b18880)
![chats](https://github.com/user-attachments/assets/5ca65d19-c537-419e-984d-533a7d939aaf)

`GROUP MESSAGING:`
![create-group](https://github.com/user-attachments/assets/cae7f705-9665-4c32-973b-c3fd89d75c60)
![group-chat](https://github.com/user-attachments/assets/8c070f09-e482-47de-8b48-d059f453b6b6)

`SEARCH FUNCTIONALITY:`
![search-chats](https://github.com/user-attachments/assets/a01e754f-8a12-4b95-abcb-d4060a8a9a0d)

`UPDATING YOUR PROFILE:`
![profile-update](https://github.com/user-attachments/assets/858fc66f-5e2d-4ae6-b2a8-ea5b00315501)

`VIEWING FRIEND & GROUP PROFILE:`
![friend-info](https://github.com/user-attachments/assets/c577cda1-1f15-4c74-a367-73661c56a5bc)
![group-info](https://github.com/user-attachments/assets/bcb770e9-aea9-4b42-bcfd-02ae935d19fd)

````
