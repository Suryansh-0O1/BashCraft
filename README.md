# Landing Page Project

This repository contains the code for a responsive landing page designed to showcase past and future events. The page features a fixed header with a hamburger menu for mobile navigation, an organized layout for event listings, and a modern dark-themed design.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [Code Overview](#code-overview)
  - [HTML Structure](#html-structure)
  - [CSS Styling](#css-styling)
  - [JavaScript Functionality](#javascript-functionality)
- [Usage](#usage)
- [License](#license)

## Features
- **Responsive Design:** Adapts seamlessly to various screen sizes, ensuring an optimal user experience on both mobile and desktop devices.
- **Hamburger Menu:** A sliding menu that provides easy navigation on smaller screens, enhancing usability.
- **Event Listings:** Clearly organized sections for past and future events, each with images and relevant details.
- **Custom Styling:** A modern aesthetic achieved through effective use of CSS.

## Technologies Used
- **HTML5:** Provides the structure for the landing page.
- **CSS3:** Used for styling the layout and visual appearance.
- **JavaScript:** Adds interactivity for the hamburger menu.

## File Structure
```
/LandingPage
│
├── LandingPage.html        # Main HTML file for the landing page
├── styles/
│   ├── page_body.css       # CSS for the main content layout
│   └── page_header.css      # CSS for the header styling
└── javascript/
    └── menu.js             # JavaScript for hamburger menu functionality
```

## Code Overview

### HTML Structure
The `LandingPage.html` file sets up the basic structure of the webpage. Key elements include:

- **Header Section:** Contains the logo and a hamburger menu for navigation. The menu is hidden off-screen until activated.
- **Main Content:** Composed of two main sections:
  - **Past Events:** Displays a title and details for the latest and other past events, including images and descriptions.
  - **Future Events:** Similar structure for upcoming events, providing a preview.

### CSS Styling
The styles are divided into two files: `page_body.css` and `page_header.css`.

- **`page_body.css`:** 
  - Sets a dark background color and white text for contrast.
  - Defines styles for the main body layout using flexbox, aligning items centrally.
  - Styles for event listings, including margins and padding to ensure clear separation and readability.
  - Media queries to ensure responsiveness across different screen sizes.

- **`page_header.css`:**
  - Styles the fixed header to remain at the top during scrolling.
  - Includes styles for the hamburger menu, with transitions for visual effects when opened or closed.
  - Defines the layout of the header sections, ensuring proper alignment of the logo and menu items.

### JavaScript Functionality
The `menu.js` file contains the logic to toggle the visibility of the hamburger menu:

- Selects the hamburger menu and the off-screen menu using `querySelector`.
- Adds an event listener to the hamburger menu that toggles the `active` class on both the menu and the off-screen menu when clicked, causing the menu to slide into view.

## Usage
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/landing-page.git
   ```
   
2. **Navigate to the Project Directory:**
   ```bash
   cd landing-page
   ```

3. **Open `LandingPage.html` in a Web Browser:**
   Simply double-click the file or open it via your browser to view the landing page.

4. **Customize:**
   Feel free to edit the HTML, CSS, or JavaScript files to suit your needs. You can change event details, add new sections, or modify styles.
