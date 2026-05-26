Container Article & Aside Demo

This project is a small HTML5 site that demonstrates how to use the `article` and `aside` containers in a modern page layout. It focuses on semantic structure, visual separation, and responsive-friendly markup.

 Project overview

The site includes multiple pages (`index.html`, `about.html`, `contact.html`, `gallery.html`) that share a consistent layout built around an `article` element for main content and an `aside` element for related or supplementary information.

A spacer element, implemented as a `<div>` containing an empty `<p>`, sits between the `article` and `aside` sections to create visual separation and improve readability. This spacer is styled with CSS and can be adjusted or replaced with margin/padding utilities.

Key HTML containers

`<article>`
  - Represents the primary content of the page (such as an article, tutorial, or standalone content block).
  - Structured to be self-contained and meaningful on its own.
  - Uses headings, paragraphs, and images to show how content within `article` should be organized.

`<aside>`
  - Provides supporting or related content, such as notes, callouts, or additional explanations.
  - Positioned next to the `article` to illustrate how sidebars or secondary panels can be built.
  - Demonstrates how `aside` helps screen readers and search engines understand secondary content.

Spacer between `article` and `aside`
  - Implemented as a `<div>` with a `<p>` inside to create vertical space between the main and side content.
  - Styled via CSS (for example, using margin or padding) to visually separate the two containers.
  - Highlights alternative approaches, such as applying margins directly on the `article` or `aside` elements.

CSS and layout

The `css` directory contains stylesheets for the different pages:

- `my_style.css` defines the core layout and typography.
- `a_styles.css`, `c_styles.css`, and `g_styles.css` add page-specific styles for the About, Contact, and Gallery pages.

The layout is designed to be multi-device-ready, with a simple responsive structure that keeps the `article` and `aside` containers readable on both large and small screens.

Images and tags

- The `logo` directory contains the site logo, favicon, and related images.
- The `tags` directory includes screenshots and diagrams that visually explain HTML elements, opening/closing tags, and the structure of article/aside sections.

These assets support the educational goal of the project by showing how HTML containers and tags look in context.

How to run the project

1. Clone the repository:
   ```bash
   git clone https://github.com/JamesOBishop10/Container_Article-Aside.git
   cd Container_Article-Aside
   ```
2. Open `index.html` in your web browser (or use a simple local server).
3. Navigate through the About, Contact, and Gallery pages to see how the `article` and `aside` containers are reused across the site.

Learning goals

This project is intended to help you:

- Understand when and why to use `article` and `aside` in semantic HTML.
- See how to visually separate main content and secondary content using CSS.
- Practice structuring a small multi-page site with consistent layout and reusable assets.
- Get comfortable working with HTML5, CSS, and basic project organization.

Future improvements

Possible enhancements include:

- Adding more examples of `article`/`aside` usage (blog posts, news items, side notes). ------- Maybe -----------
- Improving responsive behavior with flexbox or grid layouts.
- Expanding the documentation with more diagrams or code comments.
```
Questions to guide an effective README

Project basics
  - What is the name of the project?
  - In one or two sentences, what problem does it solve or what concept does it demonstrate?
  - Who is the intended audience (beginners, intermediate learners, etc.)?

Purpose and learning goals
  - What are the main concepts or skills this project teaches?
  - Why did you choose to focus on these particular containers or features (here: `article`, `aside`, spacer)?
  - What should someone know after reading/using this project that they might not know before?

Structure and files
  - What are the main HTML files, and how are they related (e.g., `index.html`, `about.html`, `gallery.html`)?
  - What directories exist (`css`, `logo`, `tags`, etc.), and what role does each one play?
  - Are there any important naming conventions or file relationships worth calling out?

Key technical details
  - What key HTML elements or patterns are being demonstrated (e.g., `article`, `aside`, spacer divs)?
  - How is layout handled (flexbox, grid, floats, simple block layout)?
  - What CSS files are used, and which pages rely on which stylesheets?

Usage / how to run
  - What steps are required to see the project in a browser (clone, open `index.html`, run a local server)?
  - Are there any tools or dependencies the user might need (even something simple like “use a modern browser”)?
  - Are there any recommended workflows (e.g., open in VS Code Live Server)?

Examples and visuals
  - Are there screenshots, diagrams, or sample snippets that help explain the concept?
  - How do the images in the `tags` folder connect to the explanation in the HTML?

Status and roadmap
  - Is this project finished, or is it a work in progress?
  - What improvements or extensions do you plan (or would like others) to make?
  - Are there known limitations or things intentionally left simple for teaching purposes?

Credits and context
  - Did you use any references, tutorials, or design inspirations worth mentioning (without copying content)?
  - Is there any licensing information or attribution needed?
