# Easy Git and GitHub Guide for Beginners 🌟

Welcome! This guide is brought to you by the **GDG OC Kabarak Leads**. We'll teach you Git and GitHub in simple steps. Git helps you keep track of changes in your code, like a time machine for your files. GitHub lets you share your code online and work with others. Let's get started! 🚀

## Table of Contents
- [What is Git?](#what-is-git)
- [Installing Git](#installing-git)
- [Setting Up Git](#setting-up-git)
- [Git Basics](#git-basics)
- [What is GitHub?](#what-is-github)
- [Creating a GitHub Account](#creating-a-github-account)
- [Your First Project Example](#your-first-project-example)
- [Sharing Your Code](#sharing-your-code)
- [Helpful Tips and Resources](#helpful-tips-and-resources)

## What is Git? 🤔
Git is like a save button for your project. Every time you make changes to your files, you can "commit" them with Git. If something goes wrong, you can go back to a previous version. Git also lets many people work on the same project at the same time without messing up each other's work.

## Installing Git 🛠️
Git works on Windows, Mac, and Linux. Here's how to install it:

### Windows
1. Go to [git-scm.com](https://git-scm.com) and download Git.
2. Open the downloaded file and install it like any other program.

### Mac
1. Open your Terminal app.
2. Copy and paste this command and press Enter: `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
3. Wait for it to finish, then type: `brew install git`

### Linux (Ubuntu)
1. Open your Terminal.
2. Type this command: `sudo apt update && sudo apt install git`

To check if Git installed correctly, type `git --version` in your Terminal and press Enter. You should see the Git version number.

## Setting Up Git 👤
Before using Git, tell it who you are:
```
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
Replace "Your Name" and "your.email@example.com" with your real name and email.

## Git Basics 🎯

### Starting a Project
1. Create a new folder for your project (like "my-first-project").
2. Open Terminal/Command Prompt and go to that folder.
3. Type `git init` to start tracking your files.

### Making Changes
1. Create or edit files in your project folder.
2. Type `git add .` to stage your changes (prepare them for saving).
3. Type `git commit -m "My first changes"` to save your changes. The message in quotes describes what you did.

### Checking Your Work
- `git status` - See what files have changed.
- `git log` - See all your save points (commits).

### Undoing Mistakes
- `git checkout -- filename` - Undo changes to a specific file.

## What is GitHub? 🌐
GitHub is like a cloud storage for your Git projects. It's where developers share their code, find cool projects, and work together with friends from anywhere. GitHub makes it easy to show your work and contribute to other's projects.

## Creating a GitHub Account 📝
1. Visit [github.com](https://github.com) in your web browser.
2. Click the green "Sign up" button.
3. Pick a username, enter your email, and create a password.
4. Verify your email when asked.
5. Done! 🎉

## Your First Project Example 📚
Let's create a simple website and put it online. Follow these steps:

### Step 1: Create Your Project Folder
- On your computer, create a new folder called "my-website".
- Open this folder in a code editor (like VS Code).

### Step 2: Add a File
Create a file named `index.html` and add this code:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Website</title>
  </head>
  <body>
    <h1>Hello, World!</h1>
    <p>This is my website on GitHub!</p>
  </body>
</html>
```

### Step 3: Save with Git
- Open Terminal/Command Prompt in your project folder.
- Type these commands one by one:
  ```
  git init
  git add .
  git commit -m "Add my first website"
  ```

## Sharing Your Code 🚀
Now let's put your project on GitHub so others can see it!

### Step 1: Create a Repository
1. Log in to GitHub.
2. Click the "+" in the top right, choose "New repository".
3. Name it "my-website" or whatever you want.
4. Make it public (free and anyone can see it).
5. Don't add anything else, click "Create repository".

### Step 2: Connect and Upload
- GitHub will show you commands. Copy and paste them:
  ```
  git remote add origin https://github.com/your-username/my-website.git
  git branch -M main
  git push -u origin main
  ```
  Replace "your-username" and "my-website" with your actual names.

- That's it! Your website is now online. Click on the repository name to view it.

### Step 3: Make Changes
Want to update your website?
1. Edit the `index.html` file.
2. Save with: `git add . && git commit -m "Updated website"`
3. Upload with: `git push`
4. Check your GitHub page - the changes are live! ✨

## Helpful Tips and Resources 💡

### Common Git Commands
- `git status` - Check what changed
- `git add .` - Stage all changes
- `git commit -m "message"` - Save changes
- `git log` - See history
- `git push` - Upload to GitHub

### Tips for Beginners
- Commit often with clear messages like "Add login form" or "Fix bug in header".
- Use branch names like "new-feature" or "bug-fix".
- Read error messages carefully - they help you learn!
- Don't be afraid to experiment - Git lets you undo mistakes.

### Next Steps
- Learn about branches to work on new features safely.
- Explore GitHub pages to host your website for free.
- Follow other developers and star projects you like.

### More Resources 📖
- [Git Official Guide](https://git-scm.com/book/en/v1/Getting-Started)
- [GitHub Hello World](https://guides.github.com/activities/hello-world/)
- [GitHub Desktop App](https://desktop.github.com/) - Easier tool for beginners
- [FreeCodeCamp Git Tutorial](https://www.freecodecamp.org/news/git-and-github-for-beginners/)
- Join communities like GitHub Discussions or Reddit's r/programming for help.

## Need Help? 🤝
If you run into problems or have questions while following this guide, contact us via WhatsApp:

- **Lead Hope**: [0796359700](https://wa.me/254796359700)
- **Baraka**: [0111314041](https://wa.me/254111314041)
- **Edwin Wanyoike**: [0725712668](https://wa.me/254725712668)
- **Kelvin**: [0768898624](https://wa.me/254768898624)

We're here to help! 😊

Happy coding! If you have questions, ask in any coding community. Everyone started somewhere! 🌟
