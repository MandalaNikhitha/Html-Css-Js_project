About NOTES APP PROJECT OVERVIEW
__________________________________________

 HTML CODE

* `<!DOCTYPE html>` → Declares the document type as HTML5.
* `<html lang="en">` → Wraps the page content and sets the language to English.
* `<head>` → Contains page metadata and links:

  * `<meta charset="UTF-8">` sets text encoding.
  * `<meta name="viewport"...>` makes it responsive for all devices.
  * `<link rel="stylesheet" href="...font-awesome.css">` imports Font Awesome icons.
  * `<link rel="stylesheet" href="style.css">` links the custom CSS file.
  * `<title>` sets the browser tab title as “Notes App.”
* `<body>` → Holds visible content:

  * `<button class="add" id="add">` creates a button with a **plus** icon (`<i class="fas fa-plus"></i>`) to add a new note.
* At the bottom, scripts are loaded:

  * `marked.min.js` helps render markdown text.
  * `script.js` contains the app’s custom JavaScript login
__________________________________

JAVA SCRIPT CODE
* This JavaScript code works with the HTML **Notes App** to handle adding, editing, deleting, and saving notes.

* **`<button id="add">`** → Triggers `addNewNote()` when clicked.
* **`<div class="note">`** → Each note container, created dynamically.
* **`<div class="tools">`** → Holds the **Edit (`<button class="edit">`)** and **Delete (`<button class="delete">`)** buttons.
* **`<div class="main">`** → Displays formatted note content (markdown).
* **`<textarea>`** → Allows typing/editing the note text.
* **`localStorage`** → Stores notes as JSON so they remain after reloading the page.

The script switches between `<textarea>` and `<div class="main">` for editing and uses **Font Awesome icons (`<i>` tags)** for buttons.
__________________________
STYLE CSS CODE








