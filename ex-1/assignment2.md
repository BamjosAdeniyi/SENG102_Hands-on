# Assignment: Understanding Semantic HTML

## 1. What is Semantic HTML?
Semantic HTML refers to the use of HTML elements that clearly describe their meaning and purpose within a webpage. Instead of using generic tags like `<div>` for everything, semantic elements are used to define the structure of the content clearly.

In simpler words, these elements describe the type of content they are supposed to contain. This tells both the browser and the developer exactly what the code is intended to do, improving readability and accessibility.

---

## 2. Importance of Semantic HTML
Using semantic tags is a best practice for several reasons:

* **Accessibility:** It helps screen readers interpret the content for visually impaired users.
* **SEO (Search Engine Optimization):** Search engines can better understand the structure and importance of your content.
* **Readability:** It makes the code cleaner and easier for other developers to read.
* **Maintenance:** A well-structured page is much easier to update and maintain over time.
* **Organization:** It provides a logical, clear structure to web pages.

---

## 3. Core Semantic Elements


| Element | Description |
| :--- | :--- |
| `<header>` | The introductory part of a page or a specific section. |
| `<nav>` | Contains navigation links (menus, sidebars). |
| `<main>` | Defines the unique, primary content of the document. |
| `<section>` | Splits a page into different thematic chapters or sections. |
| `<article>` | Independent content that can stand alone (e.g., a blog post). |
| `<aside>` | Content placed "aside" from the main text (e.g., sidebars). |
| `<footer>` | The bottom of a page/section containing contact or copyright info. |
| `<form>` | Defines a section for user input and interactive controls. |
| `<table>` | Used to organize data into rows and columns. |
| `<details>` | Defines additional details that the user can hide or view. |
| `<summary>` | Defines a visible heading for the `<details>` element. |
| `<figure>` | Used to encapsulate media like illustrations or photos. |
| `<figcaption>` | Provides a descriptive caption for a `<figure>`. |
| `<mark>` | Used to highlight specific text for reference. |

---

## 4. Tag Comparisons

### **Bold vs. Strong**
* **`<b>` Tag:** Used to make text bold for **visual presentation** only. It is purely a styling element and adds no special meaning.
* **`<strong>` Tag:** Indicates that the text is **important**. While it appears bold, its main purpose is semantic; search engines and screen readers treat it as high-priority content.

### **Italic vs. Emphasis**
* **`<i>` Tag:** Displays text in italics for **stylistic purposes**. It does not add extra meaning to the text.
* **`<em>` Tag:** Used to **emphasize** text. It indicates that the words should be stressed. Screen readers give special attention to `<em>` content.

---