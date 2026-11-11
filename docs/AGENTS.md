# Project Instructions

- This is a static HTML/CSS site. The main page is `Liber-Tea.html`; its stylesheet is `Styles/Styles.css`.
- For font-family changes, inspect the existing declarations and confirm the intended font and weight before editing. The stylesheet currently lists `"FS Sinclair", "Swiss 721", sans-serif` for `.box`.
- Local Swiss 721 files are `Styles/swiss-721/Swiss721Bold.ttf` and `Styles/swiss-721/Swiss721Black.ttf`. If declaring them with `@font-face`, use URLs relative to `Styles/Styles.css` and match each declared weight to the actual font file; do not assume a regular weight is available.
- Keep font rules in `Styles/Styles.css` and preserve its four-space indentation. Avoid unrelated layout or color changes when working on typography.
- No build or test runner is configured. Verify font changes by opening `Liber-Tea.html` in a browser, checking the computed font and weight, and confirming the local font files load without errors.