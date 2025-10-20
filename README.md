**🧑‍💻 HNG Frontend Stage 1 Task — Demilade**

🚀 Overview

This project is my Stage 1 task for the HNG Internship (Frontend Track).
It continues from Stage 0, expanding into a multi-page application built entirely with semantic HTML, CSS, and JavaScript — all inside one HTML file for simplicity and modularity.

It includes:

A Home page introducing me.

An About Me page (reflection and structured sections).

A Contact Us page with form validation and accessibility support.

🗂️ Pages & Features
🏠 Home Page

Introduces the project and purpose.

Contains navigation to other sections.

Semantic structure using <header>, <main>, and <section>.

👤 About Me Page

Data-testids included:

test-about-page

test-about-bio

test-about-goals

test-about-confidence

test-about-future-note

test-about-extra

Content sections:

Bio

Goals in the program

Areas of low confidence

Note to future self

Extra thoughts

All wrapped semantically with <main> and <section> tags.

📩 Contact Us Page

Form fields (with validation and accessibility):

Full name — test-contact-name

Email — test-contact-email

Subject — test-contact-subject

Message — test-contact-message

Submit button — test-contact-submit

Success message — test-contact-success

Error messages — test-contact-error-<field>

Validation Rules:

All fields are required.

Email must follow name@example.com.

Message must be at least 10 characters.

On success → form resets and displays a success message.

Accessibility ensured with:

<label for="..."> linking

aria-describedby on all error messages

aria-invalid dynamically set for invalid fields

♿ Accessibility & Responsiveness

Uses semantic HTML elements (<main>, <section>, <header>, <nav>, <ul>, <li>, etc.)

Fully keyboard navigable

Uses ARIA attributes for validation feedback

Responsive layout using CSS media queries (mobile, tablet, and desktop)

🧱 Tech Stack

HTML5 — Semantic structure

CSS3 — Responsive styling

Vanilla JavaScript (ES6) — Dynamic content switching & validation

⚙️ How It Works

All content is in a single HTML file.
Navigation between Home, About, and Contact pages is handled dynamically using JavaScript — no page reloads needed.

🧪 Test Identifiers

All required data-testid attributes from HNG Stage 1 specifications are implemented for automated testing.

🌐 Live Demo

🔗 Live URL: [Your Hosted Link Here]
💻 GitHub Repository: [Your GitHub Repo Link Here]

To host, you can use GitHub Pages or Netlify. Example for GitHub Pages:

Push your code to GitHub

Go to Settings → Pages → Deploy from main branch

Copy the generated URL and paste above.

🧭 How to Run Locally

Clone this repository:

git clone https://github.com/your-username/hng-stage1.git


Open the folder:

cd hng-stage1


Open index.html in your browser:

Double-click the file, or

Run via VS Code Live Server extension

🧠 Reflection

Building this project helped strengthen:

Understanding of form validation logic

Writing accessible and semantic HTML

Structuring code cleanly while avoiding spaghetti logic

Building a multi-page experience without frameworks
