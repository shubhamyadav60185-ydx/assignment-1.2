Q1. Install Visual Studio Code.

Answer:

Visual Studio Code (VS Code) is a free source-code editor developed by Microsoft. It is used to write, edit, and debug programs in different programming languages.

Installation Steps:

Visit the official website: https://code.visualstudio.com/

Download Visual Studio Code for Windows.

Run the downloaded installer.

Accept the agreement and follow the installation instructions.

Open Visual Studio Code after installation.

Q2. Install the LTS version of Node.js.

Answer:

Node.js is a JavaScript runtime environment that allows JavaScript code to run outside a web browser. It also includes npm (Node Package Manager), which is used to install and manage packages.

Installation Steps:

Visit https://nodejs.org/

Download the LTS (Long-Term Support) version of Node.js.

Run the installer.

Follow the instructions and keep the default settings.

Complete the installation and restart VS Code if it was already open.

Q3. Install the Live Server and Prettier extensions in VS Code.

Answer:

Live Server and Prettier are useful extensions in Visual Studio Code.

Live Server: It runs an HTML file on a local development server and automatically refreshes the browser when changes are saved.

Prettier: It is a code formatter that automatically formats code to make it clean and readable.

Installation Steps:

Open Visual Studio Code.

Click the Extensions icon or press Ctrl + Shift + X.

Search for Live Server by Ritwick Dey and click Install.

Search for Prettier - Code formatter by Prettier and click Install.

Q4. Create a folder named web-development-practice.

Answer:

A project folder is used to organize all the files related to a website in one place.

Steps:

Create a new folder on the Desktop.

Name the folder web-development-practice.

Open Visual Studio Code.

Select File → Open Folder.

Choose the web-development-practice folder and open it.

Q5. Create index.html, style.css, and script.js files inside the folder.

Answer:

These three files are used to create a basic website.

index.html: Defines the structure and content of the web page.

style.css: Controls the design, colours, spacing, and layout of the web page.

script.js: Adds functionality and interactivity to the web page.

Create these three files inside the web-development-practice folder.

File 1: index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Welcome to Web Development!</h1>
    <p>My development environment is ready.</p>
    <button onclick="showMessage()">Click Me</button>

    <script src="script.js"></script>
</body>
</html>

File 2: style.css

body {
    font-family: Arial, sans-serif;
    text-align: center;
    background-color: #f0f8ff;
    padding: 50px;
}

h1 {
    color: #1565c0;
}

p {
    font-size: 18px;
}

button {
    padding: 10px 20px;
    background-color: #1565c0;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

File 3: script.js

function showMessage() {
    alert("JavaScript is working!");
}

Save all three files using Ctrl + S.

Q6. Run the HTML file in the browser using Live Server.

Answer:

Live Server allows us to run an HTML file on a local development server and view the web page in a browser.

Steps:

Open the web-development-practice folder in VS Code.

Open the index.html file.

Right-click inside the editor.

Select Open with Live Server.

The web page will open in the default browser.

Check that the heading, paragraph, and button are displayed correctly.

Click the button to verify that JavaScript is working.

The browser will usually open a local address similar to http://127.0.0.1:5500/index.html.

Q7. Verify the installation by running node -v and npm -v commands in the terminal.

Answer:

The Node.js and npm installations can be verified using commands in the VS Code terminal.

Steps:

Open Visual Studio Code.

Select Terminal → New Terminal.

Type the following command and press Enter:

node -v

This command displays the installed Node.js version.

Type the following command and press Enter:

npm -v

This command displays the installed npm version.

Example Output:

node -v
v22.x.x

npm -v
10.x.x

The exact version numbers may vary depending on the installed version. If both commands display version numbers, the installation is working correctly.

Result

The web development environment was prepared using Visual Studio Code, Node.js, Live Server, and Prettier. The project folder and three required files were created, the HTML page was run in a browser, and the Node.js and npm installations were verified.

Screenshots Required for Submission

VS Code showing the project folder and three files.

Terminal showing the output of node -v and npm -v.

Browser showing the running HTML page.