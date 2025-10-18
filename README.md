#🚀 AI SaaS Landing Page Template
**Author:** Alasa Gift  
**Built with:** Tailwind CSS + AOS Animation  
**Version:** 1.0  
**Release Date:** 2025  

---

## 🧠 Overview
This **AI SaaS Landing Page Template** is a modern, responsive, and animated web template designed for startups, AI tools, SaaS apps, or automation platforms.  
It features smooth scroll animations, gradient visuals, and a futuristic dark mode aesthetic.

---

## 📁 Project Structure

project-folder/ │ 
├── index.html      # Main landing page file │ 
├── assets/ │   
├── images/   # All icons, avatars, and mockups │   │   ├── logo.png │   │   ├── logo-footer.png │   │   ├── hero-dashboard.png │   │   ├── plan-starter.svg │   │   ├── plan-pro.svg │   │   ├── plan-enterprise.svg │   │   ├── faq.svg │   │   ├── avatar-alasa.png │   │   ├── avatar-sarah.png │   │   └── avatar-anita.png │   │ │   └── fonts/ (optional)     # If you include local fonts later │ └── README.md

---

## ⚙️ How to Use This Template

### 1️⃣ Add to Your Project
You can add this template in **two simple ways**:

#### **Option 1: Copy Files**
- Download and unzip the folder you received.  
- Copy all contents (`index.html` and `assets/`) into your web project directory.

#### **Option 2: Deploy Standalone**
If you just need the landing page live:
- Upload the folder to your hosting platform (e.g. **Netlify**, **Vercel**, **GitHub Pages**, or **cPanel public_html**).

---

### 2️⃣ Open in Browser
After copying, open the `index.html` file in your browser to preview:
```bash
double-click index.html

or drag it into Chrome/Edge.


---

🧩 Customization Guide

Here’s what you can change to make the landing page yours 👇

🪄 Brand Logo

Replace: assets/images/logo.png

Footer logo: assets/images/logo-footer.png

Recommended size: 200x60px (transparent background, PNG or SVG)



---

💬 Hero Text

Located around line 75 inside index.html:

<h1>Empower Your Business with Smart AI Automation</h1>
<p>Streamline workflows, boost productivity...</p>

Edit this section to match your brand or message.


---

🎨 Colors

All colors are defined using Tailwind CSS utility classes.
To change gradients, edit this part:

from-purple-600 to-cyan-500

Example:

from-blue-500 to-green-400

You can also change background shades:

bg-[#0b0b0f]
bg-[#141420]


---

🧱 Features Section

Modify icons and text under:

<section id="features">

Each feature card looks like:

<img src="assets/images/insight-icon.svg" alt="Smart Insights Icon" />
<h3>Smart Insights</h3>
<p>Gain real-time analytics...</p>

Replace icons or descriptions as needed.


---

💵 Pricing Section

Edit plan names, prices, and features inside:

<section id="pricing">

Example:

<h3>Pro</h3>
<p class="text-4xl font-bold mb-6">$29<span>/mo</span></p>

You can also update SVG plan icons:

plan-starter.svg

plan-pro.svg

plan-enterprise.svg



---

👩‍💻 Testimonials

Each testimonial follows this structure:

<img src="assets/images/avatar-alasa.png" alt="Alasa G. Avatar" />
<p>“This AI platform saved us countless hours...”</p>
<h4>– Alasa G., Product Manager</h4>

👉 Image size should be 120×120px (transparent background works best).
You can use round or square images — both display fine.


---

❓ FAQ Section

Update questions and answers inside:

<section id="faq">

Each question is inside a <details> block:

<details>
  <summary>Is this template responsive?</summary>
  <p>Yes! It looks great on all devices.</p>
</details>


---

🌐 Live Hosting (Optional)

Deploy your landing page for free using:

Netlify → drag and drop your folder

Vercel → import from GitHub

GitHub Pages → push to a public repo


No backend or build process required.


---

💡 Animation Settings

This template uses AOS.js.
Control animation behavior by editing this snippet (bottom of index.html):

AOS.init({
  duration: 900,
  once: true,
});

You can adjust:

duration: speed (in ms)

once: run once or every scroll

offset: when animation starts



---

🔧 Dependencies

All libraries are loaded via CDN — no installation required.

Library	Purpose	CDN

TailwindCSS	Styling framework	https://cdn.tailwindcss.com
AOS.js	Scroll animations	https://unpkg.com/aos@2.3.4/dist/aos.css / .js
Google Fonts	Typography (Inter)	https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700



---

🧰 Optional Enhancements

You can extend the template with:

Contact Form Integration → Formspree / Netlify Forms

Stripe Checkout Buttons for real pricing

Live Demo Links for product previews

Custom Dark Mode Toggle (optional JS)



---

🪙 Credits

Designed and developed by Alasa Gift
© 2025 All rights reserved.
For support or customization: Contact the author directly.


---

✅ Quick Checklist Before Delivery

[ ] Replace YourBrand in footer text

[ ] Add your logo (logo.png and logo-footer.png)

[ ] Update hero headline and subtext

[ ] Edit pricing and testimonials

[ ] Test responsiveness on desktop and mobile

[ ] Verify all image paths work correctly (assets/images/...)



---

🎉 Done!

Your AI SaaS Landing Page is now ready to deploy!
Open index.html in your browser or upload the project to your hosting platform — and your futuristic AI landing page will be live 🚀

---
