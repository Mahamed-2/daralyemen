# Dar Al Yemen Mandi - Web Application

A modern, responsive, and multilingual web application for **Dar Al Yemen Mandi**, located in Göteborg, Sweden. The website showcases authentic Yemeni cuisine with a beautiful, Scandinavian-inspired minimalist design.

## Features

- **Multilingual Support**: Fully localized in English, Swedish, and Arabic. Users can seamlessly switch languages using the navigation toggle, which also dynamically updates the document direction (LTR/RTL).
- **Interactive Menu**: A dynamic food menu filtered by categories (Mandi, Zurbian, Stews, Rice) with detailed descriptions, prices, and beautiful imagery.
- **Cart & Checkout Flow**: A fully functional mock shopping cart that dynamically tracks items.
- **Order Progress Animation**: After placing an order, users are presented with a gorgeous 20-second animated progress modal simulating order confirmation, preparation, transit, and final delivery statuses.
- **Responsive Design**: Carefully crafted with Tailwind CSS to ensure the website is fully usable and fittable on both desktop monitors and small mobile viewports.

## Technical Stack

- **HTML5 & Vanilla JavaScript**: No heavy frameworks used. The entire application logic (translations, cart management, DOM manipulation) is contained within a single `daralyemen.html` file for ultimate simplicity.
- **Tailwind CSS**: Used via CDN for rapid UI development, utilizing a custom configuration to match the brand's exact colors (Gold, Charcoal, Cream, Green, Red).
- **FontAwesome**: Used for beautiful iconography across the site.
- **Google Fonts**: Uses 'Playfair Display' for premium headings, 'Inter' for body text, and 'Cairo' for elegant Arabic typesetting.

## How to Run

Because this project is built with Vanilla HTML/JS and uses a CDN for styling, there is no build step or package installation required! 

Simply open `index.html` in any modern web browser to view the application:

```bash
open index.html
```

## Project Structure

- `index.html`: The core application file containing all structure, scripts, data, and styling configuration.
- `burmah.png`, `daralyemenlogo.png`: Local image assets for the brand and menu.
- `README.md`: Project documentation.
- `*.docx`: Brand guidelines, video scripts, and user persona research.

---
*Taste Yemen in the heart of Göteborg.*
