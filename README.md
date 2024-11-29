# hussain.github.io
This is my portfolio website i am being serious about this portfolio.

# Portfolio Project Documentation

## Overview

This repository contains the code for a personal portfolio website. The portfolio highlights the skills, experience, projects, and contact information of Mohammad Hussain, a Frontend Developer. The project features a responsive design, making it adaptable to various screen sizes, and includes sections for the profile, about, experience, projects, and contact details.

### Features
- **Responsive Design**: The portfolio is fully responsive, adapting to both desktop and mobile devices.
- **Navigation**: The website features a top navigation bar and a hamburger menu for smaller screen sizes.
- **Profile Section**: Includes an introduction with a picture, a brief about the developer, and links to social profiles (LinkedIn, GitHub).
- **Experience Section**: Displays a list of technologies and skills with proficiency levels.
- **Projects Section**: Showcases recent projects with links to live demos and GitHub repositories.
- **Contact Section**: Provides contact information, including email and LinkedIn profile.
- **Smooth Scrolling**: Implemented smooth scrolling for navigation between sections.

---

## Table of Contents

1. [Tech Stack](#tech-stack)
2. [File Structure](#file-structure)
3. [How to Run Locally](#how-to-run-locally)
4. [Features and Functionality](#features-and-functionality)
5. [Customization](#customization)
6. [Contributing](#contributing)
7. [License](#license)

---

## Tech Stack

The portfolio is built using the following technologies:

- **HTML**: Structure of the website, with semantic tags for SEO and accessibility.
- **CSS**: Styling, including responsive design and transitions.
  - Utilizes Flexbox and Grid for layout.
  - Uses Google Fonts (`Poppins`) for typography.
  - Media queries for responsive design adjustments.
- **JavaScript**: A small script for the hamburger menu toggle functionality.

---

## File Structure

```
/portfolio-project
  ├── assets/              # Contains images (profile-pic.png, project images, icons, etc.)
  ├── index.html           # Main HTML file
  ├── style.css            # Main CSS file for styling
  ├── mediaqueries.css     # CSS file for media queries (responsive design)
  ├── script.js            # JavaScript file for hamburger menu toggle
  ├── README.md            # Documentation file (this file)
```

- **`assets/`**: Folder containing all images (profile picture, project images, icons for social links).
- **`index.html`**: The main HTML file for the portfolio structure.
- **`style.css`**: Contains the styling rules, including fonts, layouts, buttons, and sections.
- **`mediaqueries.css`**: Handles the media queries for different screen sizes (desktop, tablet, mobile).
- **`script.js`**: Contains the JavaScript for toggling the hamburger menu on mobile devices.

---

## How to Run Locally

### Prerequisites

Ensure you have a modern browser like Chrome, Firefox, or Safari installed to view the portfolio.

### Steps to Run Locally

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/portfolio-project.git
   ```

2. Navigate to the project folder:

   ```bash
   cd portfolio-project
   ```

3. Open the `index.html` file in your preferred browser:

   - **Option 1**: Open the file directly in your browser.
   - **Option 2**: Use a local server to run the project (optional). You can use tools like **Live Server** (VSCode extension) or any local server setup you prefer.

4. View the portfolio on `localhost` or directly on the browser.

---

## Features and Functionality

### 1. **Responsive Layout**
   - The layout adjusts based on the screen size using media queries.
   - On larger screens, a top navigation bar (`#desktop-nav`) is displayed.
   - On smaller screens (mobile), a hamburger menu (`#hamburger-nav`) is shown for navigation.

### 2. **Profile Section**
   - **Profile Picture**: A profile image (stored in `assets/profile-pic.png`) with the option to download the CV by clicking the "Download CV" button.
   - **Social Links**: Links to LinkedIn and GitHub profiles with clickable icons.

### 3. **About Section**
   - A brief introduction about the developer with details about education and experience.
   - A clickable arrow directs users to the Experience section.

### 4. **Experience Section**
   - Lists technical skills with proficiency levels (e.g., HTML, CSS, JavaScript, etc.).
   - Information is displayed in an easy-to-read article format, using icons for better visual appeal.

### 5. **Projects Section**
   - Displays recent projects with images and buttons linking to the GitHub repository and live demos.

### 6. **Contact Section**
   - Displays email and LinkedIn contact information.
   - Each item is represented with an icon for easy identification.

### 7. **Smooth Scrolling**
   - Smooth scroll functionality is implemented for seamless navigation between sections.

---

## Customization

You can customize the portfolio by making changes to the following:

1. **Profile Information**:
   - Update the name and position in the HTML (`<h1 class="title">Mohammad Hussain</h1>`).
   - Replace the profile image in `assets/profile-pic.png`.

2. **Social Links**:
   - Change the social media URLs for LinkedIn and GitHub in the profile section.

3. **Experience Section**:
   - Modify the technologies and proficiency levels by editing the relevant `<article>` tags in the HTML.

4. **Projects Section**:
   - Update the project images and links to your GitHub repositories and live demos.

5. **Contact Information**:
   - Change the email and LinkedIn URL in the Contact section.

6. **Styling**:
   - Modify `style.css` to change the look and feel of the portfolio.
   - You can update colors, fonts, and layout as needed.

7. **Responsive Design**:
   - If you want to adjust the breakpoints for different screen sizes, you can update the media queries in `mediaqueries.css`.

---

## Contributing

If you would like to contribute to the development of this portfolio project, you are welcome to fork this repository and create a pull request. Make sure to:

1. Fork the repository to your GitHub account.
2. Create a feature branch (`git checkout -b feature-name`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to your branch (`git push origin feature-name`).
5. Open a pull request to merge your changes.

---

## License

This project is open-source and available under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## Contact

If you have any questions or suggestions, feel free to reach out via:

- **Email**: examplemail@gmail.com
- **LinkedIn**: [Mohammad Hussain's LinkedIn](https://www.linkedin.com)