# 📝 Task Manager App

A simple and elegant task management application built with **Node.js**, **Express.js**, and **EJS** templating engine. Create, view, and manage your tasks with a beautiful dark-themed UI.

![Task Manager](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![EJS](https://img.shields.io/badge/EJS-B4CA65?style=for-the-badge&logo=ejs&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

## ✨ Features

- 🎨 **Modern Dark UI** - Beautiful dark theme with Tailwind CSS
- 📝 **Create Tasks** - Add tasks with title and detailed descriptions
- 👁️ **View Tasks** - Read individual task details on separate pages
- 📁 **File-based Storage** - Tasks stored as `.txt` files in the filesystem
- 📱 **Responsive Design** - Works on desktop, tablet, and mobile devices
- ⚡ **Fast & Lightweight** - Built with Express.js for optimal performance

## 🚀 Quick Start

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/task-manager-app.git
   cd task-manager-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000`

## 🏗️ Project Structure

```
task-manager-app/
├── files/                  # Task files storage
├── views/                  # EJS templates
│   ├── index.ejs          # Homepage with task list
│   └── show.ejs           # Individual task view
├── public/                 # Static assets
│   ├── stylesheets/
│   └── javascripts/
├── index.js               # Main server file
├── package.json           # Dependencies and scripts
└── README.md              # Project documentation
```

## 🛠️ Tech Stack

- **Backend**: Node.js, Express.js
- **Templating**: EJS (Embedded JavaScript)
- **Styling**: Tailwind CSS
- **Storage**: File System (`.txt` files)
- **Package Manager**: npm

## 📖 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/` | Homepage - Display all tasks |
| `GET` | `/file/:filename` | View individual task |
| `POST` | `/create` | Create a new task |

## 🎯 Usage

### Creating a Task
1. Enter a **title** for your task
2. Add **detailed description** in the textarea
3. Click **"Create Task"** button
4. Task will be saved and appear on the homepage

### Viewing a Task
1. Click **"Read More"** on any task card
2. View the complete task details
3. Use **"Go Back"** to return to the homepage

## 📦 Dependencies

```json
{
  "express": "^4.18.x",
  "ejs": "^3.1.x"
}
```

## 🔧 Development

### Running in Development Mode

```bash
# Install nodemon for auto-restart
npm install -g nodemon

# Start with nodemon
nodemon index.js
```

### Adding New Features

1. **Edit Routes**: Modify `index.js` for new endpoints
2. **Update Views**: Edit EJS templates in `views/` folder
3. **Style Changes**: Update Tailwind classes in templates

## 🚀 Deployment

### Deploy to Heroku

```bash
# Install Heroku CLI
# Create Heroku app
heroku create your-app-name

# Deploy
git push heroku main
```

### Deploy to Vercel

```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel --prod
```

## 🤝 Contributing

1. **Fork** the repository
2. Create your **feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. Open a **Pull Request**

## 📋 Future Enhancements

- [ ] **Database Integration** (MongoDB/PostgreSQL)
- [ ] **User Authentication** 
- [ ] **Task Categories/Tags**
- [ ] **Due Dates & Reminders**
- [ ] **Search & Filter Tasks**
- [ ] **Task Priority Levels**
- [ ] **Export/Import Tasks**
- [ ] **Dark/Light Theme Toggle**

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourprofile)

## 🙏 Acknowledgments

- Built with ❤️ using Express.js
- Styled with Tailwind CSS
- Inspired by modern task management apps

---

⭐ **Star this repo** if you found it helpful!

```bash
# Quick setup commands
git clone https://github.com/YOUR_USERNAME/task-manager-app.git
cd task-manager-app
npm install
npm start
```

**Happy Task Managing! 🎉**
