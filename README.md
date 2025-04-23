# DevTime

DevTime is a minimalist productivity app in progress, built using pure **Ruby**, following the **MVC architecture** without relying on full-stack frameworks like Rails.

The goal is to explore concepts like **ruthless prioritization**, **async communication**, and **functional simplicity** .

![DevTime Logo](assets/DevTimeLogo.png)

## Project Status

**Currently in development.**  
I'm laying down the foundation using plain Ruby and file-based persistence, keeping the codebase clean and educational.

---

## Planned Folder Structure

```

devtime/
├── app/
│   ├── controllers/ # Handles user interaction and flow
│   │   └── application_controller.rb
│   ├── models/  # Business logic and data management
│   │   └── user.rb
│   └── views/ # Template rendering (.erb or custom)
│       └── home/
│           └── index.erb
├── config/ # App settings and routes
│   └── routes.rb
├── public/ # Static files (CSS, JS)
│   └── assets/
│       ├── styles.css
│       └── script.js
├── db/ # Migrations and schema
│   ├── migrate/
│   └── schema.rb
├── lib/ # Utilities, helpers, and core modules
│   └── helpers/
│       └── date_helper.rb
├── spec/ or test/  # (Future) automated tests
│   └── user_spec.rb
├── .env
├── app.rb
├── Gemfile
└── README.md # You are here

```

## Project Status

**Currently in development.**  
I'm laying down the foundation using plain Ruby and file-based persistence, keeping the codebase clean and educational.

---

## Planned Features

- [ ] Create, update, and delete tasks
- [ ] Task status: To Do / In Progress / Done
- [ ] Local persistence (e.g., JSON or SQLite)
- [ ] Simple web UI using ERB templates or CLI mode
- [ ] Async-style task review (like HEY’s screener logic)

---

## Getting Started

To run the project:

```bash
# Clone the repo
git clone https://github.com/your-username/devtime.git
cd devtime

# Run the app
ruby main.rb

```

# About this Project

This app is part of a personal challenge: learning Ruby in depth while exploring real-world software design without relying on frameworks. It's a playground for good code, meaningful structure, and keeping things boring _(in the best way possible)_.

# About me

Made by **Miguel Fernando Rocha** aka **Kid** — just a hacker kid building tools that respect your time.

[Email me!](miguelferocha@outlook.com) | [ LinkedIn (If u wanna hire me...)](https://www.linkedin.com/in/miguel-fernando-rocha-a9431a288/)
