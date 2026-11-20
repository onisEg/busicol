# Busicol · Business Landing Page

A frontend training project that presents a fictional consultancy through solutions, company information, recent work and testimonials.

[Open the live demo](https://oniseg.github.io/busicol/) · [View screenshot](https://raw.githubusercontent.com/onisEg/resume/23df91e50f87b60e1360d79edcc24cf77eb09b07/public/projects/busicol.webp)

## Reading the layout

1. The header and hero introduce the business. The solutions section uses illustrations, while the about section and counters break up the page before the work gallery.
2. The lower sections contain a financial-services feature, a testimonial and a contact call to action. Section order and display copy are defined directly in the HTML.
3. The stylesheet has a narrow-screen breakpoint at 767px. To adjust a gallery item, trace its markup to the matching gallery rules and image in the asset directory.

## Run locally

From the repository root, serve the checked-in files with Python 3:

```sh
python -m http.server 8000
```

Open [localhost:8000](http://localhost:8000/) to load `index.html`. The browser reads the HTML, styles and assets directly. On Windows, `py -m http.server 8000` starts the same server.

## Source guide

| File or directory | What to look for |
| --- | --- |
| [index.html](index.html) | Single page with solutions, counters, gallery, testimonial and contact sections. |
| [style.css](style.css) | Section layout, visual treatments and the mobile breakpoint. |
| [imgs](imgs) | Illustrations, work images and other page assets. |

## Manual walkthrough

Compare the solutions row and recent-work gallery at desktop width and at 767px. Check image crops and text wrapping after changing a headline. The page serves as a layout exercise; the repository links the Bootstrap bundle as a stylesheet, so the custom CSS is the place to start when tracing the layout.
