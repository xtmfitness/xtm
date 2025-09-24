# Page One (Templatemo)

This is a modified copy of the TemplateMo "Page One" static HTML template.

What I changed
- Replaced header text with `img/Clean Logo.png` and added the tagline.
- Updated Home, Services, Gallery, and Contact sections.
- Removed the contact form and footer copyright.
- Added custom styles in `css/templatemo-style.css` for logo, services, placeholders, and contact email.

Quick publish options

1) GitHub Pages (recommended for free, simple hosting)
- Create a new GitHub repository and push this folder as the repository root.
- In repository Settings → Pages, choose the `main` branch and `/ (root)` directory.
- After a few minutes your site will be available at `https://<username>.github.io/<repo>`.

2) Netlify (recommended for easy continuous deploys and custom domains)
- Create a Netlify account and connect your GitHub repo (or drag & drop the site folder).
- For direct uploads, zip the folder and drag it to Netlify Drop.

3) Vercel
- Create a Vercel account and import the GitHub repo. Use the default settings for a static site.

4) FTP / cPanel
- Upload the site folder contents to your web host's `public_html` (or equivalent) via FTP.

Local preview

Run a quick local HTTP server and open the site in your browser:

```powershell
cd 'C:\Users\gtsar\Desktop\NUW\templatemo_504_page_one\templatemo_504_page_one'
python -m http.server 8000
# then open http://127.0.0.1:8000/index.html
```

Need help deploying?
- Tell me which provider you prefer (GitHub Pages, Netlify, Vercel, FTP), and I will create any necessary configuration or set up a deploy workflow for you.
