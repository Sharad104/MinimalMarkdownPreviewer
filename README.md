# Markdown Editor with Preview

A full-stack Markdown editor built with Node.js, Express, MongoDB, and vanilla HTML, CSS, and JavaScript. The editor allows real-time Markdown preview, file saving, and loading from a MongoDB database.

## Features
- Real-time Markdown Preview
- Save and Open Markdown files
- Simple and lightweight implementation

## Tech Stack
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Markdown Rendering**: Marked.js

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Sharad104/MinimalMarkdownPreviewer
   cd markdown-editor
   ```

2. Install dependencies:

   ```npm install``` 

3. Set up your MongoDB atlas DB or use mine in dotenv ;>.

4. Start the server:

    ```node server.js```

5. Visit http://localhost:3000 in your browser to start using it.

Usage

    Write Markdown in the left editor.
    Preview Markdown on the right.
    Save your Markdown file with a Title.
    Open saved Markdown files by entering the Title.

## Screenshot
![ss1](https://i.postimg.cc/prNSdpnc/mmp.jpg)
Type "githubpreview" in input and click on open ! as "README.md" is deleted from MongoDB.
