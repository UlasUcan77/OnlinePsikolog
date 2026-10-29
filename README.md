<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" width="100%" alt="Online Psikolog — Booking platform for psychologists. A calendar grid with one slot highlighted in red.">
</picture>

**Live at [onlinepsikolog.org](https://www.onlinepsikolog.org/)**

Online Psikolog is a web platform where clients find a psychologist and book an appointment. I built it as a freelance project with a React front end and a PHP backend, and I run its deployment and server operations on cPanel.

> This is a showcase repository. Online Psikolog is a client project, so its source code is private; this page describes what the platform does and how it is built.

<!--
## Screenshots

Add PNGs to docs/screenshots/ and uncomment this section.

<p>
  <img src="docs/screenshots/home.png" width="400" alt="Home page">
  <img src="docs/screenshots/experts.png" width="400" alt="Specialist listings">
</p>
-->

## What it does

- Specialist listings with an individual profile page for each psychologist.
- An appointment system for booking sessions.
- Blog management for publishing articles.
- A fully responsive interface for phones, tablets and desktops.

## How it works

```mermaid
flowchart LR
    A[Browser] --> B[React SPA<br/>Vite + TypeScript]
    B -- HTTP --> C[PHP backend]
    subgraph cPanel hosting
      B
      C
    end
```

The front end is a single-page React app written in TypeScript, built with Vite and routed with React Router. The production build is served from cPanel hosting alongside the PHP backend, which handles appointments, specialist data and blog content.

## Tech stack

React · TypeScript · Vite · React Router · Framer Motion · PHP · cPanel

## Running it

The source code is not public, so the site cannot be built from this repository. To see it in action, visit [onlinepsikolog.org](https://www.onlinepsikolog.org/).

## Contact

Ulaş Uçan · [LinkedIn](https://www.linkedin.com/in/ula%C5%9F-u%C3%A7an-36531626b) · [uls.ucn@gmail.com](mailto:uls.ucn@gmail.com)
