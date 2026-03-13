## CS Portfolio – Tasnim Rahmatullah

This is a **personal computer science portfolio** site for **Tasnim Rahmatullah**, showcasing projects, experience, skills, and contact information.  
The site is built as a **fully static single-page website** using plain **HTML, CSS, and JavaScript**.

### Features

- **Hero section** with a concise introduction and quick facts (location, university, interests).
- **About section** highlighting education, CGPA, and relevant coursework.
- **Projects section** with hand-picked projects:
  - BokuBot (RAG chatbot for BRAC University students)
  - Data Science, ML & Deep Learning Portfolio
  - Purbachal New Town Society Website
  - Password Generator
- **Experience section** describing research, bootcamps, and certifications.
- **Skills section** grouped into languages, tools/frameworks, and concepts.
- **Contact section** with email, GitHub, and LinkedIn links.
- **Responsive layout** designed to work on desktop and mobile.

### Tech Stack

- **HTML5** – structure and content (`index.html`)
- **CSS3** – layout, typography, and responsive design (`styles.css`)
- **JavaScript (ES6)** – navigation behavior and small interactions (`main.js`)

### Project Structure

- `index.html` – Main single-page portfolio.
- `styles.css` – Global styles and responsive layout.
- `main.js` – Navigation toggle and interactive behavior.
- `.github/workflows/main.yaml` – (Optional) CI/deployment workflow configuration.

### Getting Started (Local Preview)

No special build step is required. You can open the site directly in a browser.

1. **Clone the repository**:

   ```bash
   git clone <your-repo-url>.git
   cd Portfolio
   ```

2. **Open in a browser**:
   - Option 1: Double-click `index.html` (or open it via your browser’s “Open File” dialog).
   - Option 2 (recommended): Serve via a simple local web server, for example with Python:

     ```bash
     # Python 3
     python -m http.server 8000
     # Then visit http://localhost:8000 in your browser
     ```

### Deployment

Because this is a static site, it can be hosted on many platforms, such as:

- **GitHub Pages**
- **Netlify**
- **Vercel**
- **AWS S3 + CloudFront**

In most cases you only need to configure the host to serve `index.html` and static assets in the project root.

If you are using GitHub Pages, you can:

1. Push this repository to GitHub.
2. In the repository settings, enable GitHub Pages and point it at the `main` (or `gh-pages`) branch.

### Customization

- **Content**: Edit text in `index.html` (sections: About, Projects, Experience, Skills, Contact).
- **Profile image**: Replace `profile.jpg` with your own image file (keep the same file name or update the `src` attribute).
- **Styling**: Adjust colors, spacing, and typography in `styles.css`.
- **Behavior**: Tweak or extend any small interactions inside `main.js`.

### Contact

If you have questions or suggestions about this portfolio:

- **Email**: `tasnimdrmc6461@gmail.com`
- **GitHub**: `https://github.com/ProfCode101`
- **LinkedIn**: `https://www.linkedin.com/in/tasnim-rahmatullah-88b585256/`

