## Setting up my Git Repository

<h3>1. Instructions to set up local folder to point to GitHub</h3>

    ```BASH
    echo "# colmaracademy" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/xuncsg/colmaracademy.git
    git remote -v
    git push -u origin main
    ```
<h3>* If pushing an existing repository from the command line </h4>

    ```BASH
    git remote add origin https://github.com/xuncsg/colmaracademy.git
    git branch -M main
    git push -u origin main
    ```

<h3>2. In the event that the URL repo is set wrongly, use the following command to set the correct url:</h3>

    ```BASH
    git remote set-url origin https://github.com/xuncsg/colmaracademy.git
    git remote -v
    git push
    ```

<!-- Updated with 2. -->

<!-- Updated as of 15 August 24 with 3. -->

<h3>3. Important Note on **css specificity**:</h3>

    ```BASH
    - Universal selector (*) targets every element (regardless tag, class, ID)
    - If pseudo class `:root` is used, `:root` takes priority over `html`
        - When applied, font size of 5px takes priority over that of html
    - Here, `html` selector takes priority as root element over universal selector

    ```css
        *{
            margin: 0;
            padding: 0;
        }

        /* :root{ font-size: 5px; } */

        html, body{
            box-sizing: border-box;
            font-family: "Lato", sans-serif;
            font-size: 16px;
        }
    ```