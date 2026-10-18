# Eyosiyas Tesfaye | AI-Integrated Full Stack Developer Portfolio

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

A modern, fully responsive personal portfolio website that showcases my projects, skills, certificates, awards and resume. I am an AI-integrated full stack web developer from Addis Ababa, Ethiopia, currently training at Evangadi Ethiopia Coding Academy.

**Live site:** _add your link here after deploying, for example `https://eyosiyas-tesfaye.github.io/portfolio/`_

---

## Features

- **Dark, professional design** with a pink and blue accent theme and smooth hover effects
- **Typing animation** on the home screen
- **About, Skills, Resume, Projects, Services and Thanks** sections
- **Frontend Foundations and Full Stack and AI Toolkit** skills layout
- **Project cards** with a Live Demo button and a Quick Preview pop-up that shows the live site inside the page
- **Certifications** from Udacity with a full-size viewer and a Verify Online link
- **Awards and Achievements** gallery with certificates and ceremony photos
- **Resume section** with a preview image, PDF download and Word download
- **Email chooser pop-up** that opens Gmail, the visitor's mail app, or copies the email address
- **WhatsApp contact button** and social links (GitHub, Telegram, LinkedIn, Instagram)
- **Scroll reveal animations** (turned off automatically for visitors who prefer reduced motion)
- **Fully responsive** on phones, tablets and desktops

## Featured Projects

| Project | Type | Stack | Live Demo |
| --- | --- | --- | --- |
| ChatGPT Clone | AI project | React, JavaScript, CSS3, AI API | [Open](https://chat-gpt-clone-frontend.onrender.com/) |
| Netflix Clone (Flixora) | Entertainment | React, JavaScript, Movie API | [Open](https://flixora-movies.vercel.app/) |
| Evangadi Forum | Full stack | React, Node.js, Express, MySQL | [Open](https://evangadi-forum-frontend-hl7j.onrender.com/dashboard) |

> The demos are hosted on free plans (Render and Vercel). The first visit can take up to a minute while the server wakes up.

## Tech Stack

- **HTML5** for structure
- **CSS3** with custom properties (variables) for the theme
- **Bootstrap 5.3** for the responsive grid, modals and utilities
- **Vanilla JavaScript** for the typing effect, scroll reveal, project preview, certificate viewer and email chooser
- **Bootstrap Icons** and **Font Awesome** for icons
- **Google Fonts (Inter)** for typography

No build step and no framework are needed. It is a static website.

## Project Structure

```text
.
├── index.html                      # The whole website (all sections, modals and scripts)
├── README.md
├── project/
│   ├── css/
│   │   ├── bootstrap.css           # Local Bootstrap styles
│   │   └── portfolio.css           # My custom styles and theme colors
│   ├── image/
│   │   ├── eyosi.jpeg              # Profile photo
│   │   ├── eyosi-full.jpeg
│   │   ├── resume-preview.jpg      # Resume picture shown on the site
│   │   ├── certificates/           # Udacity certificates
│   │   └── achievements/           # Award certificates and ceremony photos
│   └── Eyoaiyas-Resume/
│       ├── EYOSIYAS TESFAYE.pdf    # Resume (PDF)
│       └── EYOSIYAS TESFAYE.docx   # Resume (Word)
└── Resource/Design/                # Design inspiration references
```

## Run Locally

1. Download or clone the repository.
2. Open `index.html` in any modern browser.

That is all. To use a local server instead (optional):

```bash
# with Python
python -m http.server 8000
# then open http://localhost:8000
```

An internet connection is needed for Bootstrap scripts, icons, fonts and the live project previews, because they load from CDNs.

## Upload to GitHub

**Option A: with the GitHub website (no Git needed)**

1. Sign in at [github.com](https://github.com) and click **New repository**.
2. Name it `portfolio` (or `Eyosiyas-Tesfaye.github.io` to get a link without a folder name), set it to **Public** and create it.
3. Click **uploading an existing file** and drag in everything *inside* the `week-7` folder (`index.html`, `project`, `Resource`, `README.md`). Do not upload the folder itself, because GitHub Pages needs `index.html` at the top level.
4. Write a commit message such as `Add portfolio website` and click **Commit changes**.

**Option B: with Git**

```bash
git init
git add .
git commit -m "Add portfolio website"
git branch -M main
git remote add origin https://github.com/Eyosiyas-Tesfaye/portfolio.git
git push -u origin main
```

## Deploy for Free with GitHub Pages

1. Open your repository and go to **Settings**, then **Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Choose the **main** branch and the **/ (root)** folder, then click **Save**.
4. Wait one or two minutes. Your site will be live at:
   - `https://eyosiyas-tesfaye.github.io/portfolio/` (repository named `portfolio`)
   - `https://eyosiyas-tesfaye.github.io/` (repository named `Eyosiyas-Tesfaye.github.io`)
5. Paste the final link into the **Live site** line at the top of this file.

You can also host the same folder on Vercel or Netlify by importing the repository. No settings are needed.

## How to Customize

| What to change | Where |
| --- | --- |
| Theme colors | `:root` variables at the top of `project/css/portfolio.css` |
| Typing animation words | the `words` list in the script at the bottom of `index.html` |
| About text, skills, education, experience | the matching sections in `index.html` |
| Add a project | copy a card inside the `#portfolio` section and change the title, text, tech badges and link |
| Add a certificate or award | copy a card inside the `cert-section` blocks and add the image to `project/image/` |
| Update the resume | replace the PDF and DOCX in `project/Eyoaiyas-Resume/` (keep the same file names) |
| Social links, WhatsApp and email | search for `github.com`, `wa.me` and `emailModal` in `index.html` |

## Notes and Tips

- Some websites block being shown inside another page. If a Quick Preview stays blank, the **Live Demo** button still opens the site in a new tab.
- `project/image/apple.jpg` and the large image in `Resource/Design/` are not used by the live site. You can delete them to make the repository lighter.
- This is a public repository, so anything inside it can be seen by anyone. Only keep files you are happy to share.

## Connect With Me

- GitHub: [Eyosiyas-Tesfaye](https://github.com/Eyosiyas-Tesfaye)
- LinkedIn: [eyosiyas-tesfaye](https://linkedin.com/in/eyosiyas-tesfaye-2b5226435/)
- Telegram: [@Eyosi1212](https://t.me/Eyosi1212)
- Instagram: [@tesfayeeyosiyas2121](https://instagram.com/tesfayeeyosiyas2121)

## License and Usage

Copyright &copy; 2026 Eyosiyas Tesfaye. You are welcome to learn from the code structure and take inspiration from the design. Please do not reuse my personal content (photos, certificates, resume and written text) without permission.
