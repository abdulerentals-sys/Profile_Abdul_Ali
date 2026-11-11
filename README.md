# Dr. Abdul Ali — personal profile

A responsive personal website about Abdul Ali's IIT Bombay PhD, energy storage research, education, and entrepreneurial journey founding eRentals.

## Contents

- Personal introduction and the story of completing a doctorate while building a business.
- Research in vanadium redox flow batteries, DAE methods, an all-iron flow battery prototype, and microgrids.
- A verified journal publication, conference presentations, and selected projects.
- eRentals' founding journey and areas of work.
- Education, campus leadership, acknowledgements, contact details, and the original resume.

## Run and build

The website uses static HTML, CSS, and JavaScript, with no third-party runtime dependencies or external font requests.

Open `index.html` directly, or serve the repository with any static server. All asset paths are relative, so the site also works beneath a GitHub Pages project path.

```sh
npm run check
npm run build
```

The build copies the homepage, assets, and resume to `dist/` for static hosting. The original resume PDF is preserved byte for byte. No dependency installation is needed with Node.js available.

## Editing

- `index.html`: biography, research, education, contact, and structured metadata.
- `assets/profile.css`: typography, colours, responsive layout, reduced-motion and print styles.
- `assets/profile.js`: mobile navigation, research filters, section navigation state, and footer year.
- `CV_AbdulAli_28July25.pdf`: original downloadable resume, July 2025 version.
- `.openai/hosting.json`: associated private Sites preview and static output directory.

The content remains readable without JavaScript. Disclosure sections use native HTML. Research filters and mobile navigation enhance the page when JavaScript is available.

## Content provenance

Education, research projects, conference presentations, campus roles, and the January 2023 start of eRentals are grounded in the existing July 2025 resume. PhD completion in May 2026 and the personal account of balancing research and entrepreneurship come from Abdul's subsequent account of his journey. The website explains this distinction next to the original CV download.

The 2025 paper is listed as published, verified against the [publisher record](https://doi.org/10.1016/j.jpowsour.2025.237659) and the [IIT Bombay publication list](https://www.ese.iitb.ac.in/faculty/dayadeep-monder). Manuscripts listed as under review or in preparation in the older CV are not represented as published papers.

Company links use [e-rentals.in](https://e-rentals.in/) and the [official eRentals LinkedIn page](https://www.linkedin.com/company/e-rentals/). No unverified business metrics or fabricated testimonials are used.

The previous homepage was a business dashboard. It remains in Git history; this revision replaces the homepage with the requested personal profile.

## Verification

JavaScript syntax and static build pass. Browser checks cover desktop, tablet, and narrow phone layouts (320, 390, 768, 1024 and desktop viewport), mobile menu and Escape handling, section anchors, all three research filters, and expandable project details. Internal links and assets were checked; the original resume matches its Git blob and deployed copy.
