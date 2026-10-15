Seven Hills Wai website source package

Files:
- index.html: website markup
- styles.css: extracted CSS styles
- script.js: extracted inline JavaScript in original order

Open index.html in a browser. GSAP and ScrollTrigger are loaded from CDN in the HTML head, and Google Fonts are loaded from Google Fonts, so those features need an internet connection.

Any image assets embedded directly in the HTML/JavaScript remain included. Images referenced by filename (for example background-hills.jpg, rooftop-bar.jpg, gym.jpg, horse-arena.jpg, pool.jpg, more.jpg) are not included unless separately supplied; replace those URLs or add the corresponding image files if needed.
