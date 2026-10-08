# QuickNotes

QuickNotes is a simple note-taking web app built with HTML, CSS and JavaScript. You can write short notes, sort them into categories, search through them and delete them, and your notes are saved in the browser so they are still there after a refresh.

## Features

- Add notes of up to 200 characters
- Choose a category: Personal, Work or Study
- Each category has its own coloured card border
- Delete any note
- Search notes as you type (not case-sensitive)
- Validation messages for empty or too-long notes
- Note counter that handles zero, one and many notes
- Notes saved with localStorage and restored when the page opens
- Responsive layout for small screens

## How to run locally

1. Clone the repository:
   `git clone https://github.com/SWNgugi/quicknotes-app.git`
2. Open the `quicknotes-app` folder in VS Code.
3. Right-click `index.html` and choose **Open with Live Server**, or simply open `index.html` in your browser.

## What I learned

- How to structure a page using semantic HTML and correctly associate labels with form inputs.
- How to use Flexbox to create responsive form layouts that stack on smaller screens using media queries.
- How to dynamically create elements with createElement and textContent, providing a safer alternative to innerHTML when handling user-generated text.
- How to store and retrieve data using localStorage, JSON.stringify(), and JSON.parse().
- How to break development into small, manageable steps and make clear Git commits throughout the process.
