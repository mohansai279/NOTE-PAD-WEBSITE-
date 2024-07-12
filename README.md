# NOTE-PAD-WEBSITE-
# Note Taking Website

## Overview
This repository contains the code for a simple note-taking web application. The primary file, `note.html`, provides a user interface for creating, editing, and deleting notes. The notes are stored in the browser's local storage, allowing users to retain their notes even after refreshing the page or closing the browser.

## Features
- **Add Notes**: Users can add new notes by clicking the "Add Note" button.
- **Edit Notes**: Users can type directly into the text areas to edit their notes. Changes are saved automatically.
- **Delete Notes**: Users can delete notes by clicking the delete button (✖) located at the top-right corner of each note.
- **Persistent Storage**: Notes are saved in the browser's local storage, so they persist across sessions.

## File Details

### note.html
The `note.html` file includes the following sections and features:

- **HTML Structure**:
  - The document uses HTML5 and includes meta tags for character set and viewport settings.
  - The title of the page is set to "Note Taking Website".

- **CSS Styling**:
  - The body has a dark violet background color and uses Arial, sans-serif as the font.
  - The header section is styled to display a title and an "Add Note" button, with a darker violet background color.
  - The note section is styled to be left-aligned and contains text areas for note input.
  - Each note is styled with a border, padding, and a fixed width, and contains a delete button positioned at the top-right corner.

- **JavaScript Functionality**:
  - **addNote()**: Adds a new note to local storage and reloads the notes.
  - **getNotesFromLocalStorage()**: Retrieves notes from local storage.
  - **loadNotes()**: Loads notes from local storage and displays them in the note section.
  - **deleteNoteAndReload(index)**: Deletes a note at the specified index and reloads the notes.

## Usage
To use the note-taking application, open the `note.html` file in a web browser. You can add, edit, and delete notes, and your notes will be saved in the browser's local storage.

## Screenshot
![NOTE](https://github.com/user-attachments/assets/608ff74e-44a3-434a-9d61-14a442e40cae)

