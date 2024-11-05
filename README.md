# ATS Pod 5 Project
**Frida Cano Falcón**

## Discovering the World - Articles Page

This project is a web page showcasing various articles categorized by subjects such as travel, work, lifestyle, food, and business. Each article is displayed in a card format, including an image, title, subject, brief description, and action buttons for editing or deleting articles. The page is responsive and styled using HTML, CSS, JavaScript, and Bootstrap.


## Project Overview

### Features
- **Article Cards**: Each card displays the article's image, title, subject, and a brief description.
- **Action Buttons**: Each card includes icons for editing and deleting the article.
- **Subject Filters**: Buttons below the title "Discovering the World" allow users to filter articles by subject.
- **Responsive Design**: The layout adjusts for mobile, tablet, and desktop screens using Bootstrap for responsive design.

### Main Components
- **HTML (index.html)**: Defines the structure of the webpage, including the card layout and filter buttons.
- **CSS (styles.css)**: Styles the page, providing positioning, color, and font settings, along with overlay effects for the cards.
- **JavaScript (scripts.js)**: Contains JavaScript code for interactivity (in the current form, this is limited to front-end display).
- **Icons**: Edit and delete icons on each card use URLs for the pencil and trash can images.

## Setup Instructions

To deploy this project locally on a new computer, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/FCANOF/WebPageProject.git
   ```
   
2. **Navigate to the Project Directory**:
   ```bash
   cd WebPageProject
   ```

3. **Open the Project**:
   You can open the `index.html` file in a browser to view the page. Alternatively, use an editor like Visual Studio Code for live previewing:

   - Open the folder in VS Code:
     ```bash
     code .
     ```
   - Install a live server extension in VS Code for a better development experience, if desired.

4. **Ensure Internet Connectivity**:
   Since the project relies on external icons and Bootstrap, ensure that your computer is connected to the internet to load these assets.

## Technology Stack

- **HTML5** for structure.
- **CSS3** for styling, with custom overlays and responsive card designs.
- **JavaScript** for dynamic interactions.
- **Bootstrap** (via CDN) for responsive layout and styling.

## License

This project could be distributed under the MIT or Apache 2.0 license