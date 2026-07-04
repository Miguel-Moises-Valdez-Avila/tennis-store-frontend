# 🎾 Tennis Store — Frontend UI (Blade & CSS)

A clean and responsive **frontend interface** for a tennis e-commerce store, built with Laravel Blade templates and custom CSS. This project focuses on the UI/UX design and visual structure of the store.

---

## 🔗 Related Repositories

> **Backend API:** [tennis-store-api](https://github.com/Miguel-Moises-Valdez-Avila/tennis-store-api)
> **Full Stack Version:** [tennis-store-laravel](https://github.com/Miguel-Moises-Valdez-Avila/tennis-store-laravel)

---

## 🧩 Features

- ✅ **Product catalog page** — clean grid layout showcasing tennis equipment
- ✅ **Homepage** — hero section, featured products, and promotions
- ✅ **Product detail page** — images, description, and price display
- ✅ **Shopping cart view** — order summary and item list UI
- ✅ **Checkout page** — clean form layout for purchase flow
- ✅ **Fully responsive** — mobile-first design for all screen sizes
- ✅ **Custom CSS styling** — handcrafted styles without heavy dependencies

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Templating | Laravel Blade |
| Styling | CSS3 (custom) |
| Scripting | JavaScript (ES6+) |
| Framework | Laravel (view layer only) |
| Version Control | Git + GitHub |

---

## 📸 Screenshots

> Add screenshots of your homepage, catalog, product detail, and cart pages here

---

## ⚙️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/Miguel-Moises-Valdez-Avila/tennis-store-frontend.git
cd tennis-store-frontend

# Install dependencies
composer install
npm install

# Environment setup
cp .env.example .env
php artisan key:generate

# Start the development server
php artisan serve
npm run dev
```

---

## 🗂️ Project Structure

```
resources/
├── views/
│   ├── layouts/
│   │   └── app.blade.php
│   ├── home.blade.php
│   ├── catalog.blade.php
│   ├── product-detail.blade.php
│   ├── cart.blade.php
│   └── checkout.blade.php
├── css/
│   └── app.css
└── js/
    └── app.js
```

---

## 🎨 Design Highlights

- Clean and minimal layout focused on product visibility
- Consistent color palette and typography throughout
- Smooth hover effects and transitions on interactive elements
- Mobile-first approach ensuring usability on all devices

---

## 🗺️ Roadmap

- [ ] Migrate styles to Tailwind CSS
- [ ] Connect to tennis-store-api backend
- [ ] Add product search and filter UI
- [ ] Implement dark mode
