# 🌸 Roy Perfumes — Luxury Fragrance Store

A fully responsive, luxury perfume e-commerce website built with pure HTML, CSS, and JavaScript. No frameworks, no build tools — just one file, ready to deploy.

![Roy Perfumes](https://img.shields.io/badge/Status-Live-brightgreen) ![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![EmailJS](https://img.shields.io/badge/EmailJS-Integrated-blue) ![Netlify](https://img.shields.io/badge/Netlify-Ready-00C7B7?logo=netlify&logoColor=white)

---

## ✨ Features

- 🛍️ **Full Shopping Cart** — Add/remove items, select 15ml or 50ml sizes, live total calculation
- 📧 **Email Orders** — Order details sent to your Gmail via EmailJS when a customer checks out
- 📱 **Fully Responsive** — Works on mobile, tablet, and desktop with hamburger menu
- 🎨 **Luxury Design** — Dark gold aesthetic with Cormorant Garamond typography, animated cursor, floating particles
- 🛒 **Slide-in Cart Drawer** — Smooth cart panel with full order summary
- ✅ **Form Validation** — Checkout form validates all required fields before submitting
- 🖼️ **Real Product Images** — All 8 perfume images embedded directly (no broken links)
- 🔔 **Toast Notifications** — Elegant feedback on every user action
- 🎬 **Scroll Animations** — Elements reveal as you scroll down the page

---

## 🧴 Products Included

| # | Name | 15ML | 50ML |
|---|------|------|------|
| 1 | Petra | Rs. 1,340 | Rs. 2,240 |
| 2 | Hug of Jasmine | Rs. 1,430 | Rs. 2,390 |
| 3 | Taos Hum | Rs. 1,520 | Rs. 2,590 |
| 4 | Napoleon | Rs. 1,790 | Rs. 3,140 |
| 5 | Monaco | Rs. 1,790 | Rs. 3,790 |
| 6 | Los Vikings | Rs. 1,610 | Rs. 2,960 |
| 7 | The King | Rs. 1,700 | Rs. 3,790 |
| 8 | Forbidden City | Rs. 1,790 | Rs. 2,690 |

---

## 🚀 Live Demo

> Deployed on Netlify → **[royperfumes.netlify.app](https://royperfumes.netlify.app)**

---

## 🛠️ Setup & Deployment

### Option 1 — Netlify (Recommended, Free)

1. Go to [netlify.com](https://www.netlify.com) and sign up free
2. On your dashboard, drag and drop `roy_perfumes.html` into the deploy box
3. Your site is live instantly at `random-name.netlify.app`
4. Rename it: **Site Settings → Domain Management → Custom subdomain**

### Option 2 — GitHub Pages

1. Create a new GitHub repository
2. Upload `roy_perfumes.html` and rename it to `index.html`
3. Go to **Settings → Pages → Source → main branch**
4. Your site goes live at `yourusername.github.io/repo-name`

### Option 3 — Local

Just open `roy_perfumes.html` in any browser. No server or install needed.

---

## 📧 Email Orders Setup (EmailJS)

When a customer places an order, the details are emailed to you automatically.

### Step 1 — Create EmailJS Account
1. Sign up free at [emailjs.com](https://www.emailjs.com)
2. Go to **Email Services → Add New Service → Gmail**
3. Connect your Gmail account and note the **Service ID**

### Step 2 — Create Email Template
1. Go to **Email Templates → Create New Template**
2. Set **To Email** to your Gmail address
3. Use this template body:

```
New Order Received! 🛍️

Customer Name: {{customer_name}}
Phone: {{phone}}
Email: {{customer_email}}
Delivery Address: {{address}}

─────────────────────────
ORDER ITEMS:
{{order_items}}
─────────────────────────
TOTAL: {{total}}
```

4. Save and note the **Template ID**

### Step 3 — Add Your Keys to the HTML

Open `roy_perfumes.html` and find these 3 lines near the bottom of the `<script>` section:

```js
const EMAILJS_PUBLIC_KEY  = 'YOUR_PUBLIC_KEY';   // Account → Public Key
const EMAILJS_SERVICE_ID  = 'YOUR_SERVICE_ID';   // Email Services → Service ID
const EMAILJS_TEMPLATE_ID = 'YOUR_TEMPLATE_ID';  // Email Templates → Template ID
```

Replace each value with your real credentials from EmailJS.

### Step 4 — Allow Your Domain
- In EmailJS go to **Account → Allowed Origins**
- Add your live URL e.g. `https://royperfumes.netlify.app`

---

## 📁 Project Structure

```
roy-perfumes/
│
├── roy_perfumes.html      # Entire website (single file)
└── README.md              # This file
```

> All product images are embedded as base64 inside the HTML — no separate image folder needed.

---

## 🧰 Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure |
| CSS3 | Styling, animations, responsive layout |
| Vanilla JavaScript | Cart logic, form handling, UI interactions |
| [EmailJS](https://www.emailjs.com) | Sending order emails (no backend needed) |
| [Google Fonts](https://fonts.google.com) | Cormorant Garamond + Montserrat typography |
| [Netlify](https://www.netlify.com) | Free hosting & deployment |

---

## 💰 Hosting Cost

| Service | Plan | Cost |
|---------|------|------|
| Netlify | Free | $0/month |
| EmailJS | Free (200 emails/month) | $0/month |
| Custom Domain (optional) | e.g. Namecheap | ~$10/year |

**Total running cost: $0/month** 🎉

---

## 📞 Contact

**Roy Perfumes**
- 📧 Email: [roys.prosworld@gmail.com](mailto:roys.prosworld@gmail.com)
- 📞 Phone: 318-256-9184
- 🕐 Hours: Monday – Sunday, 10am – 10pm PST
- 📸 Instagram · Facebook · YouTube

---

## 📜 License

This project is private and intended for Roy Perfumes business use only.

---

*Built with ❤️ for Roy Perfumes — Where scent becomes memory.*
