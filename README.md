# Leandro Belli - CV

This repository hosts the source code and data for my Curriculum Vitae.

## Structure

- **`docs/`**: This directory contains the website files, capable of being served by GitHub Pages.
  - **`cv-data.js`**: Contains all the CV content in a structured JSON format (English and Spanish).
  - **`index.html`**: The main entry point that renders the CV using the data file.
  - **`style.css`**: Styles for the CV layout.

## How it Works

The CV is built as a static site. `index.html` loads `cv-data.js` and dynamically populates the page based on the selected language.

## Language Support

- **English (Default)**: Loaded by default.
- **Spanish**: Accessible via the language toggle button.

## Editing

To update the CV content, edit the `docs/cv-data.js` file. The structure separates English (`en`) and Spanish (`es`) content.
