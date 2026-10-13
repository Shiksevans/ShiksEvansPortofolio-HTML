# Evans Shikutwa | Portfolio

Personal portfolio website for **Evans Shikutwa**, an AI trainer, LLM evaluator, data annotator and transcriptionist based in Nairobi, Kenya.

**Live site:** `https://your-username.github.io/your-repo-name/` (replace after deploying, see [Deploy](#deploy-to-github-pages))

---

## What's on the site

| Section | What it shows |
|---|---|
| **Hero** | Introduction, role, and an annotated street-scene illustration |
| **About** | Short bio, photo, location, background, languages and focus |
| **Skills** | Annotation and labeling, transcription, quality assurance, LLM evaluation, training and prompting, programming (Python), annotation tools, platforms, languages, plus education and certifications |
| **Projects** | Five independent projects and four platform-work entries (see below) |
| **Contact** | Email, LinkedIn, location, time zone, languages, rates, availability, and a message form |
| **Booking** | A four-step booking request flow (service, date, time, details) |

### Independent projects

1. **PointCloud Inspector**: 3D annotation QA on an openly licensed LiDAR dataset.
2. **LabelForge AI**: a 300-message annotation dataset with intent, sentiment, urgency and human-review labels, plus a handbook, taxonomy, adjudication log and quality dashboard.
3. **TruthLens**: a 100-question benchmark for testing an AI model's factuality, unsupported claims and abstention.
4. **MedScribe QA**: 25 fictional clinical dictations with WER analysis and a "Meaning Changed" challenge.
5. **ClinCheck AI**: 50 fictional healthcare questions with a severity-ranked error register and a "Red Flag Review" system.

> All clinical content is fictional and uses no real patient identifiers. ClinCheck AI is an AI evaluation project, not a clinical decision-making product.

### Platform work

Remotasks, Outlier, Scale AI and Toloka.

---

## Tech

- A single self-contained file: `portfolio.html` (HTML, CSS and vanilla JavaScript)
- No framework, no build step, no dependencies to install
- Fonts from Google Fonts: Space Grotesk, Inter and JetBrains Mono (with fallbacks if offline)
- Illustrations are inline SVG, and the profile photo is embedded in the file as a compressed image
- Responsive layout with a mobile menu, keyboard-friendly booking controls, and reduced-motion support

---

## Run it locally

1. Download or clone this repository.
2. Open `portfolio.html` in any modern browser.

That's all. No server is needed.

---

## Deploy to GitHub Pages

1. Rename `portfolio.html` to `index.html` (GitHub Pages looks for this name).
2. Push the repository to GitHub.
3. Go to **Settings, Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select the `main` branch and the `/ (root)` folder, then save.
5. After a minute or two the site is live at `https://<your-username>.github.io/<repo-name>/`.

Other free hosts such as Netlify and Cloudflare Pages also work by uploading the single HTML file.

---

## How to customise

Open the HTML file in a text editor and search for these items:

| What to change | Where to look |
|---|---|
| Email address used for messages and bookings | `const EMAIL = ...` near the bottom of the file |
| Bio, skills, projects, rates, availability | The matching `<section>` blocks (`id="about"`, `"skills"`, `"projects"`, `"contact"`) |
| Booking services and times | The `serviceChoices` and `timeChoices` blocks in the booking section |
| Colors | The CSS variables at the top of the `<style>` block (`--teal`, `--amber`, `--coral`, `--violet`, `--ink`) |
| Profile photo | The `<img>` inside `<figure class="about-photo">`. Replace its `src` with a file path such as `assets/photo.jpg` or a new embedded image. |

---

## About the contact and booking forms

The site has no backend, so nothing is stored or sent automatically. When a visitor submits the contact form or a booking request, the page shows the finished message with three options: open it in Gmail, open it in their email app, or copy it. The visitor then sends the email themselves.

For real-time availability and automatic confirmations, you can link or embed a scheduling tool such as Cal.com or Calendly in the booking section. For a contact form that delivers messages directly, a service such as Formspree can be connected.

---

## Repository structure

```
.
├── index.html      # the portfolio (renamed from portfolio.html for GitHub Pages)
└── README.md
```

---

## Contact

- **Email:** shikutwaevans339@gmail.com
- **LinkedIn:** [linkedin.com/in/evans-shikutwa-a2740b255](https://www.linkedin.com/in/evans-shikutwa-a2740b255)
- **Location:** Nairobi, Kenya (East Africa Time, UTC+3)

---

© 2026 Evans Shikutwa. All rights reserved. If you want others to reuse the code, add a `LICENSE` file (for example MIT) to the repository.
