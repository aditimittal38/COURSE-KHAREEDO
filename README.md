# Course Khareedo

A first-year learning project: a simple course-catalog website for browsing popular programming courses. The site is built with HTML and CSS and includes a home page, course detail pages, and a login screen.

**Live site:** [Course Khareedo](https://aditimittal38.github.io/COURSE-KHAREEDO/)

## Features

- Browse Python, C++, Java, HTML/CSS, JavaScript, and MySQL courses
- View course descriptions, duration, language, tutor, price, and included content
- Navigate between the catalog and individual course pages
- Responsive page layouts with course imagery and promotional styling
- Login screen mockup

## Run Locally

No package installation is required. From the `COURSE-KHAREEDO` directory, start a local static web server:

```bash
py -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser. You can also open `index.html` directly.

## Project Structure

```text
index.html       Course catalog home page
homePage/        Home page styles and course images
productpages/    Individual course pages and shared styles
login/           Login screen mockup
logo.jpg         Site logo
```

## Note

This is a static front-end prototype. Login, signup, cart, and purchase buttons are visual only; there is no authentication, payment, or course-delivery backend.
