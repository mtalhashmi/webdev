# Interactive Web Development Course Dashboard

This is a single-page interactive web application designed as a student dashboard for a 15-week frontend web development course. It provides a modern, hands-on, and project-based learning experience, allowing students to track their progress and access daily lesson content, assignments, and cheat sheets.

## Features

* **Modern UI/UX:** Clean design with a refined color palette, modern typography, and responsive layout using Tailwind CSS.
* **Interactive Hero Section:** Engaging welcome section with dynamic text changes.
* **Progress Tracking:** A visual progress bar displays overall course completion, and individual day completion can be marked and tracked per user.
* **User Profiles (Simulated):** Students can "sign in" with their name to save and load their individual progress locally in the browser.
* **Accordion-based Curriculum:** Weeks are organized into collapsible accordion items for easy navigation.
* **Daily Lesson Tabs:** Each week's content is broken down into daily lessons accessible via tabs, featuring class content, assignments, and cheat sheets.
* **Google Forms Integration for Project Submission:** A button for each week directs students to an external Google Form for submitting their weekly projects.
* **Responsive Design:** Optimized for various screen sizes (desktop, tablet, mobile).

## Project Structure


.
├── index.html
├── style.css
└── script.js
├── README.md
├── LICENSE
└── .gitignore


* `index.html`: The main HTML file containing the structure and content of the dashboard.
* `style.css`: Custom CSS for additional styling and overrides not handled by Tailwind CSS.
* `script.js`: All JavaScript logic for interactivity, data management, and dynamic content generation.
* `README.md`: This file, providing project information.
* `LICENSE`: The license file for the project (MIT License).
* `.gitignore`: Specifies intentionally untracked files that Git should ignore.

## How to Run Locally

1.  **Clone the repository (or download the files):**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
    cd YOUR_REPOSITORY_NAME
    ```
    (Replace `YOUR_USERNAME` and `YOUR_REPOSITORY_NAME` with your actual GitHub details if you've already pushed it there).
2.  **Open `index.html`:** Simply open the `index.html` file in your web browser. You can drag and drop it into your browser, or right-click and choose "Open with..." your preferred browser.

## Hosting on GitHub Pages

This project is designed to be easily hosted on GitHub Pages:

1.  **Create a Public GitHub Repository:** Create a new public repository on your GitHub account (e.g., `web-dev-course-dashboard`).
2.  **Upload Files:** Upload all the files (`index.html`, `style.css`, `script.js`, `README.md`, `LICENSE`, `.gitignore`) to the root of your new repository.
3.  **Enable GitHub Pages:**
    * Go to your repository on GitHub.
    * Click on **Settings** > **Pages**.
    * Under "Build and deployment", set "Source" to **"Deploy from a branch"**.
    * Under "Branch", select `main` (or `master`) and choose the `/ (root)` folder.
    * Click **Save**.
4.  **Access Your Site:** Your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPOSITORY_NAME/` within a few minutes.

## Important Note on Project Submission

The "Submit Weekly Project" button links to a placeholder Google Form. **You must replace `https://forms.gle/aumP8AwS91LKaWuf7` in `script.js` with the actual shareable link to your own Google Form** that is configured to collect files. This is a secure and effective way to receive student submissions without needing a backend for this static website.

## Technologies Used

* **HTML5:** For content structure.
* **CSS3:** For styling.
* **Tailwind CSS:** A utility-first CSS framework for rapid UI development and responsiveness.
* **JavaScript (Vanilla JS):** For all interactive functionalities and dynamic content.
* **Google Fonts:** For custom typography.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
