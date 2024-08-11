# Facebook-Login-page
Using tailwind-css only



---

-> Facebook Login Page Clone using Tailwind CSS and PostCSS

This project aims to replicate the Facebook login page using HTML, Tailwind CSS, and PostCSS. By following the steps below, you'll create a sleek and responsive UI similar to Facebook's login screen.

->-> Prerequisites

Before you begin, ensure that you have the following installed:

1. Code Editor: Use a code editor like Visual Studio Code or Sublime Text.
2. Browser: Chrome or Firefox is recommended.
3. Node.js and npm: Install Node.js to manage packages, including Tailwind CSS and PostCSS.

->->-> Step 1: Install Node.js

1. Download Node.js: Visit the official Node.js website (https://nodejs.org/en/download/) and download the appropriate version for your operating system.
2. Install Node.js: Follow the installation instructions provided on the website.
3. Verify Installation: Open a terminal or command prompt and run the following commands:
   ```
   node -v
   npm -v
   ```
   If installed correctly, these commands should display the installed Node.js and npm versions.

->->-> Step 2: Set Up Your Project

1. Create Project Structure:
   - Open your terminal and navigate to the desired location for your project.
   - Create a new folder for your project (e.g., `my-facebook-clone`) and open it in your code editor.
   - Inside this project folder, create another folder named `src`. This is where your source code will reside.
   ```
   mkdir my-facebook-clone
   cd my-facebook-clone
   mkdir src
   ```

2. Install Tailwind CSS and PostCSS:
   - In your project folder, run the following commands:
     ```
     npm install tailwindcss postcss autoprefixer
     ```
   - Create a `tailwind.config.js` file by running:
     ```
     npx tailwindcss init
     ```
   - Configure PostCSS by creating a `postcss.config.js` file:
     ```javascript
     module.exports = {
       plugins: {
         tailwindcss: {},
         autoprefixer: {},
       },
     };
     ```

3. Create Files:
   - Inside the `src` folder, create two files:
     - `index.html` for HTML content.
     - `styles.css` for your Tailwind CSS styles.

4. Write Your Facebook Login Page:
   - Use HTML to create the login form structure in `index.html`.
   - Apply Tailwind CSS classes to style your components in `styles.css`.

That's it! You're ready to start building your Facebook login page clone. Refer to the full tutorial for detailed steps and styling.

---

Feel free to customize the README further based on your project's specifics. Happy coding! 😊🚀
