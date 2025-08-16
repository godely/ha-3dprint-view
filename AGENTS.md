# Project Overview

This is a single-page web application that serves as an interactive 3D model viewer. It is built with modern web technologies.

## Core Technologies

-   **Language**: JavaScript (using ES6 modules)
-   **3D Rendering**: The project uses the `online-3d-viewer` library. This library handles all complex 3D rendering and file parsing. The official source code can be found at its GitHub repository: https://github.com/kovacsv/Online3DViewer

## How to Run and Test

-   **Running the Application**: The application can be run by simply opening the `index.html` file in a modern web browser.
-   **Testing**: There are currently no automated tests for this project. All validation should be done through manual testing in the browser.

## Key Files

-   `index.html`: This is the main and only file for the application. It contains all the HTML structure, CSS styling, and JavaScript logic.

## Agent Instructions

-   **Initial Goal**: For this initial phase, create a simple, self-contained `index.html` file for rapid prototyping and easy experimentation.
-   **Dependencies**: To maintain simplicity for now, load all required libraries (like `online-3d-viewer`) directly from a CDN within the HTML file. Do not introduce `npm`, a `package.json` file, or a build system (like Webpack or Vite) at this stage.
-   **Future Evolution**: Be aware that this project is a prototype. It will eventually be refactored into a more complex component (a Home Assistant custom card), which will likely require a proper build system and package management. Please keep this in mind and avoid making architectural choices that would complicate this future transition.