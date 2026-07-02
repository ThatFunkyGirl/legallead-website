# LegalLead website

A single-file HTML/CSS/JS website for LegalLead. No build tools, no dependencies to install.

## Edit it
Open `index.html` in VS Code. Everything is in one file:
- Colors: top of the `<style>` block, under `:root { ... }`
- Page text: search for the page you want, e.g. `id="page-about"`
- Nav links / buttons that jump between pages: any element with `data-goto="pagename"`

## Run it locally
1. Open this folder in VS Code (`File > Open Folder`)
2. Install the "Live Server" extension (by Ritwick Dey) from the Extensions panel
3. Right-click `index.html` in the file explorer and choose "Open with Live Server"
4. It opens in your browser at something like `http://127.0.0.1:5500` and auto-reloads when you save changes

## Share it with others (put it live on the internet)
Live Server only works on your own computer. To get a real public link:

**Fastest — Netlify Drop**
1. Go to https://app.netlify.com/drop
2. Drag this whole folder into the browser window
3. You get a live public URL in seconds, no account needed for the first deploy

**Free & permanent — GitHub Pages**
1. Create a new GitHub repository
2. Push this folder's contents to it (index.html must be at the root)
3. In the repo, go to Settings > Pages, set the source to the main branch
4. Your site goes live at `https://yourusername.github.io/reponame`

Either option gives you a link you can text, email, or post — anyone can open it, no install needed.
