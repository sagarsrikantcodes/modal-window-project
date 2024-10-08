# Modal Window Project

## Overview

This project involves creating a modal window UI component that can be used on webpages. The modal window will overlay the current page content, allowing users to interact with it before returning to the main content. The project emphasizes the use of JavaScript classes and DOM manipulation.

## Features

- **Open Modal**: The modal can be opened by clicking any of the designated buttons.
- **Close Modal**: The modal can be closed by:
  - Clicking the close button inside the modal.
  - Clicking outside the modal on the overlay.
  - Pressing the `Esc` key on the keyboard.
  
## Technologies Used

- HTML
- CSS
- JavaScript (ES6)

## Project Structure

 - Project Link:- https://sagarsrikantcodes.github.io/modal-window-project/ 

## modal-window-project

 - index.html # The main HTML file
 - styles.css # CSS styles for the modal and overlay
 - script.js # JavaScript for modal functionality

## Getting Started

### Prerequisites

- A code editor (like Visual Studio Code)
- A browser (Chrome, Firefox, etc.)
- Live Server extension (recommended for local development)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sagarsrikantcodes/modal-window-project.git

2. Navigate to the project directory:
   ```bash
   cd modal-window-project

3. Open `index.html` in your browser or use the Live Server extension in VS Code.

### How to Use
1. Click any of the buttons labeled "Open Modal" to display the modal window.
2. To close the modal, you can:
    - Click the close button in the modal.
    - Click outside the modal on the overlay.
    - Press the `Esc` key.

### Code Overview
The JavaScript file contains the following key components:
 - *Element Selection:* Using `document.querySelector` and `document.querySelectorAll` to 
   select modal-related elements. 
 - *Event Handlers:* Functions that handle the opening and closing of the modal.
 - *Class Manipulation:* Adding and removing classes to show or hide the modal.

### Future Improvements
 - Add animations for opening and closing the modal. 
 - Enhance accessibility features (e.g., ARIA roles).
 - Implement dynamic content loading within the modal. 

### License
This project is licensed under the MIT License. See the LICENSE.md file for details.

### Acknowledgements
Thanks to Jonas for the instructional course that guided the development of 
this project.
