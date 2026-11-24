# Siti Nurzaini Yahya — Translation & Localization Website

Formal portfolio website for Siti Nurzaini Yahya, English ⇄ Malaysian Malay translator and localization specialist.

## Structure

```
.
├── .gitlab-ci.yml   # GitLab Pages deployment
├── README.md
└── public/
    └── index.html   # The complete site (HTML, CSS and JS in one file)
```

## Publish on GitLab Pages

1. Create a new project on GitLab (e.g. `zaini`).
2. Upload these files, keeping the folder structure, or push them with git:
   ```bash
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://gitlab.com/<your-username>/zaini.git
   git push -u origin main
   ```
3. The pipeline runs automatically. When it finishes, go to **Deploy → Pages** in the project to find the site URL
   (usually `https://<your-username>.gitlab.io/zaini`).

## Before going live

- **Testimonials:** the three cards in the `#testimonials` section are placeholders marked "Sample".
  Replace each quote, name and title with a real client testimonial (with the client's permission),
  then delete the `<span class="tag">Sample</span>` lines.
- **Contact form:** the form opens the visitor's email app with the details filled in; it does not send by itself.
  To receive submissions directly, connect a form service such as Formspree.

## Edit locally

Open `public/index.html` in any browser. No build step is needed.
