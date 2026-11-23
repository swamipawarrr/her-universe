# Her Universe — free birthday website

A mobile-first, interactive 3D galaxy gift made with HTML, CSS and Three.js.

## 1. Personalise it
Open `index.html` in a code editor. Find `const CONFIG = {` near the top of the JavaScript section.

The current version is already personalised for Sharu, from Swami. To edit it later, find `const CONFIG = {` in `index.html` and change:
- `herName`: her name or nickname
- `yourName`: your name
- `welcome`: the welcome message
- `planets`: the six planet titles and messages

The last planet is the birthday destination. Make the messages specific to your relationship. Save the file.

## 2. Preview it
The 3D engine is loaded from jsDelivr, so an internet connection is required.
- Easiest: double-click `index.html` in a modern browser.
- If your browser blocks module loading from a local file, use VS Code with the free Live Server extension, then click **Go Live**.

## 3. Publish for free with GitHub Pages
1. Create/sign in to a free account at https://github.com
2. Create a new **public** repository, for example `her-universe`.
3. Upload `index.html` to the repository root (you can also upload this README).
4. Open repository **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then Save.
7. Wait a minute or two. GitHub will show a public website URL in the Pages section.
8. Open that URL on your phone to test it, then send it to her.

## Notes
- Cost: ₹0 using GitHub Pages' free hosting and the free Three.js CDN.
- No account, database, API key, or paid service is needed for the website.
- An internet connection is needed to load Three.js.
- The website does not collect or transmit her data.
- Test on your phone before sending. If the device is older, close other tabs for smoother 3D animation.
- You can replace the generic sample text with real memories, but don't publish private photos or sensitive information without considering who can access the public link.
