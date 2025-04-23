# Mini CMS

#### Video Demo: <URL HERE>

#### Description

**Mini CMS** is a basic content management system built with Node.js, Express, and EJS templating. It allows an admin to create, edit, and delete posts, which are then displayed publicly on the main site. Each post belongs to a category, and users can browse posts filtered by category.

The admin area is accessible at `/admin`, but only pre-authorized users can log in. Public registration is disabled to reflect a typical CMS workflow where admin accounts are managed manually.

---

##### Features

- Public-facing page with a list of posts
- Post detail pages
- Post categorization and category filtering
- Sidebar category list on both the index and post pages
- Admin panel with:
  - Login system for pre-authorized users
  - Create, edit, delete posts
  - Upload a featured image for each post
  - Manage categories (create, edit, delete)

---

##### Technologies Used

##### Core Stack

- **Node.js** — JavaScript runtime for the server
- **Express** — Web framework to manage routes, middleware, and requests
- **EJS** — Templating engine for rendering HTML on the server side
- **SASS** — CSS preprocessor to write cleaner, modular stylesheets

##### Dev Tools

- **Nodemon** — Automatically restarts the server on file changes
- **NPM** — Manage project dependencies

---

This project is part of my final submission for Harvard's CS50 course.
