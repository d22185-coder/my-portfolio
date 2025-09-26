# My Portfolio — Step-by-step (saved)

This README contains the step-by-step instructions for editing, previewing, and deploying your single-file portfolio site.

## 1) Save the file locally
- This directory `my-portfolio/` was created by the script.
- `index.html` is the single-file website. Open it in your editor (Spyder) and edit placeholders.

## 2) Basic edits (replace placeholders)
- Replace `[Your Name]` with your real name.
- Replace the profile image `src` with your own image filename under `assets/images/`.
- Edit the About text, blog post titles, and gallery captions.

## 3) Add your images and assets
- Put images inside `assets/images/`.
- Recommended filenames used in the template: `profile-placeholder.png`, `gallery1.png`, `gallery2.png`, `gallery3.png`, `gallery4.png`.
- Compress images before adding to keep the site fast.

## 4) Quick local preview
- Double-click `index.html` to open in a browser.
- OR run a local server in this folder:
  ```bash
  cd my-portfolio
  python -m http.server 8000
  # then open http://localhost:8000
  ```
- Or use the Live Server extension in VS Code for real-time updates.

## 5) Contact form options
- Option A — mailto: (no backend): use `action="mailto:you@example.com"` in the form.
- Option B — Formspree (recommended): change `action` to `https://formspree.io/f/your-id` and `method="POST"`.
- Option C — Netlify Forms: add `data-netlify="true"` and a hidden `form-name` input (works when deployed to Netlify).

## 6) Deploying
- GitHub Pages: push repo and enable Pages in repository settings.
- Netlify: drag & drop folder or connect repo for continuous deploys.
- Vercel: import project from GitHub and deploy.

## 7) Tips
- Add meta description and OpenGraph tags for better sharing.
- Add `alt` attributes for all images.
- Compress images for faster loading.

## 8) Next steps I can help with
- Split CSS/JS into separate files and produce `style.css` & `script.js`.
- Configure Formspree or Netlify form and update HTML accordingly.
- Generate a social preview image & favicon.

