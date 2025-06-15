# 🌿 makeGreen

**makeGreen** is a Node.js script that fakes GitHub contribution history by making backdated commits. Whether you're looking to make your GitHub profile look active or create unique patterns on your contribution graph, this tool helps you "go green."

## 🚀 About

**makeGreen** enables you to:
- Generate commits for any date in the past
- Fill up your contribution graph for visual appeal
- Create artistic patterns using custom commit strategies

## 📦 Getting Started

Follow the steps below to set up and run the project:

### 1. Clone this repository

```bash
git clone https://github.com/itzpa1/makeGreen.git
cd makeGreen
```

### 2. Initialize a new Node.js project

```bash
npm init -y
```

### 3. Install dependencies

```bash
npm install moment simple-git random
```

### 4. Add your commit logic

Ensure you have:
- A JavaScript file (`index.js`) to handle commit logic
- A JSON file to define the commit dates or patterns

> ⚙️ If you're using a prewritten `index.js`, you can skip this and directly run the script.

## ▶️ Running the Script

After setting everything up, simply run:

```bash
node index.js
```

This will start generating the commits as per your script.

## 🎥 Video Tutorial

For a complete walkthrough, check out the original tutorial that inspired this project:  
[Watch here](https://www.youtube.com/watch?v=G-EGDH50hGE)

## 🛠️ npm Modules Used

- [`moment`](https://www.npmjs.com/package/moment): Date and time manipulation
- [`simple-git`](https://www.npmjs.com/package/simple-git): Git commands with JavaScript
- [`random`](https://www.npmjs.com/package/random): Generate random values

## 💡 Room for Improvement

- Create text or pixel art with commit patterns
- Add configuration for commit density
- Automate pattern generation using input strings

## 🙌 Credits

Inspired by [Akshay Saini](https://github.com/akshaymarch7)'s original idea and tutorial.
