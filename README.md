# 🎴 Animated CV / Resume Generator

A stunning, single-file animated CV built with **vanilla HTML, CSS & JavaScript** —
no frameworks, no build step. It doubles as a **resume generator**: open the
built-in editor, edit your details live, and download a standalone HTML CV.

![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JS](https://img.shields.io/badge/Vanilla_JS-F7DF1E?logo=javascript&logoColor=black)
![No deps](https://img.shields.io/badge/dependencies-none-success)

## ✨ Highlights
- Animated **aurora** background, mouse **spotlight**, and gradient text
- **Typing** effect cycling through roles
- **Scroll-reveal** animations (IntersectionObserver)
- Interactive **project cards** with a cursor-tracking glow
- Built-in **CV generator panel** — edit fields live, then **Download as HTML** or **Save as PDF**
- Fully **responsive** + a clean **print** stylesheet
- One file, zero dependencies

## 🚀 Use it
Just open `index.html` in a browser. Click **✦ Customize CV** (bottom-right) to
edit your name, roles, about, location and links, then download your own copy.

## 📂 Files
- **`index.html`** — the personal CV (animated, single file)
- **`generator.html`** — a blank reusable CV generator: fill the form, edit live, and download a standalone HTML CV for anyone

## 🛠 How it works
Content (skills, projects, roles) lives in small JS arrays and is rendered into
the page. `generator.html` exposes that data through a live editor form so it can
build a CV for any person.
