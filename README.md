# Sastrería Los Abuelos – Luxury Tailor Website

![Screenshot](https://github.com/mizulegendsstudios/sastrerialosabuelos/blob/main/src/images/losabueloslogo%20.png?raw=true)

**Sastrería Los Abuelos** is a fully responsive, single‑page website for a premium tailor shop in Panama. It combines a classic, elegant design with modern web technologies to showcase bespoke suits, custom shirts, alterations, and image consulting services.

🔗 **Live Demo:** https://mizulegendsstudios.github.io/sastrerialosabuelos/

---

## Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Built With](#built-with)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Customization](#customization)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## About the Project

This website was created for **Sastrería Los Abuelos**, a traditional tailor shop with over 25 years of experience in Panama. It highlights their craftsmanship, exclusive fabrics, and personalized attention to detail.

The design reflects the client’s brand identity – elegance, luxury, and tradition – through a carefully chosen color palette (dark green, tanned wood, gold accents), serif typography, and a refined layout.

The site is built with vanilla HTML, CSS, and JavaScript; it does not rely on any frameworks or build tools, making it extremely easy to deploy and maintain.

---

## Features

- **Responsive Design** – Adapts seamlessly to mobile, tablet, and desktop screens.
- **Video Background** – A subtle, looping video adds a cinematic feel.
- **Sticky Navigation** – Smooth scrolling menu with mobile hamburger toggle.
- **Hero Section** – High‑impact call to action with an invitation to book a consultation.
- **About Section** – Tells the story of the tailor shop.
- **Services Grid** – Showcases the four main services with images, descriptions, and a call to action.
- **Gallery** – Photo gallery with hover overlays and a lightbox modal to view images full‑size.
- **Testimonials** – Client reviews with avatars to build trust.
- **Contact Form** – Fully styled form with validation (basic JavaScript) and contact information.
- **Newsletter Subscription** – Footer newsletter form.
- **Social Media Links** – Integrated icons for Facebook, Instagram, WhatsApp, and Pinterest.
- **Accessible & SEO‑Friendly** – Semantic HTML, meta tags, descriptive alt attributes, and hidden header text for screen readers.

---

## Built With

- **HTML5** – Semantic structure
- **CSS3** – Custom properties (variables), Flexbox, Grid, transitions, and animations
- **Vanilla JavaScript** – Interactive elements (menu toggle, gallery modal, form submissions)
- **Font Awesome 6** – Icons
- **Google Fonts** – Playfair Display & Lato
- **Unsplash** – Placeholder images (replace with actual photos for production)

---

## Getting Started

### Prerequisites

No special software is required. You only need a modern web browser to view the site locally.

If you want to edit the code, any text editor (VS Code, Sublime Text, etc.) is sufficient.

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/mizulegendsstudios/sastrerialosabuelos.git
   ```
2. **Navigate to the project folder**
   ```bash
   cd sastrerialosabuelos
   ```
3. **Open `index.html` in your browser**
   - You can double‑click the file, or
   - Use a local development server (e.g., Live Server extension for VS Code).

That’s it! The page is fully self‑contained.

---

## Usage

The website is ready to be hosted on any static web server:

- **GitHub Pages** – Simply push the code to the `main` branch and enable Pages in the repository settings.
- **Netlify / Vercel** – Drag‑and‑drop the project folder or connect the repository.
- **Traditional hosting** – Upload all files to your server’s public directory.

Remember to replace placeholder images and video with your own assets before going live.

---

## Customization

The color scheme and typography can be easily adjusted by modifying the CSS custom properties in the `:root` selector (inside `<style>`):

```css
:root {
    --color-primary: #2e5842;   /* Dark green */
    --color-secondary: #b98d6b; /* Wood/tanned */
    --color-accent: #c19a6b;    /* Gold */
    --color-light: #f8f5f2;     /* Off‑white background */
    --color-dark: #1a1a1a;      /* Almost black text */
}
```

Other common modifications:

- **Logo**: Replace the `src` of the `<img>` inside the `<header>`.
- **Video Background**: Change the `src` in the `<video>` tag.
- **Gallery/Service Images**: Update the inline `background-image` URLs.
- **Contact Details**: Edit the phone, email, and address in the “Contact” section and footer.
- **Testimonials**: Modify the text and author information in the `#testimonials` section.

For a production site, consider moving the CSS to an external file and optimising images and video for better performance.

---

## Roadmap

- [ ] Migrate styles to an external CSS file for better organisation.
- [ ] Add a server‑side endpoint for the contact form (e.g., using Netlify Forms or a simple PHP script).
- [ ] Implement lazy loading for gallery images.
- [ ] Add a “back‑to‑top” button.
- [ ] Create a dedicated booking/calendar system.
- [ ] Translate the site into multiple languages (e.g., English as a fallback, Spanish as primary).

---

## Contributing

Contributions are welcome! If you would like to suggest improvements:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

Please ensure your code follows the existing style and is well‑commented.

---

## License

Distributed under the MIT License. See `LICENSE` file for more information.  
(If no license file exists, you may add one – for example, the MIT license is commonly used for open‑source static websites.)

---

## Acknowledgments

- **Unsplash** – For the high‑quality placeholder images.
- **Font Awesome** – For the icon library.
- **Google Fonts** – For the beautiful typography.
- **Sastrería Los Abuelos** – For the inspiration and permission to build this project.
- **You** – For checking out this repository!

---

👔 *Handcrafted with care, just like a bespoke suit.*  
