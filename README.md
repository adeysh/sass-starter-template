# Sass Starter Template

I created this for starting my sass projects using gulp.

## Installation

1. Create an empty directory to get started and initialize git repository.
2. Use git command
   ```
   git pull https://github.com/adeysh/sass-starter-template.git
   ```
   to clone the starter files into your project root directory.

### If you're using frontend-mentor

1. If you're using frontend-mentor starter files for development then you can remove the README.md file and .gitignore files from the cloned repo.
2. Move the frontend-mentor starter files to the current directory using

```
mv ~/frontend-mentor-starter-files/* .
```

3. Run `npm install` to install all the dependencies.
4. Run `npx gulp` to start the server at `localhost:3000`.
5. You can continue further below.

### If you're not using frontend-mentor

1. Create the `index.html` file and link the css file in the `dist/style.css` and js file in `dist/script.js`.
2. Explore the files in the directory in the `app/` folder.
3. Create an npm project in the root of the project folder.

   ```js
   npm init -y
   ```

4. Install all the dependencies for the gulp workflow.

   ```js
   npm install
   ```

5. If there are some errors, try to fix it with `npm audit fix`

6. Start the server with

   ```js
   npx gulp
   ```

7. This should start the server at `localhost:3000`

8. Create scss components files at `components/` folder. Include styles from util as `@use '../util' as *` to import the styles from util folder.
