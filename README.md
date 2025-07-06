# Ritz-Carlton Navigation & Slider Clone

This project is a **React-based recreation** of two key sections from the [Ritz-Carlton](https://www.ritzcarlton.com/) website:

- **Top Navigation Menu**
- **Homepage Slider/Carousel Section**
  - **I implemented both**:
  - **SwiperJS** — used for fully responsive, smooth carousels
  - **Custom React Slider** — built manually using state, refs, and animation logic for bonus points

Built with modern frontend tools like **React**, **TailwindCSS**, **Framer Motion**, and **SwiperJS**, this project emphasizes responsive layout, semantic HTML, animation, and modular component architecture.

---

## Live Demo

🔗 [https://your-vercel-or-netlify-link.vercel.app](https://your-vercel-or-netlify-link.vercel.app)

---

## Branch Info

Code is available in branch:

- adity-roy

🔗 [https://github.com/Anzotica-co-at/react-hiring-test-adity672roy/tree/adity-roy](https://github.com/Anzotica-co-at/react-hiring-test-adity672roy/tree/adity-roy)

---

## Run This Project Locally

## 1. Clone the Repository

```bash
git clone https://github.com/Anzotica-co-at/react-hiring-test-adity672roy.git
cd react-hiring-test-adity672roy
```

---

## 2. Switch to the Correct Branch (adity-roy)

```bash
git checkout adity-roy
```

---

## 3. Install Dependencies

```bash
npm install
```

---

## 4. Start the Development Server

```bash
npm run dev
```

---

## 5. Open the App in Your Browser

Visit: [http://localhost:5173](http://localhost:5173)

---

## Tech Stack

- **React** (Vite)
- **TailwindCSS** – Utility-first CSS framework
- **Framer Motion** – For smooth animations and transitions
- **SwiperJS** – Powerful and mobile-friendly carousel library
- **Fully responsive** for both desktop and mobile
- **Functional Components** with React Hooks

---

## Features

- Fully responsive top navigation with mobile accordion menu
- **Animated custom sliders** built using **React**, **TailwindCSS**, and **Framer Motion**, along with **SwiperJS-powered carousels** featuring smooth **text and image transitions**
- Modular and reusable components
- Mobile-first responsive layout
- Clean and semantic HTML
- Interactive UI with hover, scroll, and slide animations
- Easy to maintain and extend

---

## Folder Structure

    src/
    ├── components/
    │ ├── heading/
    │ │ └── Heading.jsx // Reusable section heading component
    │ ├── sliders/
    │ │ ├── Carousel.jsx // Custom Hero carousel
    │ │ ├── DestinationSlider.jsx // Custom Destination-based slider
    │ │ ├── HotelSlider.jsx // Custom Hotel-themed slider
    │ │ ├── SliderNavigation.jsx // Custom slider Progress (next, prev buttons)
    │ │ └── SwiperSlider.jsx // SwiperJS slider
    │ ├── header/
    │ │ ├── Navbar.jsx // Main navbar container
    │ │ ├── NavbarDesktop.jsx // Desktop navigation
    │ │ ├── NavbarMobile.jsx // Mobile navigation
    │ │ ├── NavAccordion.jsx // Accordion for nested mobile menu
    │ │ └── data.js // Navigation data
    ├── layout/
    │ └── Layout.jsx // Shared layout wrapper (includes Navbar)
    ├── pages/
    │ └── Home.jsx // Home page with all slider sections
    ├── App.jsx
    ├── index.css // tailwindcss
    └── main.jsx
