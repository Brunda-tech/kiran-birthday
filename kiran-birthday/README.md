# Kiran's Birthday Surprise 🎉

A static website (HTML, CSS and JavaScript only). No build step or installs needed.

## Run it locally
Open `index.html` in a browser, or in VS Code right-click it and choose "Open with Live Server".

## Edit the content
- Memory stories and photo captions: the `MEMORIES` list near the bottom of `index.html`
- Typing lines in the intro: the `LINES` list
- Letter and "About him" cards: the HTML sections with the same names
- Replace a photo: put a new image in `images/` using the same file name

## Deploy with GitHub Pages
1. Create a new repository on GitHub (for example `kiran-birthday`).
2. In this folder run:
   git init
   git add .
   git commit -m "Birthday website"
   git branch -M main
   git remote add origin https://github.com/<your-username>/kiran-birthday.git
   git push -u origin main
3. On GitHub open Settings > Pages, set Source to "Deploy from a branch", choose `main` and `/ (root)`, then Save.
4. After a minute your site is live at https://<your-username>.github.io/kiran-birthday/
