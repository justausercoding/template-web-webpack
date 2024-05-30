# Web template for webpack

## Steps

1. HTML: Create structure of website
2. CSS: (Use reset and add fonts) write CSS
3. JavaScript: write JS code

<br>

## Important

### package.json

The following was changed to prevent accidental publish:
- deleted: "main": "index.js"
- added: "private": true

<br>

## Deploy to Github Pages
(https://gist.github.com/cobyism/4730490)

1. Remove the `dist` directory from the project’s `.gitignore` file.

2. Make sure git knows about your subtree (the subfolder with your site).

    ```sh
    git add dist && git commit -m "Initial dist subtree commit"
    ```
3. Use subtree push to send it to the `gh-pages` branch on GitHub. (see 'package.json' for script)





