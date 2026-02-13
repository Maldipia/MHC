# Must Have Corner & Business Network Websites

This repository hosts multiple websites for our business network, deployed via GitHub Pages.

## 🌐 Live Websites

- **Must Have Corner** - [musthavecorner.com](https://www.musthavecorner.com)
  - Fresh food delivery service in Amadeo, Cavite
  
- **Airbnb Workshop** - [musthavecorner.com/airbnb-workshop](https://www.musthavecorner.com/airbnb-workshop)
  - Free 1-hour workshop for Airbnb & staycation hosts

## 📁 Repository Structure

```
.
├── index.html              # Must Have Corner main website
├── order.html              # Order form redirect page
├── airbnb-workshop/
│   └── index.html         # Airbnb workshop landing page
├── .github/
│   └── workflows/
│       └── static.yml     # GitHub Pages deployment workflow
└── README.md              # This file
```

## 🏢 Must Have Corner

**Fresh Food & Essentials Delivered Daily**

Premium food delivery service serving Amadeo, Cavite and nearby areas.

### Products & Services
- 🥚 Fresh brown eggs (graded by weight, not size)
- 🍗 Chicken Inasal (butterflied grilled)
- 🥓 Pork Samgyup BBQ
- 🍚 MHC Special Fried Rice
- 🐔 Fresh & frozen whole chicken
- 🦀 Fresh crabs

### Key Features
- ✅ FREE delivery for orders ₱1,299+
- ✅ 24-48 hour farm-to-table freshness
- ✅ 10km delivery radius from Amadeo
- ✅ Multiple payment options (Cash, GCash, PayMaya, Bank Transfer)
- ✅ 3-4 hours advance order for ready-to-eat items

### Contact Information
- 📞 **Phone:** 0967-400-0040
- 📧 **Email:** musthavecornerofficial@gmail.com
- 📍 **Location:** Daang Luma, Brgy. Loma, Amadeo, Cavite 4119
- 🕒 **Hours:** Monday-Sunday, 8:00 AM - 8:00 PM

### Order Online
🛒 [Order Form](https://script.google.com/macros/s/AKfycbz7BAjqOYBVEdyMR7jUpKbrr1pK7JJDojHCwGsgHaNU9XXzGKKBTL1Zltnf1941ZxIShQ/exec)

---

## 🏡 Airbnb Workshop

**A Must-Have AirBNB Starter Kit**

Free 1-hour in-person workshop for Airbnb & staycation hosts.

### Event Details
- 📅 **Date:** February 7, 2026 (Saturday)
- ⏰ **Time:** 9:00–10:00 AM
- 📍 **Venue:** Yani Garden Cafe, Amadeo, Cavite
- 💰 **Price:** FREE (₱0)
- 🎟️ **Seats:** Limited

### What You'll Learn
- How to set rules guests respect
- How to protect your listing without drama
- How confident hosts think before issues happen
- Build your own one-page Airbnb Starter Kit

### Registration
📝 [Reserve Your Free Seat](https://forms.gle/XFmFxbvMm7PKvwBc8)

---

## 🔗 Our Business Network

Part of a family of trusted businesses:

| Business | Description | Website |
|----------|-------------|---------|
| **TYG Services** | Automation & Professional Services | [tyg-services.com](https://tyg-services.com) |
| **Luntian** | Premium Accommodation & Staycation | [luntian.net](https://luntian.net) |
| **Sole Blessing** | Original Sneakers & Footwear | [soleblessing.com](https://soleblessing.com) |
| **Must Have Corner** | Fresh Food Delivery | [musthavecorner.com](https://www.musthavecorner.com) |
| **The Gold Blessing** | Fine Gold Jewelry | Coming Soon |
| **Aster** | Premium Apparels | Coming Soon |

---

## 🚀 Deployment

This repository uses **GitHub Actions** for automatic deployment to GitHub Pages.

### How It Works
1. Push changes to the `main` branch
2. GitHub Actions automatically triggers the deployment workflow
3. Static files are deployed to GitHub Pages
4. Changes are live within minutes

### Manual Deployment
If needed, you can manually trigger the workflow:
1. Go to **Actions** tab in GitHub
2. Select "Deploy static content to Pages"
3. Click "Run workflow"

### Deployment Configuration
- **Branch:** main
- **Workflow:** `.github/workflows/static.yml`
- **Permissions:** Read contents, write to Pages, write ID token

---

## 🛠️ Local Development

### Prerequisites
- Any modern web browser
- Basic text editor or IDE
- Local web server (optional, for testing)

### Running Locally

**Option 1: Simple File Opening**
```bash
# Navigate to the repository
cd /path/to/repository

# Open in browser
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

**Option 2: Local Server (Recommended)**
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

---

## 📝 Making Changes

### Updating Must Have Corner Website
Edit `index.html` directly. Key sections:
- Hero section (line ~240)
- Products grid (line ~420)
- Pricing tables (line ~580)
- Contact information (line ~720)

### Updating Airbnb Workshop Page
Edit `airbnb-workshop/index.html`. Key sections:
- Event details (line ~280)
- Workshop content (line ~350)
- Registration CTA (line ~450)

### CSS Styling
Both pages use inline CSS within `<style>` tags in the `<head>` section.

---

## 🎨 Design System

### Must Have Corner
- **Primary Color:** Emerald Green (#059669)
- **Font:** System fonts (Apple/Segoe UI)
- **Layout:** Grid-based responsive design
- **Theme:** Clean, modern, trustworthy

### Airbnb Workshop
- **Primary Color:** Brand Green (#286147)
- **Font:** System fonts
- **Layout:** Single column, warm café aesthetic
- **Theme:** Warm, inviting, professional

---

## 📱 Responsive Design

Both websites are fully responsive and optimized for:
- 📱 Mobile phones (320px+)
- 📱 Tablets (768px+)
- 💻 Desktops (1200px+)

---

## 🔍 SEO & Metadata

### Must Have Corner
- Open Graph tags configured
- Schema.org LocalBusiness markup
- Optimized meta descriptions
- Keyword targeting: food delivery, Amadeo Cavite, fresh eggs

### Airbnb Workshop
- Event-specific metadata
- Social sharing optimized
- Landing page best practices

---

## 📧 Contact & Support

### Technical Issues
- Open an issue in this repository
- Contact: musthavecornerofficial@gmail.com

### Business Inquiries
- Email: musthavecornerofficial@gmail.com
- Phone: 0967-400-0040

### Partnership Opportunities
Interested in becoming a partner or reseller? Email us!

---

## 📄 License

© 2025 Must Have Corner. All rights reserved.

Part of our trusted business network serving Amadeo, Cavite and nearby areas.

---

## 🔄 Version History

### Current Version
- Must Have Corner website v1.0
- Airbnb Workshop landing page v1.0
- GitHub Pages deployment configured
- Automatic deployment via GitHub Actions

---

## 🎯 Roadmap

### Upcoming Features
- [ ] Online ordering system integration
- [ ] Customer testimonials section
- [ ] Photo gallery
- [ ] Blog section
- [ ] Newsletter signup
- [ ] Live chat support

---

## 🤝 Contributing

This is a private business repository. For suggestions or feedback:
1. Open an issue
2. Email us directly
3. Call our support line

---

**Built with ❤️ in Amadeo, Cavite**

Supporting local families through quality products and services since 2024.

---

### Quick Links
- 🛒 [Order Now](https://script.google.com/macros/s/AKfycbz7BAjqOYBVEdyMR7jUpKbrr1pK7JJDojHCwGsgHaNU9XXzGKKBTL1Zltnf1941ZxIShQ/exec)
- 📝 [Workshop Registration](https://forms.gle/XFmFxbvMm7PKvwBc8)
- 💬 [Facebook Page](https://www.facebook.com/musthavecorner)
- 🌐 [TYG Services](https://tyg-services.com)
- 🏡 [Luntian](https://luntian.net)
- 👟 [Sole Blessing](https://soleblessing.com)
