# 🎬 Factoría – HTML & CSS Project

This project is a static website built using **HTML and CSS** as part of a front‑end learning exercise.  
The site simulates a small movie platform called **Factoría**, featuring multiple pages, a consistent design system, and a clean, user‑friendly layout.

---

## 📁 Project Structure

The website includes **four main pages**:

### 1. `index.html` – Home Page
- Highlights four featured movies.
- Each movie card includes an image, title, description, and age tag.
- The Batman card links to the detail page.
- Shared header and footer across the site.

### 2. `listado.html` – Movies Listing
- Displays all movies in a responsive grid layout.
- Each card includes metadata and a button for more details.

### 3. `detalle.html` – Movie Detail Page
- Dedicated page for the movie *Batman*.
- Includes:
  - Large poster image  
  - Title, tagline, metadata  
  - Full description  
  - Embedded YouTube trailer  
  - Back‑to‑home button  

### 4. `contacto.html` – Contact Form
- Contains a fully styled form using **GET** method.
- Includes 6 fields:
  - Name  
  - Surname  
  - Email  
  - Phone  
  - Contact reason (select)  
  - Message (textarea)  
- Clean, centered layout with a card‑style form container.

---

## 🎨 Styling (CSS)

All styles are defined in `styles.css`, including:

- Global layout using Flexbox  
- Responsive movie grid  
- Card components with rounded corners  
- Text truncation using `-webkit-line-clamp`  
- Styled form inputs and buttons  
- Footer fixed at the bottom using a flex layout:
  ```css
  html, body { height: 100%; }
  body { display: flex; flex-direction: column; }
  main { flex: 1; }

## Features
Fully navigable multi‑page structure

Consistent header and footer

Embedded video trailer

Responsive layout

Clean and accessible form

Organized folder structure (src/images/...)

🚀 How to Run
Simply open index.html in any modern browser.
No dependencies or build tools required.

📚 Learning Outcomes
Through this project, I practiced:

Semantic HTML structure

CSS layout techniques (Flexbox, Grid)

Component‑based styling

Form creation and GET method handling

Embedding multimedia content

Maintaining visual consistency across pages

Iterative refinement and debugging

🔄 Personal Reflection
Working on this project helped me understand the value of iterative development: building a first version, reviewing it, refining it, and improving it step by step.
I learned to pay attention to visual balance, spacing, alignment, and the overall user experience.
Fixing layout issues, integrating the video, and polishing the form taught me how small adjustments can significantly improve the final result.

Overall, I’m satisfied with the outcome: the site is clean, functional, visually consistent, and meets all the requirements of the assignment.

## Author
Karina Lorenzo
Front‑end student and creative contributor.