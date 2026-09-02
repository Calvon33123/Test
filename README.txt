SafeReport - Separate Page Stylesheets

Each HTML page now depends only on its own CSS file:

html/index.html     -> css/login.css
html/home.html      -> css/home.css
html/report.html    -> css/report.css
html/myreports.html -> css/myreports.css
html/profile.html   -> css/profile.css

The original animation keyframes and animation timings are preserved in each relevant stylesheet.
styles.css is no longer required by any HTML page.
