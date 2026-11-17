# GeekHub — blog page layout

A responsive single-page layout of a GeekHub-style news blog, built as practice for an
HTML5 & CSS3 course (2018). Plain HTML and CSS, no build step and no JavaScript.

## What's on the page

- Header with the logo and the main menu
- Two news posts with banners and "Continue Reading" buttons
- Sidebar: search, a list of courses, an email subscription form, partner banners
- Previous / Next pager and a footer

## Run it

Open `index.html` in a browser — that's it. Or serve the folder locally:

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## Structure

```
.
├── index.html     # The page
├── style.css      # All styles
└── images/        # Logo, favicon, post banners, partner banners, subscribe icons
```

## What it practices

- Semantic HTML5: `header`, `nav`, `main`, `article`, `aside`, `section`, `footer`
- Two-column layout with CSS Grid that collapses into one column on tablets and phones
- Flexbox for the header, menu, pager and footer
- Three breakpoints: 768 px, 658 px and 539 px
- Accessible forms: labelled inputs, a real submit button, visible keyboard focus
- Web font (Open Sans) loaded from Google Fonts with `display=swap`

## Notes

- Menu, course and pager links are placeholders (`#`), and the forms are not wired to a backend:
  this is a layout exercise.
- GeekHub, GeekTalks, GeekLabs and their logos belong to their owners. This is a non-commercial
  learning project, not affiliated with them.

Made by [Ilya Bielov](https://www.facebook.com/MrBiela).
