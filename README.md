# Odin Signup Page

A responsive signup page built with HTML and CSS as part of The Odin Project curriculum.

---

## Features

- **Two-column layout** using Flexbox — an image/branding panel on the left and a form panel on the right
- **Custom font** (`Norse-Bold`) loaded via `@font-face` for the Odin logo text
- **Background image** with `cover` sizing and centered positioning on the branding panel
- **Semi-transparent logo band** overlaid on the background image using `rgba`
- **Signup form** with the following fields:
  - First Name and Last Name
  - Email and Phone Number
  - Password and Confirm Password
- **Input validation styling** — blue ring on focus, red border on invalid input
- **Create Account button** with custom green styling
- **Login link** for existing users, styled in matching green
- **Sectioned left panel** — intro text, form, and action button each occupy their own flex child with alternating background colors

---

## Built With

- HTML5
- CSS3 (Flexbox, pseudo-classes, `@font-face`)

---

## Project Structure

```
project/
├── index.html
├── style.css
├── background.jpg
├── odin-lined.png
└── font/
    └── Norse-Bold.woff
```

---
Photo by Halie West on Unsplash

## What I Learned

- Structuring a two-column layout with Flexbox
- Using `@font-face` to load custom fonts
- Styling form inputs with `:focus` and `:invalid` pseudo-classes
- Layering content over background images with semi-transparent overlays
- Targeting specific flex children with `:nth-child` selectors
