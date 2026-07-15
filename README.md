# Personal Profile Page

A semantic, accessible personal profile/portfolio page built to practice HTML5 structure and accessibility fundamentals.

🔗 **Live Demo:** [https://github.com/thevelans/WebDevelopment_Projects]

## What it does

Displays a developer's bio, skills, featured projects, and contact info in a single clean page, using proper semantic HTML so the content is navigable by screen readers and easy for search engines to parse.

## Built With

- HTML5 (semantic elements)
- CSS3

## Features

- Semantic layout using `header`, `nav`, `main`, `section`, `article`, `footer`
- Accessible navigation with `aria-label` and heading hierarchy
- Skills list, project highlights, and contact section
- Responsive image and flexible skill tags

## What I Learned

I learned that "accessible HTML" isn't just about adding `alt` text — it's about choosing the right semantic element for each section (`article` for a project, `address` for contact info) so assistive technology can actually understand the page structure, not just read the text.

## Challenges & Solutions

My first draft used `div`s for everything, which meant a screen reader had no way to distinguish sections. I refactored to use semantic tags and added `aria-labelledby` on each section pointing to its heading, which ties the section and its title together for assistive tech.

## How to Run Locally

```bash
git clone https://github.com/yourusername/profile-page.git
cd profile-page
open index.html
```
