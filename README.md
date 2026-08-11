# Git & GitHub – Assignment

Welcome to the Git & GitHub hands-on assignment! 🚀

The purpose of this assignment is to practice the basic Git and GitHub workflow learned.

## 🎯 Learning Objectives

By completing this assignment, you will practice:

- Forking a GitHub repository
- Cloning a repository
- Working with a local Git repository
- Checking repository status
- Staging changes using `git add`
- Creating commits using `git commit`
- Pushing changes to GitHub using `git push`
- GitHub authentication

---

## 📋 Assignment Instructions

### Step 1: Fork the Repository

Fork this repository to your own GitHub account.

Click:

**Fork → Create fork**

After forking, you will have your own copy of this repository.

---

### Step 2: Clone Your Fork

Copy the URL of your fork and clone it to your computer.

```bash
git clone <your-fork-url>
```

Example:

```bash
git clone https://github.com/your-username/git-github-day4-assignment.git
```

Then move into the project folder:

```bash
cd git-github-day4-assignment
```

---

### Step 3: Open the Project in VS Code

Run:

```bash
code .
```

---

### Step 4: Go to the `submissions` Folder

Inside the project, you will find a folder named:

```text
submissions
```

Open this folder.

---

### Step 5: Create Your Profile File

Create a new file using your name.

**Format:**

```text
firstname-lastname.txt
```

**Example:**

```text
rahul-sharma.txt
```

---

### Step 6: Add Your Information

Add the following information to your file:

```text
Name: Your Full Name
College: Your College/University Name
Branch: Your Branch
Year: Your Current Year
Skills: HTML, CSS, JavaScript
GitHub: Your GitHub Username
```

**Example:**

```text
Name: Rahul Sharma
College: ABC University
Branch: Computer Science
Year: 1st Year
Skills: HTML, CSS, JavaScript
GitHub: NikhilM512
```

---

## 🔧 Git Commands

After creating your file, open Git Bash inside the project folder.

### 1. Check Repository Status

```bash
git status
```

You should see your newly created file as an untracked file.

---

### 2. Stage Your Changes

```bash
git add .
```

---

### 3. Check the Status Again

```bash
git status
```

Your file should now appear under:

```text
Changes to be committed
```

---

### 4. Commit Your Changes

Use the following commit message:

```bash
git commit -m "Added student profile"
```

---

### 5. Push Your Changes to GitHub

```bash
git push origin main
```

If GitHub asks you to authenticate, complete the GitHub authentication process.

---

## ✅ Final Repository Structure

Your repository should look like this:

```text
git-github-assignment/
│
├── README.md
│
└── submissions/
    │
    └── your-name.txt
```

**Example:**

```text
git-github-day4-assignment/
│
├── README.md
│
└── submissions/
    │
    ├── rahul-sharma.txt
```

---

## 📤 Submission

Submit the URL of your forked GitHub repository to the form shared below.

Google Form - [https://forms.gle/EeWxsz19RomzdDYm7]
**Example:**

```text
https://github.com/your-username/git-github-assignment
```

Google Form:

---

## ⭐ Git Workflow

Remember the workflow:

```text
Fork
  ↓
Clone
  ↓
Modify
  ↓
git status
  ↓
git add .
  ↓
git commit
  ↓
git push
  ↓
GitHub
```

---

## ⚠️ Important Notes

- Do NOT modify or delete other students' files.
- Create only your own profile file inside the `submissions` folder.
- Use your own GitHub account.
- Use a meaningful commit message.
- Make sure your changes are visible on GitHub after pushing.
- Do not share your GitHub password or authentication credentials with anyone.

---

## 🎓 Goal

The goal of this assignment is to understand and practice the basic Git & GitHub workflow:

**Fork → Clone → Modify → Add → Commit → Push**
