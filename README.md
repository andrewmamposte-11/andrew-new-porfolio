# Andrew Mamposte – Online Portfolio

Hands-on Activity 7.1 (Introduction to Computing, Unit 8: Web Design Basics – HTML and CSS).
A one-page personal portfolio built with HTML and an external CSS stylesheet.

## Folder contents

```
andrew-mamposte-portfolio/
├── index.html      The whole website (Home, About, Skills, Certificates, Portfolio, Contact sections)
├── style.css       External stylesheet (all colors, layout, and animations)
├── README.md       This file
└── images/
    ├── profile.jpg            Profile picture (used in Home and About)
    ├── certificate-csharp.jpg C# Programming 1 certificate (from the uploaded PDF)
    └── certificate-c.jpg      C Programming 1 certificate (from the uploaded PDF)
```

## How to open

Keep all files and the `images` folder together, then double-click `index.html`.
Do not move `index.html` or `style.css` out of the folder, or the design and pictures will disappear.

## How to edit

- Open the folder in Visual Studio Code, or open a file with Notepad. Do not use Word.
- Text (bio, education, projects, contact): edit `index.html`.
- Colors and fonts: edit the `:root { ... }` block at the top of `style.css`.
- After saving, press F5 in the browser to refresh (Ctrl + F5 if nothing changes).

## How to replace the images

1. Prepare your picture (JPG recommended).
2. Rename it to match the file you are replacing, for example `profile.jpg`.
3. Put it in the `images` folder and choose "Replace the file".

The profile picture must stay named `profile.jpg`. To change a certificate, replace `certificate-csharp.jpg` or `certificate-c.jpg` the same way. 

## Features

- Dark theme with cyan, purple, and pink accents
- Animated background, floating profile picture, moving gradient name
- Scroll effects: progress bar, items that fade in, back-to-top button
  (progress bar and fade-in work in Chrome and Edge; other features work in all browsers)
- Certificate cards: click a card to open an enlarged certificate with details (CSS only)
- Mobile-friendly layout
- Contact form opens the visitor's email app (plain HTML cannot send emails by itself)

## HTML and CSS concepts used

Elements and attributes, head and body, external stylesheet (`<link>`), classes, an ID (`#contact-form`),
pseudo-classes (`a:link`, `a:visited`, `a:hover`, `a:active`), block and inline elements, and the box model.

## Author

Andrew Mamposte – BSIT, Mindoro State University (MINSU)
