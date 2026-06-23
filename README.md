# Digikala Website

A front-end recreation of [Digikala](https://www.digikala.com/) — Iran’s largest online store — built as the **final project for Web 1** while learning **HTML** and **CSS**.

**Live demo:** [https://fatemeafd.github.io/Digikala-website/](https://fatemeafd.github.io/Digikala-website/)

> This is an educational project for practice only. It is not affiliated with Digikala.

## About

The goal of this project was to practice semantic HTML, layout with CSS, responsive design basics, and building a multi-section landing page inspired by a real-world website. The layout follows Digikala’s RTL (right-to-left) design and includes many of the sections found on their homepage.

## Features

- **Header** — top banner, search bar, login/register link, navigation menu with category submenu
- **Story carousel** — horizontal scroll of promotional stories
- **Image sliders** — hero and promotional banners
- **(Amazing Deals)** — discounted products with countdown timer
- **Category sections** — shop by category, supermarket, and popular brands
- **Product carousels** — best sellers, personalized picks, and trending items
- **\*(Magazine)** — blog/article cards
- **Footer** — support info, links, newsletter signup, and app download section
- **Login page** — separate `login.html` with a registration-style form

## Tech Stack

| Technology                      | Use                                |
| ------------------------------- | ---------------------------------- |
| HTML5                           | Page structure and content         |
| CSS3                            | Styling, layout, and visual design |
| [Swiper](https://swiperjs.com/) | Product and banner carousels       |

No frameworks or CSS preprocessors — plain HTML and CSS only, with a small amount of JavaScript for Swiper initialization.

## Project Structure

```
digikala/
├── index.html          # Main homepage
├── login.html          # Login / sign-up page
├── css/
│   ├── main.css        # Imports all section stylesheets
│   ├── header.css
│   ├── slider.css
│   ├── wonderful.css
│   ├── footer.css
│   └── ...             # One CSS file per section
├── images/             # SVG icons, banners, and product images
└── swiper/             # Swiper library (bundled)
```

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/fatemeafd/Digikala-website.git
   cd Digikala-website
   ```

2. Open `index.html` in your browser — no build step required.

   Optionally, use a local server (e.g. VS Code Live Server) for a closer-to-production experience.

## What I Learned

- Structuring a large page with semantic HTML
- Organizing CSS into modular files with `@import`
- Flexbox and positioning for navigation and product grids
- RTL layout (`dir="rtl"`) for Persian content
- Integrating a third-party slider library (Swiper)
- Recreating a complex UI from an existing website as a design reference

## Author

**Fateme Ahmadifard**

## License

This project is for educational purposes only. All Digikala branding, logos, and design elements belong to their respective owners.
