# Sass Starter Template

## Installation

1. I created this for starting my sass projects using gulp.
2. Create the `index.html` file and link the css file in the `dist/style.css` and js file in `dist/script.js`.
3. Explore the files in the directory in the `app/` folder.
4. Create an npm project in the root of the project folder.

   ```js
   npm init -y
   ```

5. Install all the dependencies for the gulp workflow.

   ```js
   npm install
   ```

6. If there are some errors, try to fix it with `npm audit fix`

7. Start the server with

   ```js
   npx gulp
   ```

8. This should start the server at `localhost:3000`

9. Create scss components files at `components/` folder. Include styles from util as `@use '../util' as *` to import the styles from util folder.
