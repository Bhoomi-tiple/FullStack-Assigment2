# HTML Best Practices: Good vs Bad HTML

A simple HTML5 assignment demonstrating the difference between poorly structured HTML and well-structured, accessible, and responsive HTML through a college website example.

## 📌 About the Project

This project contains two HTML files that demonstrate how HTML structure and coding practices affect the readability, accessibility, maintainability, and responsiveness of a webpage.

The same college website concept is implemented in two ways:
- **Bad HTML:** Uses generic containers and a basic layout with limited accessibility and responsiveness.
- **Good HTML:** Uses semantic HTML5 elements, improved styling, accessibility attributes, and responsive design.

## 📂 Project Structure

```text
FullStack-Assigment2/
│
├── bad.html
├── good.html
└── README.md
```

## 🔴 Bad HTML — `bad.html`

The first file demonstrates a basic webpage structure with several areas that can be improved.

**Key observations:**
- Uses generic `<div>` elements for the header, navigation, content, and footer.
- Has limited accessibility support.
- Does not include character encoding or viewport metadata.
- Uses a simple layout without responsive media queries.
- Has less descriptive document metadata.

These choices make the structure less meaningful and the page less adaptable.

## 🟢 Good HTML — `good.html`

The second file improves the webpage by following modern HTML5 practices.

**Improvements include:**
- **Semantic HTML5:** Uses `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>`.
- **Accessibility:** Includes descriptive navigation labels and section headings connected through ARIA attributes.
- **Responsive Design:** Uses viewport metadata and a media query for smaller screens.
- **Better Styling:** Applies consistent spacing, colors, typography, and card-based sections.
- **Document Metadata:** Includes character encoding and a descriptive page title.
- **Improved Content Structure:** Organizes courses and information into meaningful sections.

## ⚖️ Good HTML vs Bad HTML

| Feature | Bad HTML | Good HTML |
|---|---|---|
| Page structure | Generic `<div>` containers | Semantic HTML5 elements |
| Accessibility | Limited | Improved with descriptive labels |
| Responsive design | No media query | Media query for smaller screens |
| Metadata | Basic title | Title, charset, and viewport |
| Content organization | Basic content boxes | Structured sections and articles |
| Styling | Simple layout | Consistent, responsive styling |

## 🛠️ Technologies Used

- **HTML5:** Defines the structure and content of the webpage.
- **CSS3:** Controls colors, typography, spacing, layout, and responsive styling.
- **Media Queries:** Adapt the layout for smaller screens.
- **ARIA Attributes:** Provide additional accessibility information where appropriate.

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Bhoomi-tiple/FullStack-Assigment2.git
   ```

2. Open the project folder:

   ```bash
   cd FullStack-Assigment2
   ```

3. Open `bad.html` or `good.html` in your web browser.

No additional dependencies or installation are required.

## 🎯 Learning Outcomes

Through this assignment, I explored:
- The importance of semantic HTML5 elements.
- How document metadata supports browser rendering and responsive layouts.
- The role of accessibility attributes in improving webpage usability.
- How CSS and media queries improve presentation across screen sizes.
- Why clean, structured HTML is easier to understand and maintain.

## 👩‍💻 Author

**Bhoomi Tiple**

GitHub: [Bhoomi-tiple](https://github.com/Bhoomi-tiple)

---

*This project was created as part of a Full Stack Development assignment to demonstrate HTML5 structure and best practices.*
