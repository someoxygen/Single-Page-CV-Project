# Single Page CV Project

This project is a single-page CV built using only HTML. It does not require package installation, a build process, or any server-side technology.

## Project structure

```text
SinglePageCVProject/
├── index.html    # CV page
├── favicon.png   # Favicon displayed in the browser tab
└── README.md     # Project description and setup instructions
```

## Requirements

A modern web browser is all you need to run the project:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

## Running the project

### 1. Open it directly in a browser

After downloading or cloning the project, double-click the `index.html` file in the project directory. The page will open in your default browser.

### 2. Run it with Visual Studio Code

Open the project directory in Visual Studio Code:

```bash
code .
```

Then open `index.html`. If you have the Live Server extension installed, right-click the file and select **Open with Live Server**.

### 3. Run it with a local HTTP server

If Python is installed on your computer, run the following command from the project directory:

```bash
python -m http.server 5500
```

Then open the following address in your browser:

```text
http://localhost:5500
```

To stop the server, press `Ctrl + C` in the terminal.

## Customization

- Personal information, education, and experience can be edited in `index.html`.
- Replace `favicon.png` to update the icon displayed in the browser tab.
- Colors can be changed through the `style` attributes of the relevant HTML elements.

## Technologies used

- HTML5
