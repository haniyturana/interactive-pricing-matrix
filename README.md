# Interactive Product Management Dashboard with PDF Export

An educational project showing how to build a fully interactive Product Management Dashboard using raw **HTML5, CSS3, and Vanilla JavaScript**. This application allows users to manage product categories, upload dynamically rendered image collages, calculate estimated revenues, and export the entire layout into a clean, presentation-ready PDF directly from the browser.

## 🚀 Live Demo
Try out the live working dashboard here: [Click here for the Live Demo](https://haniyturana.github.io/interactive-pricing-matrix/)
## ✨ Core Features Included
* **Main Collage Overview:** Dynamically builds an image gallery from user uploads with a built-in *click-to-zoom* modal (Zoom In/Out/Reset).
* **Product Categories & Grid layout:** Organizes structural product grids with inline editable category names (`contenteditable`) and individual price tags.
* **Auto-Calculation Engine:** Automatically computes sums per category and multiplies them by input quantities to update the *Summary Matrix* and Grand Total Revenue in real time.
* **Local Storage Caching:** Saves all text changes, price tags, quantities, and uploaded image states instantly so data isn't lost on a browser refresh.
* **Client-Side PDF Export:** Integrates `html2pdf.js` via CDN to seamlessly transform the DOM layout into a clean, landscape-oriented PDF document.

## 🛠️ Tech Stack & Concepts Covered
* **HTML5:** Semantic layouts, file input elements, and `contenteditable` attributes.
* **CSS3:** Flexbox layouts, grid alignments, hover transitions, and sticky action bars.
* **JavaScript (ES6+):** Live event listeners, DOM manipulation, handling asynchronous images via the `FileReader API`, and data persistence utilizing `localStorage`.
* **html2pdf.js:** A client-side library to convert HTML elements into high-quality PDFs via html2canvas and jsPDF.

## 📖 How to Run & Learn From This Code
Because this project does not rely on heavy frameworks or external backend servers, running it locally is incredibly easy:
1. Clone this repository to your local machine:
```bash
   git clone [https://github.com/haniyturana/interactive-pricing-matrix.git](https://github.com/haniyturana/interactive-pricing-matrix.git)
