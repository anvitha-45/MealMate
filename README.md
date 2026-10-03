# MealMate — Responsive Food Ordering Website

> **"Good Food. Made Simple."**  
> A modern, responsive food-ordering frontend portfolio website built with clean HTML5, CSS3, and Bootstrap 5.

---

## 📌 Project Description

**MealMate** is a multi-page, responsive web application concept designed to provide users with a clean, fast, and delightful food browsing experience. The website showcases a variety of cuisines—ranging from breakfast specials and gourmet burgers to stone-baked pizzas, wholesome meals, desserts, and refreshing beverages.

This project was built to demonstrate core frontend development proficiencies for real-world web engineering roles, focusing on semantic markup, modern CSS architecture (custom properties, responsive layout patterns, custom styling), and Bootstrap 5 grid and components without unnecessary dependencies.

> **Note:** This project is an intentional **Frontend Demonstration**. There is no backend, database, authentication, or live payment processing attached. All interactive flows (such as product details, quantity toggles, mock cart calculations, and contact submission) are designed as pure static UI/UX simulations.

---

## ✨ Features

- **Responsive Multi-Page Architecture**: 6 cohesive pages linked through a unified navigation and footer system.
- **Modern Food-Tech Visual Identity**: Appetizing warm coral and amber palette, subtle elevation shadows, rounded cards, and typography paired for high readability (`Outfit` + `Plus Jakarta Sans`).
- **Responsive Mobile Navigation**: Collapsible Bootstrap 5 navbar with active page indicators and a visual cart badge.
- **Categorized Food Catalog**: 6 distinct food categories (Breakfast, Burgers, Pizza, Meals, Desserts, Beverages) with clean anchor navigation jumps.
- **Appetizing Food Showcase**: 12 curated menu items with consistent image aspect ratios, star ratings, prices in Indian Rupees (₹), and descriptive item snippets.
- **Detailed Product Page**: Full food detail view featuring high-res imagery, ingredients & highlights, quantity UI, and cross-sell product suggestions ("You May Also Like").
- **Promotions & Offers Hub**: Special discount cards (FIRST20, WEEKEND100, COMBO50, BOGO) with coupon code boxes and redemption instructions.
- **Mock Order Review & Cart**: Complete static cart summary showing itemized pricing, quantity controls, delivery fees, and order totals. Includes a Bootstrap modal simulating checkout confirmation.
- **Accessible Contact Form**: Structured contact channels, operating hours, and an HTML5 input form with proper semantic labels.
- **Zero JavaScript Overhead**: Built purely with HTML5, CSS3, and the standard Bootstrap 5 bundle (strictly for native UI components like togglers and modals).

---

## 🛠️ Technologies Used

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Semantic structure (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`), SEO meta tags, and accessible forms. |
| **CSS3** | Custom design system using CSS Variables (design tokens), flexbox, transitions, custom elevation shadows, and responsive rules. |
| **Bootstrap 5 (v5.3.3)** | Responsive 12-column grid system, navbar collapse mechanism, modal dialog, and layout utilities. |
| **Bootstrap Icons (v1.11.3)** | Crisp, lightweight SVG font icons for ratings, features, and UI feedback. |
| **Google Fonts** | `Outfit` (for bold brand headlines) and `Plus Jakarta Sans` (for clean, legible body text). |

---

## 📄 Pages

1. **`index.html` (Home Page)**:
   - Dynamic Hero section with dual-column layout, primary CTAs, and trust metrics.
   - Category exploration grid (6 food categories).
   - Popular choices showcase (6 trending dishes).
   - "Why MealMate?" value proposition blocks (Fresh Food, Affordable Prices, Easy Ordering, Wide Variety).
   - Today's top offers carousel/cards.
   - High-impact closing banner CTA and global footer.

2. **`menu.html` (Full Menu)**:
   - Category navigation pills linking directly to section anchors.
   - 12 distinct dishes distributed across 6 categories.
   - Responsive multi-column layout (4 cards/row desktop, 2-3 tablet, 1 mobile).
   - Direct links to item details.

3. **`food-details.html` (Product Details)**:
   - Dedicated product view for the *Classic Burger*.
   - High-resolution photography, ingredients list, ratings, and price display.
   - Interactive quantity control UI (`- 1 +`) and "Add to Cart" action.
   - "You May Also Like" recommendation cards for upsells.

4. **`offers.html` (Special Offers & Deals)**:
   - 4 promotional cards with unique discount badges and coupon codes (`FIRST20`, `WEEKEND100`, `COMBO50`, `BOGO`).
   - 3-step visual guide on how to redeem promo codes.
   - Quick navigation back to menu.

5. **`cart.html` (Mock Cart & Checkout)**:
   - Order review with 3 sample items (Classic Burger, Margherita Pizza, Cold Coffee).
   - Itemized price calculation breakdown (Subtotal, Delivery Fee, Total).
   - Delivery address preview.
   - Native Bootstrap checkout simulation modal explaining the frontend nature of the project.

6. **`contact.html` (Contact Us)**:
   - Contact cards displaying email, phone, kitchen headquarters, and operating hours.
   - Accessible contact form with inputs for Name, Email, Phone, Inquiry Subject, and Message.
   - Inline feedback alert confirming form submission testing.

---

## 📱 Responsive Design

MealMate is tested and optimized across all major device viewports:

- **Mobile Phones (320px – 480px / 375px baseline)**:
  - Collapsible off-canvas/hamburger navigation.
  - Single-column stacked cards for optimal readability and touch targets.
  - Fluid images and adjusted headline typography.
  - Zero horizontal scroll (`overflow-x: hidden`).
- **Tablets & Small Screens (768px – 991px)**:
  - 2 to 3 card grid columns.
  - Compact side-by-side hero and form arrangements.
- **Laptops (1024px – 1366px)**:
  - Balanced 3 to 4 column card matrices.
  - Sticky navigation bar with backdrop blur.
- **Desktops (1440px – 1920px)**:
  - Max-width content containers (`container`) to prevent extreme stretching on ultra-wide monitors.

---

## 📁 Project Structure

```text
MealMate/
│
├── index.html              # Home page
├── menu.html               # Menu page (12 dishes across 6 categories)
├── food-details.html       # Product detail page (Classic Burger)
├── offers.html             # Deals and promo coupons page
├── cart.html               # Mock cart and order review page
├── contact.html            # Contact information and inquiry form
│
├── css/
│   └── style.css           # Central stylesheet (design tokens, components, responsive rules)
│
├── images/
│   ├── logo.svg            # MealMate vector brand logo
│   ├── hero-food.jpg       # Hero banner food platter
│   ├── category-*.jpg      # 6 Category preview images
│   └── *.jpg               # 12 Dish photos (burgers, pizza, biryani, pasta, etc.)
│
└── README.md               # Documentation and interview guide
```

---

## 🚀 How to Run Locally

Because MealMate is built entirely with client-side web standards, no complex runtime environment, Node modules, or local servers are mandatory:

### Option 1: Direct Browser Opening (Quickest)
1. Clone or download this repository to your computer:
   ```bash
   git clone https://github.com/your-username/MealMate.git
   ```
2. Navigate into the `MealMate` folder.
3. Double-click `index.html` (or right-click and choose **Open with > Chrome / Firefox / Edge / Safari**).

### Option 2: Using VS Code Live Server (Recommended)
1. Open the `MealMate` folder in **Visual Studio Code**.
2. Install the **Live Server** extension (by Ritwick Dey).
3. Right-click `index.html` and click **"Open with Live Server"**.
4. The website will open at `http://127.0.0.1:5500/index.html`.

### Option 3: Using Python's Built-in HTTP Server
If you have Python installed, run:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000` in your web browser.

---

## 🌐 Live Demo

- **Live Website**: [https://anvitha-45.github.io/MealMate/](https://anvitha-45.github.io/MealMate/)
- **GitHub Repository**: [https://github.com/anvitha-45/MealMate](https://github.com/anvitha-45/MealMate)

> ⚡ **Continuous Deployment Enabled**: This repository is configured with GitHub Actions. Any updates pushed to the `main` branch automatically build and deploy to the live demo website in real time.

---

## 🔮 Future Improvements

If extended into a full-stack production application, the following enhancements could be incorporated:
- **Dynamic JavaScript Cart**: State management using `localStorage` or modern state libraries to dynamically calculate cart totals, modify quantities, and remove items.
- **Instant Search & Real-Time Filtering**: Client-side filtering by dietary preference (Veg, Non-Veg, Vegan, Gluten-Free) and price range.
- **Form Validation & Backend Mailer**: Real-time form input validation with backend integration (e.g., Formspree, Node.js/Express, or serverless functions).
- **Authentication & User Profiles**: User sign-in/sign-up, order history tracking, and saved delivery addresses.
- **Payment Gateway Integration**: Secure checkout processing with Stripe, Razorpay, or PayPal.
- **Dark Mode Support**: CSS theme switcher using custom properties and system preference detection (`prefers-color-scheme`).

---

## 💼 Interview Talking Points

When presenting this project in a frontend developer interview, consider highlighting:

1. **Semantic HTML Architecture**:
   - Organized document outline utilizing `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>` rather than generic `<div>` soup.
   - Descriptive `alt` attributes on all images and explicit `<label for="...">` associations with form inputs for web accessibility (WCAG compliance).

2. **Modular CSS & Design Tokens**:
   - Usage of CSS custom properties (`:root`) for colors, typography, border radii, and shadows, allowing consistent theme management and quick redesigns.
   - Implementation of `scroll-margin-top` to account for sticky navbar offsets during internal anchor jumps.

3. **Effective Use of Bootstrap 5**:
   - Leveraged Bootstrap's 12-column flexbox grid (`col-12 col-md-6 col-lg-3`) for responsive breakpoints without writing hundreds of redundant media queries.
   - Customized Bootstrap default components via `css/style.css` to build an original brand identity rather than a cookie-cutter template.

4. **Honest Engineering Boundaries**:
   - Transparently framed the application as a frontend UI/UX prototype, ensuring every button and navigation link functions cleanly while avoiding misleading fake backend claims.

---

## 📜 License & Attribution

- Built for educational, resume, and portfolio demonstration purposes.
- Food photography sourced via Unsplash (free license for commercial and personal use).
- Developed by **Senior Frontend Developer & UI/UX Engineer**.
