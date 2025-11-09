# Vis Hva Du Kan (Show What You Can)

Assignment 1 - Kodehode: HTML and CSS Fundamentals

## Project Description

This project is a simple website built using fundamental HTML and CSS skills. The goal is to demonstrate understanding of basic web development concepts including HTML structure, CSS styling, and proper use of classes and IDs.

NOTE: sometimes an element will have an id or class tag which dont exist. that is because i use these tags as a makeshift header / name for the element.

NOTE: all css related to buttons in any way should be in buttons.css

## Assignment Requirements

### HTML Structure

-   Create a simple website with essential HTML elements
-   Use Emmet `!` to construct the boilerplate
-   Include `<header>`, `<main>`, and `<footer>` sections
-   Utilize basic HTML structure including headings (`<h1>`, `<h2>`, etc.), paragraphs (`<p>`), and images (`<img>`)
-   Use classes when multiple elements require styling
-   Use IDs when a single element requires styling

### CSS Styling

-   Use external CSS to style the website
-   Modify background colors and font properties
-   Apply margin and padding to add spacing around and inside elements
-   Keep the website clean and organized
-   Focus on basic CSS techniques

## Project Structure

```
kodehode_VisHvaDuKan/
├── home.html
├── README.md
├── assets/
│   ├── icons/
│   ├── images/
│   │   ├── gifs/
│   │   ├── posts/
│   │   └── thumbnails/
│   └── videos/
│       ├── regular/
│       └── shorts/
├── components/
│
└── styles/
    ├── buttons.css
    ├── comment-section.css
    ├── header.css
    ├── home.css
    ├── menu-bar.css
    ├── navigation-bar.css
    └── video-section.css
```

## Installation Guide

### Prerequisites

-   A web browser (Chrome, Firefox, Safari, Edge, etc.)
-   A code editor (VS Code, Sublime Text, etc.) - optional, for viewing/editing code

### Option 1: View Online

1. Visit the GitHub repository: `https://github.com/Borgerod/kodehode_VisHvaDuKan`
2. Click on the deployed link (if GitHub Pages is enabled)

### Option 2: Download and Run Locally

1. **Download the repository**

    - Go to `https://github.com/Borgerod/kodehode_VisHvaDuKan`
    - Click the green "Code" button
    - Select "Download ZIP"
    - Extract the ZIP file to your desired location

2. **Open the website**
    - Navigate to the extracted folder
    - Double-click on `home.html` to open it in your default web browser
    - Alternatively, right-click `home.html` and select "Open with" to choose a specific browser

### Option 3: Clone with Git

1. **Clone the repository**

    ```bash
    git clone https://github.com/Borgerod/kodehode_VisHvaDuKan.git
    ```

2. **Navigate to the project folder**

    ```bash
    cd kodehode_VisHvaDuKan
    ```

3. **Open the website**

    - Double-click `home.html` or open it with your preferred browser
    - Or use a local development server:

        ```bash
        # Using Python 3
        python -m http.server 8000

        # Using Node.js (with http-server package)
        npx http-server
        ```

    - Then visit `http://localhost:8000/home.html` in your browser

## Technologies Used

-   HTML5
-   CSS3
-   Google Material Icons

## Features

-   Responsive header with navigation
-   Search functionality UI
-   Video section layout
-   Comment section styling
-   Reusable button components
-   Clean and organized CSS structure

## Author

Borgerod

## Repository Contents

-   HTML file(s)
-   CSS file(s)
-   Image directory (assets/)
