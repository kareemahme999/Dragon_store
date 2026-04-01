# 🐉 Dragon Fashion — E-Commerce Website

> A modern, responsive fashion e-commerce website built with HTML, CSS, JavaScript, and Bootstrap 5.

---

## 📖 Overview

**Dragon Fashion** is a front-end e-commerce web application for a popular Egyptian men's fashion brand founded in 1998. The project delivers a fully responsive, multi-page shopping experience featuring product categories, a shopping cart, user authentication, and more.

---

## 🌐 Live Pages

| Page | File | Description |
|------|------|-------------|
| 🏠 Home | `index.html` | Landing page with hero section and featured products |
| 👤 About | `About.html` | Brand story, team members, and designer profile |
| 👔 Men's | `Men_s.html` | Men's clothing category |
| 👗 Women's | `Women_s.html` | Women's clothing category |
| 🧒 Kids' | `Kids_s.html` | Kids' clothing category |
| 👜 Accessories | `Accessories.html` | Accessories category |
| 🏷️ Offers | `OFFER.html` | Discounts and special deals |
| 🛒 Cart | `Cart.html` | Shopping cart with item management |
| 📞 Contact | `contact.html` | Feedback form and store location |
| 🔐 Login | `log_in.html` | Login & registration page |

---

## ✨ Features

- **Responsive Design** — Mobile-first layout using Bootstrap 5 grid system
- **Multi-Category Store** — Men's, Women's, Kids', and Accessories sections
- **Shopping Cart** — Add, remove, and manage cart items with SweetAlert2 notifications
- **User Authentication** — Login and Register forms with client-side validation
- **Special Offers Page** — Dedicated section for discounts and promotions
- **Contact Form** — Feedback form with location and contact details
- **Team & About Section** — Animated team cards with hover effects
- **Social Media Integration** — Animated share menu with 8 platform links
- **Sticky Navigation** — Fixed top navbar with dropdown category menu
- **Swiper Slider** — Touch-friendly image carousels on applicable pages

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| HTML5 | Page structure and semantics |
| CSS3 | Custom styling and animations |
| JavaScript (ES6) | Cart logic, auth, and interactivity |
| [Bootstrap 5.3](https://getbootstrap.com/) | Responsive layout and UI components |
| [Bootstrap Icons](https://icons.getbootstrap.com/) | Icon library |
| [Font Awesome 6](https://fontawesome.com/) | Additional icons |
| [Swiper.js 11](https://swiperjs.com/) | Touch slider / carousel |
| [SweetAlert2](https://sweetalert2.github.io/) | Beautiful alert dialogs |

---

## 📁 Project Structure

```
dragon-fashion/
│
├── index.html              # Home page
├── About.html              # About page
├── Men_s.html              # Men's category
├── Women_s.html            # Women's category
├── Kids_s.html             # Kids' category
├── Accessories.html        # Accessories category
├── OFFER.html              # Offers & discounts
├── Cart.html               # Shopping cart
├── contact.html            # Contact page
├── log_in.html             # Login / Register
│
├── *.css                   # Page-specific stylesheets
├── *.js                    # Page-specific JavaScript files
│
├── picture_About/          # Images for About page
├── picture_Contact/        # Images for Contact page
└── ...                     # Other image folders per category
```

---

## 🚀 Getting Started

No build tools or installation required. This is a pure front-end project.

1. **Clone or download** the repository
2. **Open `index.html`** in your browser
3. Navigate between pages using the top navbar

> ⚠️ Make sure all image folders are present relative to the HTML files for images to load correctly.

---

## 📸 Pages Preview

### Navigation
All pages share a consistent **dark sticky navbar** with:
- Brand logo (`🐉 Dragon Fashion`)
- Links: Home · About · Categories (dropdown) · Cart · Contact
- Login / Logout button

### Shopping Cart
Cart items are managed via **localStorage** and displayed dynamically on `Cart.html`. Users receive confirmation dialogs powered by SweetAlert2.

### Authentication
The `log_in.html` page features a sliding panel UI with separate **Login** and **Register** forms, validated on the client side.

---

## 👨‍💻 Designer

**Kareem Ahmed**
Second-year student at the Faculty of Computers, Information, and Artificial Intelligence.
Specializing in Front-End Development.

- 📞 +20 155 800 3416
- 📧 kareemahmed4795@gmail.com

---

## 📄 License

This project was created as an academic final project. All rights reserved © Dragon Fashion 2025.
