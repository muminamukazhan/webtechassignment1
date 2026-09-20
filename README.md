# HTML & CSS Basics — Assignment #1

A multi-page website built for the Frontend course (Assignment #1: HTML & CSS Basics), completed individually.

**Author:** Mumina Mukazhan
**Group:** SE-2530
**University:** Astana IT University

🔗 **Repository:** https://github.com/muminamukazhan/webtechassignment1
🔗 **Live site:** https://muminamukazhan.github.io/webtechassignment1/

## Description

A multi-page site covering five HTML/CSS tasks: a personal page, a `<div>`-based layout with floats, a tribute page, a table-and-form page, and a midterm project wireframe. All pages share a common navbar for easy navigation between tasks.

## Repository structure

```
├── index.html            # Task 1 — personal page (profile card, lists, image)
├── style1.css
├── task2.html            # Task 2 — layout with <div> + float/position (no Flexbox/Grid)
├── style2.css
├── exercise1/
│   ├── index.html        # Task 3 — tribute page (Audrey Hepburn)
│   ├── styles.css
│   ├── hero.jpg
│   └── portrait.jpg
├── task4.html            # Task 4 — grades table + feedback form
├── task4.css
├── task5.html            # Task 5 — midterm project wireframe
└── README.md
```

## Tasks

| # | Task | Files | What's implemented |
|---|------|-------|---------------------|
| 1 | Personal page | `index.html`, `style1.css` | h1/h2, 2 paragraphs, `ol`/`ul` (4+ items each), image with `alt`, 2 links, profile card, element/class/id selectors |
| 2 | Div-based layout | `task2.html`, `style2.css` | header, navbar, sidebar (floated left), content (floated right), footer — built without Flexbox/Grid |
| 3 | Tribute page | `exercise1/index.html`, `exercise1/styles.css` | Tribute to Audrey Hepburn: headings, lists of career highlights and legacy, portrait image, links, "Learn More" button, 2 Google Fonts |
| 4 | Table & form | `task4.html`, `task4.css` | Grades table (rowspan/colspan, alternating rows, highlight class, id-styled heading) + feedback form (text/email/select/radio/textarea/submit) |
| 5 | Midterm: wireframe | `task5.html` | Project topic, sitemap and wireframes |

## Run locally

1. Clone the repository:
```
   git clone https://github.com/muminamukazhan/webtechassignment1.git
```
2. Open `index.html` in a browser (double-click, or use the Live Server extension in VS Code).
3. Navigate between tasks using the navbar at the top of each page.

## Technologies

- HTML5
- CSS3 (Flexbox — Task 1/3/4, float/position — Task 2)
- Google Fonts (Bodoni Moda, Lora, Playfair Display, Nunito Sans)

## Deployment

The site is published via **GitHub Pages** (Settings → Pages, `main` branch, root folder), with `index.html` as the entry point.
