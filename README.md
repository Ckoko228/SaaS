# ⚡ SaaS Messenger

SaaS Messenger is a simple web-based messaging application with a modern dark interface.

The project is created as a SaaS-style messenger where users can enter their name, send messages and communicate through a simple chat interface.

## 🚀 Features

- 💬 Send and display messages
- 👤 Custom username
- ⚡ Real-time messaging with Supabase
- 🎨 Modern dark interface
- 📱 Responsive design
- ☁️ Cloud database integration
- 🔄 Messages can be updated without reloading the page

## 🛠 Technologies

The project uses:

- **HTML5**
- **JavaScript**
- **Tailwind CSS**
- **Supabase**
- **Supabase JavaScript Client**

Tailwind CSS and Supabase are connected through CDN, so no complicated installation is required.

## 📂 Project Structure

```text
SaaS/
│
├── Saas/
│   ├── index.html
│   └── ...
│
└── README.md
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Ckoko228/SaaS.git
```

Open the project folder:

```bash
cd SaaS/Saas
```

Then open the main HTML file in your browser.

You can also use the **Live Server** extension in Visual Studio Code.

## ☁️ Supabase Setup

The project uses Supabase as a backend service.

To use your own Supabase project:

1. Create a project at [Supabase](https://supabase.com/).
2. Create the required database table for messages.
3. Get your **Project URL** and **Anon Key**.
4. Add them to the project configuration.
5. Enable the required database permissions.

Example:

```javascript
const supabaseUrl = "YOUR_SUPABASE_URL";
const supabaseKey = "YOUR_SUPABASE_ANON_KEY";

const supabase = window.supabase.createClient(
    supabaseUrl,
    supabaseKey
);
```

> Do not publish private or service-role keys in the repository.

## ▶️ Running the Project

No Node.js installation is required for the basic frontend version.

Simply open:

```text
index.html
```

Or start it using **Live Server** in VS Code.

## 🎯 Project Purpose

The purpose of this project is to practice the development of a modern SaaS web application and learn how to work with:

- frontend development;
- cloud databases;
- real-time data;
- JavaScript;
- Supabase;
- responsive user interfaces.

## 🔮 Future Improvements

Possible improvements:

- User registration and login
- Private chats
- User avatars
- Message editing and deleting
- Online/offline status
- Chat rooms
- File and image sharing
- Message timestamps
- Better mobile interface

## 👨‍💻 Author

**Daniel Gvirdzhishvili**

GitHub: [Ckoko228](https://github.com/Ckoko228)

## 📄 License

This project was created for educational purposes.
