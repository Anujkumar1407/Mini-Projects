# Mini Projects Collection

![Mini Projects](https://img.shields.io/badge/collection-mini_projects-blue)
![Status](https://img.shields.io/badge/status-active-green)

A curated set of small, self-contained web demos built with HTML, CSS and JavaScript. Each project is a single-page demo you can open in your browser or serve locally.

## Projects Overview

- **Analog Clock** — [Open demo](Analog Clock/index.html)  
  Classic analog clock built with CSS transforms and JS time updates.
- **Analog Clock 2** — [Open demo](Analog Clock 2/index.html)  
  Alternate styling and smoother animations.
- **Calculator** — [Open demo](Calculator/index.html)  
  Basic calculator (addition, subtraction, multiplication, division) implemented in vanilla JS.
- **Rock Paper Scissors** — [Open demo](Rock Paper Scissors/index.html)  
  Interactive game with score tracking and simple UI.
- **Text To Voice** — [Open demo](Text To Voice/index.html)  
  Text-to-speech example using the Web Speech API (speech synthesis).
- **To Do List** — [Open demo](To Do List/index.html)  
  Minimal todo app with add/remove and local UI; see `Assets/` for supporting images.

## Quick Preview

Open any project's `index.html` directly in your browser, or run a simple local server for a better experience (recommended when files are opened from OneDrive or when using modules).

Using Python (works on Windows, macOS, Linux):

```bash
cd "Mini Projects"
python -m http.server 8000
# then open http://localhost:8000/ in your browser
```

Using VS Code: install the **Live Server** extension, then right-click an `index.html` and choose **Open with Live Server**.

## Notes & Tips

- If a demo depends on microphone or speech APIs, allow the browser permissions when prompted.  
- If pages look broken, try serving via a local server instead of opening files directly.  
- Filenames and folders contain spaces. If a link doesn't work in your environment, replace spaces with `%20` in the URL.

## Contributing

Improvements, visual polish, and small feature additions are welcome. Suggested workflow:

1. Fork this repo
2. Create a topic branch for your changes
3. Open a PR with a short description of what you changed

## License

This collection is provided without an explicit license. Add a `LICENSE` file if you want to choose one (MIT, Apache, etc.).

---
