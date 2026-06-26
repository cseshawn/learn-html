# 📖 Learn HTML — From Zero to Web Developer

> A beginner-friendly, structured guide to mastering HTML — the foundation of every website on the internet.

![HTML5](https://img.shields.io/badge/HTML-5-E34F26?style=flat&logo=html5&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-orange)

---

## 🌐 What is HTML?

**HTML (HyperText Markup Language)** is the standard language used to create and structure content on the web. It forms the skeleton of every webpage — from text and images to links, forms, and multimedia.

Whether you're building your first website or strengthening your fundamentals, this repository will guide you step by step.

---

## 🗂️ Repository Structure

```
learn-html/
│
├── 01-basics/
│   ├── hello-world.html          # Your very first HTML page
│   ├── structure.html            # DOCTYPE, html, head, body
│   └── headings-paragraphs.html  # h1–h6, <p> tags
│
├── 02-text-formatting/
│   ├── bold-italic.html          # <b>, <i>, <strong>, <em>
│   ├── lists.html                # Ordered & unordered lists
│   └── links.html                # Anchor tags and href
│
├── 03-media/
│   ├── images.html               # <img> tag, alt, src
│   ├── audio-video.html          # Embedding media
│   └── iframe.html               # Embedding other pages
│
├── 04-tables/
│   ├── basic-table.html          # tr, th, td
│   └── advanced-table.html       # colspan, rowspan, caption
│
├── 05-forms/
│   ├── basic-form.html           # input, label, button
│   ├── form-types.html           # text, email, password, radio, checkbox
│   └── form-validation.html      # required, pattern, min/max
│
├── 06-semantic-html/
│   ├── semantic-layout.html      # header, nav, main, footer
│   ├── article-section.html      # article, section, aside
│   └── accessibility.html        # ARIA roles and best practices
│
├── 07-projects/
│   ├── personal-portfolio/       # Mini portfolio page
│   ├── contact-form/             # Fully styled contact form
│   └── product-landing-page/     # A simple landing page
│
└── README.md
```

---

## 📚 Learning Roadmap

Follow the topics in order for the best learning experience:

| #   | Topic                        | Key Tags                                    | Status          |
| --- | ---------------------------- | ------------------------------------------- | --------------- |
| 1   | HTML Basics & Page Structure | `<!DOCTYPE>`, `<html>`, `<head>`, `<body>`  | ✅ Start here   |
| 2   | Text & Formatting            | `<h1>`–`<h6>`, `<p>`, `<strong>`, `<em>`    | 📝 Beginner     |
| 3   | Links & Navigation           | `<a>`, `href`, `target`                     | 📝 Beginner     |
| 4   | Images & Media               | `<img>`, `<audio>`, `<video>`               | 📝 Beginner     |
| 5   | Lists                        | `<ul>`, `<ol>`, `<li>`                      | 📝 Beginner     |
| 6   | Tables                       | `<table>`, `<tr>`, `<th>`, `<td>`           | 🔶 Intermediate |
| 7   | Forms & Inputs               | `<form>`, `<input>`, `<select>`, `<button>` | 🔶 Intermediate |
| 8   | Semantic HTML5               | `<header>`, `<nav>`, `<main>`, `<footer>`   | 🔶 Intermediate |
| 9   | Accessibility (a11y)         | `alt`, `aria-*`, `role`                     | 🔷 Advanced     |
| 10  | Mini Projects                | Portfolio, Contact Form, Landing Page       | 🏆 Apply it all |

---

## 🚀 Getting Started

### Prerequisites

You only need two things:

- A **text editor** — [VS Code](https://code.visualstudio.com/) is recommended (free)
- A **web browser** — Chrome, Firefox, or Edge

### Run Locally

1. **Clone this repository:**

   ```bash
   git clone https://github.com/cseshawn/learn-html.git
   ```

2. **Open the project folder:**

   ```bash
   cd learn-html
   ```

3. **Open any `.html` file in your browser:**
   - Double-click a file in your file explorer, or
   - In VS Code, right-click the file → **Open with Live Server** (requires the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer))

> 💡 **Tip:** Install the **Live Server** extension in VS Code to automatically refresh your browser when you save changes.

---

## 💡 Quick Example

Here's your very first HTML page:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My First HTML Page</title>
  </head>
  <body>
    <h1>Hello, World! 👋</h1>
    <p>Welcome to my first HTML page. I'm learning web development!</p>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML"
      >Learn more about HTML</a
    >
  </body>
</html>
```

Save this as `index.html` and open it in your browser. That's it — you've written your first webpage!

---

## 📖 Recommended Resources

| Resource         | Description                        | Link                                                       |
| ---------------- | ---------------------------------- | ---------------------------------------------------------- |
| MDN Web Docs     | The most complete HTML reference   | [Visit](https://developer.mozilla.org/en-US/docs/Web/HTML) |
| W3Schools HTML   | Beginner-friendly tutorials        | [Visit](https://www.w3schools.com/html/)                   |
| freeCodeCamp     | Free interactive HTML course       | [Visit](https://www.freecodecamp.org/)                     |
| The Odin Project | Structured full web dev curriculum | [Visit](https://www.theodinproject.com/)                   |
| HTML Validator   | Check your HTML for errors         | [Visit](https://validator.w3.org/)                         |

---

## 🧠 Tips for Learning HTML

- **Practice every day** — even 20 minutes a day adds up fast.
- **Break things on purpose** — removing or changing tags helps you understand what they do.
- **Use browser DevTools** — press `F12` to inspect any webpage's HTML.
- **Build something real** — the mini projects at the end will cement your understanding.
- **Don't memorize, understand** — HTML is about structure and meaning, not just syntax.

---

## 🤝 Contributing

Contributions are welcome! If you'd like to add examples, fix errors, or improve explanations:

1. Fork this repository
2. Create a new branch: `git checkout -b feature/your-topic`
3. Commit your changes: `git commit -m "Add: new example for forms"`
4. Push to the branch: `git push origin feature/your-topic`
5. Open a **Pull Request**

Please keep code examples clean, well-commented, and beginner-friendly.

---

## 📄 License

This project is licensed under the **MIT License** — feel free to use, share, and modify it for your own learning journey.

---

## 👤 Author

**cseshawn**

- GitHub: [@cseshawn](https://github.com/cseshawn)

---

<p align="center">
  Made with ❤️ for beginners learning to build the web.<br/>
  <strong>Happy coding! 🚀</strong>
</p>
