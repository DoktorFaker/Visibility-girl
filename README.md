# Visibility Girl

A browser game (PC + phone). Pure static files: no build step, no server code.

## Play locally
Serve the folder (opening index.html directly may block audio/sprites):

    python3 -m http.server 8000   # then open http://localhost:8000

## Publish on GitHub Pages (free)
1. Create a new GitHub repository (e.g. `visibility-girl`).
2. Upload everything in this folder (or `git add . && git commit && git push`).
3. Repo Settings -> Pages -> Source: "Deploy from a branch" -> branch `main`, folder `/ (root)` -> Save.
4. After about a minute the game is live at https://YOUR-USER.github.io/visibility-girl/

Notes: total size is about 70 MB (music + recorded voices); every file is under GitHub's 100 MB limit.
`cover.jpg` is the 16:9 cover image for the repo/social preview.
