# HTML Website Development Assignment

## Question 1: Website Creation

I created a personal portfolio website showcasing my background, education, skills, and a contact form. The content includes:

- An "About Me" section with a brief bio and a placeholder profile image.
- An "Education" section with an ordered list of educational milestones.
- A "Skills" section presented in a table format.
- A "Contact" section with a form for name, email, and message.
- An aside for additional information.
- A footer with copyright, address, and date.

The website is contained in a single `index.html` file for simplicity.

## Question 2: HTML Elements

1. **Five elements I found most challenging to implement:**
   - `<form>`: Coordinating nested inputs, labels, and understanding attributes like `action` and `method`.
   - `<table>`: Structuring with `<thead>`, `<tbody>`, `<tr>`, `<th>`, and `<td>`.
   - `<textarea>`: Sizing appropriately with `rows` and `cols`.
   - `<meta>`: Selecting correct attributes like `charset` and `viewport`.
   - `<address>`: Remembering its semantic purpose for contact info.

2. **Use of semantic elements:**
   - `<header>` for top section with title and navigation.
   - `<nav>` for navigation links.
   - `<main>` for primary content.
   - `<section>` for logical content blocks (About, Education, Skills, Contact).
   - `<article>` inside About for self-contained content.
   - `<aside>` for supplementary info.
   - `<footer>` for copyright and contact.

3. **Most useful element for organizing layout:**  
   - `<section>` because it allows grouping related content into distinct blocks, making navigation easier.

## Question 3: HTML Attributes

1. **Three essential attributes:**
   - `href` → used in `<a>` for navigation links.
   - `id` → unique identifiers for sections (internal linking).
   - `src` → in `<img>` to load profile image.

2. **Use of `class` and `id`:**
   - `class` → used to group elements for potential styling (`class="section"`).
   - `id` → used for unique identifiers (`id="about"`), mainly for navigation.

3. **Most useful attribute for user experience:**  
   - `placeholder` → guides users in forms, e.g., "Your Name", making the form intuitive.

## Question 4: Development Process

1. **Planning:**  
   - Sketched a wireframe on paper, starting with overall layout (header, main, footer), then breaking main into sections, listing elements needed.

2. **Testing & Debugging:**  
   - Opened HTML in browser after major changes.  
   - Used W3C HTML Validator to fix errors like unclosed tags.

3. **Challenges & Solutions:**  
   - Improper nesting (`<tr>` not closed) → fixed by consistent indentation and validation.  
   - Ensuring self-closing tags (`<br>`) were correct.

## Question 5: Git & GitHub Implementation

1. **Git commands used:**  
   - `git init`  
   - `git add .`  
   - `git commit -m "message"`  
   - `git remote add origin [url]`  
   - `git push -u origin main`

2. **Commits & strategy:**  
   - 5 commits: "Initial HTML structure", "Added About and Education", "Implemented Skills table", "Added Contact form", "Final touches and footer"

3. **Importance of version control:**  
   - Tracks changes, allows reverting, facilitates collaboration, and provides debugging history.

## Question 6: Code Quality & Best Practices

1. **Ensuring valid HTML:**  
   - Ran code through W3C Validator, fixed missing attributes and unclosed tags.

2. **Best practices followed:**  
   - Proper indentation, semantic elements over `<div>`, added comments, avoided deprecated tags.

3. **Improvements if more time:**  
   - Add multimedia (`<audio>`, `<video>`), expand content (projects), improve accessibility with `aria-label` attributes.

## Student Details

**Student Name:** Edwin Mudenda  
**Student ID:** 2503387691
**GitHub Repository:** https://github.com/edwin-zm/html-portfolio
