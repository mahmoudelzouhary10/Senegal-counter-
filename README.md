<div align="center">

# Count Up — Live Countdown Timer

**A lightweight, real-time countdown web app built with vanilla JavaScript.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Live](https://img.shields.io/badge/Live-Demo-2ECC71)](https://mahmoudelzouhary10.github.io/Senegal-counter-/)

[**🔗 Live demo**](https://mahmoudelzouhary10.github.io/Senegal-counter-/)

</div>

---

## About

A small, focused web app that counts down to a fixed target date and updates **live, every second** — days, hours, minutes, and seconds. Originally built around a football-themed event, it's a clean example of working with dates, timers, and live DOM updates in plain JavaScript.

The goal was to keep it dependency-free: no frameworks, no libraries — just HTML, CSS, and JavaScript.

---

## What it does

- **Live countdown** to a target date, refreshing every second
- **Day / hour / minute / second** breakdown, calculated from the time difference
- **Themed, image-based UI** with a clean centered layout
- **Zero dependencies** — runs anywhere, instantly

---

## Tech stack

| Layer | Choice |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 |
| Logic | Vanilla JavaScript (`setInterval`, `Date` math, DOM updates) |
| Hosting | GitHub Pages |

---

## How it works

The core is a timer that fires once per second, takes the difference between the current time and the target date, and converts those milliseconds into days, hours, minutes, and seconds before writing them back to the page. It's a compact demonstration of date arithmetic and keeping a UI in sync with real time.

---

## Run locally

```bash
git clone https://github.com/mahmoudelzouhary10/Senegal-counter-.git
cd Senegal-counter-
# open index.html in your browser — no build step needed
```

---

## Author

**Mahmoud Elzouhary** — Web & Mobile Developer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mahmoud-elzouhary)
