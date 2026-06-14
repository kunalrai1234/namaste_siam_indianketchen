# Namaste Siam — Premium Restaurant Menu 🍽️

A beautifully crafted, fully responsive frontend landing page for **Namaste Siam**, a premium dining experience based in Bangkok, Thailand. This project showcases an elegant user interface designed to present authentic cuisine with a modern, high-end digital aesthetic.

## ✨ Features

- **Modern & Premium UI:** Designed with a warm color palette (Cream, Vibrant Orange, Dark Brown) using 'Syne' and 'DM Sans' typography for a luxurious feel.
- **Live Search & Filtering:** Instantly search through dishes by name, description, category, or ingredients.
- **Dynamic Menu Categories:** Filter the menu by Starters, Thai Specials, Indian, Desserts, and more.
- **Interactive Modals:** Detailed popup views for individual dishes including price (in THB), spice levels, ingredients, and dietary badges (Veg/Non-Veg, Chef Special, Bestseller).
- **Fully Responsive Layout:** Optimized across desktop, tablet, and mobile devices using CSS Grid and Flexbox.
- **Backend-Ready Architecture:** Includes a centralized JavaScript `dataLayer` and `derivedData` structure, perfectly primed for an easy migration to a Backend-as-a-Service (BaaS) like **Supabase**.

## 🛠️ Technologies Used

- **HTML5:** Semantic markup.
- **CSS3:** Custom properties (CSS variables), CSS Grid, Flexbox, glassmorphism effects, and smooth keyframe animations.
- **Vanilla JavaScript:** Efficient DOM manipulation, dynamic rendering, and state management without the need for heavy frameworks.
- **Google Fonts:** *Syne* (Headings/Logo) and *DM Sans* (Body/Contact).

## 🚀 Getting Started

This project is built with pure web technologies. No build steps, bundlers, or package managers are required to run the frontend.

1. Clone this repository or download the source code.
2. Open the `namaste_siam_frontend.html` file directly in any modern web browser.
3. Interact with the live search, category filters, and dish modals.

## 🗄️ Future Roadmap (Data Integration)

Currently, the application runs on a mock `dataLayer` object at the bottom of the script. The logic is specifically architected to easily swap out this local data for a live database (such as Supabase).

**Planned Database Schema Mapping:**
- `restaurant_info` -> Fetch address, contact, and hours.
- `about` -> Fetch restaurant story and highlight pillars.
- `categories` -> Dynamically generate the menu filter pills.
- `foods` -> Main menu items including arrays for ingredients and booleans for `chefSpecial` or `bestseller`.
- `gallery` -> Image URLs and alt text for the ambient photo grid.

## 👨‍💻 Author

**Kunal Rai**  
*Founder, Namaste Siam*
