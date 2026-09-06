# Nawaf Rubayan Alhejaili · Portfolio

> Professional personal portfolio website – used as a public CV when applying for jobs.

🔗 **Live site:** `https://nawaf-rubayan.github.io/portfolio/`  


---

## 📋 About

This is a single-page portfolio website built with **React** (loaded via CDN) and **Tailwind CSS** (utility classes inlined).  
It presents:

- Hero section with name, title, intro, and social links.
- About section with a summary and key stats.
- Work experience (timeline).
- Featured project – AI‑Powered PDF RAG Assistant.
- Technical & soft skills organised by category.
- Education.
- Contact details and a direct CV download button.

The design is modern, minimal, recruiter‑friendly, and fully responsive on all devices.  
It also includes a **dark/light theme toggle** with persistent user preference (localStorage).

---

## 🛠️ Tech Stack

- **React 18** (via CDN – no build step)
- **Babel Standalone** (for JSX in the browser)
- **Tailwind CSS** (via custom CSS classes – no extra build tools)
- **Fonts:** Inter (Google Fonts)
- **Icons:** Inline SVGs

No npm, no bundler, no server – just a single `index.html` file.  
Perfect for quick deployment and easy maintenance.

---

## 📁 Project Structure
/
├── index.html # Main entry point (all HTML, CSS, JS in one file)
└── cv.pdf # Your actual CV – placed in the same folder

> ⚠️ **Important:** The `cv.pdf` file must be named exactly `cv.pdf` and placed next to `index.html` for the download/view buttons to work.

---

## 🚀 How to Run Locally

1. Download or clone this repository.
2. Place your CV PDF as `cv.pdf` in the root folder.
3. Open `index.html` in any modern browser (Chrome, Edge, Firefox, etc.).
   - No server required – it works directly from the file system.

*(You can also use Live Server in VS Code for a better development experience.)*

---

## 🌐 Deploy to GitHub Pages

This repository is configured for **GitHub Pages** (static site hosting).

### Steps:

1. **Push** this repository to GitHub.
2. Go to **Settings → Pages** in your repo.
3. Under **Branch**, select `main` (or `master`) and keep the folder as `/ (root)`.
4. Click **Save**.
5. After a minute, your site will be live at:  
   `https://<your-username>.github.io/<repository-name>/`

---

## 🔧 Customisation

All personal information is stored in the `DATA` object inside the `<script>` block at the bottom of `index.html`.  
You can edit:

- `name`, `title`, `location`, `phone`, `email`
- `linkedin`, `github` (URLs)
- `summary` (professional intro)
- `experience` (array of job entries)
- `projects` (array of project objects)
- `skills` (object with category → array)
- `education` (degree, university, location, year)

After editing, simply commit and push – the site updates automatically.

---

## 📎 Adding a Custom Domain

1. In your repo **Settings → Pages**, enter your custom domain under **Custom domain**.
2. Add a `CNAME` file to the root of your repository with your domain (e.g., `nawaf.dev`).
3. Update your DNS provider with a `CNAME` record pointing to `<your-username>.github.io`.

---

## 📄 License

This project is open‑source and available under the [MIT License](LICENSE).  
Feel free to use it as a template for your own portfolio.

---

## 📬 Contact

- **Email:** [nawaaf.rubayan@gmail.com](mailto:nawaaf.rubayan@gmail.com)
- **LinkedIn:** [linkedin.com/in/nawaaf-rubayan-69a636296](https://linkedin.com/in/nawaaf-rubayan-69a636296)
- **GitHub:** [your-username](https://github.com/your-username) *(update this!)*

---

Built with ❤️ by Nawaf Rubayan Alhejaili.
