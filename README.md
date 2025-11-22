# BrightTask

A modern task management landing page built with HTML, CSS, and Tailwind CSS. Clean design, fully responsive, and ready to deploy.

**Live Demo:** [brighttask.github.io](https://yourusername.github.io/brighttask)

## What's This?

BrightTask is a landing page showcasing a task management app. It's got everything you need - hero section with app mockup, features, pricing tables, and a waitlist signup form. Perfect for presenting your SaaS product or startup idea.

## Tech Stack

Just the essentials:
- HTML5 & CSS3
- Tailwind CSS (via CDN)
- Feather Icons
- Google Fonts (Poppins)

No build tools, no complicated setup. Just open the HTML file and you're good to go.

## Getting Started

**Option 1: Just open it**

Clone the repo and double-click `index.html`. That's it.
```bash
git clone https://github.com/yourusername/brighttask.git
cd brighttask
# Double click index.html
```

**Option 2: Use Live Server (better for development)**

If you're using VS Code:
1. Install the Live Server extension
2. Right click `index.html` → Open with Live Server
3. Your browser opens automatically at `localhost:5500`

**Option 3: Python server**
```bash
python -m http.server 8000
# Open http://localhost:8000 in your browser
```

## Deploying to GitHub Pages

Want to put this online? Super easy with GitHub Pages.

1. Push your code to GitHub (if you haven't already):
```bash
git add .
git commit -m "first commit"
git push origin main
```

2. Go to your repo on GitHub → Settings → Pages

3. Under "Source", select `main` branch and `/ (root)` folder

4. Hit Save and wait a minute

Your site will be live at `https://yourusername.github.io/brighttask`

### Custom Domain

Got your own domain? Add a file named `CNAME` to your repo with just your domain name in it:
```
yourdomain.com
```

Then configure your DNS settings with your domain provider. Give it 24 hours to propagate.

## Customizing

Everything's in one file (`index.html`), so it's super easy to customize.

**Change colors:**
```html
<!-- Change blue to purple -->
<button class="bg-blue-600 hover:bg-blue-700">
<!-- to -->
<button class="bg-purple-600 hover:bg-purple-700">
```

**Update text:** Just edit directly in the HTML. Sections are clearly labeled with comments.

**Change fonts:** Edit the Google Fonts link in the `<head>` and update the font-family in the `<style>` tag.

**Add sections:** Copy any existing section, paste it where you want, and modify the content.

## Project Structure
```
brighttask/
├── index.html          # Everything's here
├── README.md          # You're reading it
└── screenshot.png     # Add your own screenshot
```

Yep, it's that simple. One HTML file does it all.

## Credits

- Icons from [Feather Icons](https://feathericons.com/)
- Fonts from [Google Fonts](https://fonts.google.com/)
- Built with [Tailwind CSS](https://tailwindcss.com/)

---

Made with ❤️ by [Sayyeone](https://github.com/sayyeone)

Questions? Open an issue or hit me up!
