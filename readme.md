# VS CODE CLONE
## [Live@]()
## Laptop
![image](./Laptop.png)
## Mobile Phone
![image](./MobilePhone.png)
## Tablet
![image](./Tablet.png)

## HTML Syntax Summary
##### <p>This HTML file builds a VS Code–themed landing page clone using Tailwind CSS for styling and Font Awesome for icons. It’s a responsive dark-mode promotional page with nav, hero section, feature cards, banners, language and extension showcases, and a footer.<p>

```
<!DOCTYPE html> — HTML5 document declaration
<html lang="en"> — English language page

<head> — metadata + imports
  - UTF-8 charset + viewport for responsiveness
  - Tailwind CSS via CDN
  - Font Awesome icons via CDN
  - <title>VS Code Clone</title>
</head>

<body class="bg-[#0d1117]"> — dark theme background

<nav> — top navigation bar
  - Left: logo + “Visual Studio Code” + menu links (Docs, Updates, Blog, etc.)
  - Right: theme icon, search box, “Download” button, hamburger menu for mobile
</nav>

<div> — version banner
  - Shows latest VS Code release info with close (x) icon
</div>

<main>
  <section> — hero section
    - Title: “The open source AI code editor”
    - “Download for Windows” button
    - License + privacy info
    - Hero image
    - 3 feature cards: models, codebase expert, team AI
  </section>

  <section> — “Use AI for free” banner
    - Text + Try Free button
  </section>

  <section> — feature sections
    - “Agent mode”, “Next edit suggestions” with images
  </section>

  <section> — extensions grid
    - Shows popular VS Code extensions (Python, Jupyter, GitLens, etc.)
  </section>

  <section> — “Code in any language”
    - Language logos (JS, TS, Python, C++, HTML, etc.)
  </section>

  <section> — customization + remote coding
    - Info about themes, profiles, GitHub Codespaces, etc.
  </section>

  <section> — “Rich features” grid
    - Cards for terminal, debugging, version control, tasks, themes, etc.
  </section>

  <section> — footer
    - Social media icons + support/privacy/terms links + Microsoft logo
  </section>
</main>
</body>
</html>
```


