# edris-and-haykel-BOQ-Calculator
standard BoQ Calculator
# EastEdge Engineering BoQ Calculator (EEBCEC)

**Professional Ethiopian Construction Cost Estimation – August 2026 Pricing**

---

## 📋 Overview

The **EastEdge Engineering BoQ Calculator (EEBCEC)** is a fully functional, modern Bill of Quantities (BoQ) estimator designed specifically for the Ethiopian construction industry. It provides accurate, itemized cost breakdowns for various building types, locations, and finishing levels, using market indices as of **August 2026**.

Developed by **Eng. Edris Abdella**, this tool reflects the standards of **Edris and Haykel Construction Partnership PLC** and is branded for **EastEdge Engineering**. It integrates your logos, background images, social links, payment details, and preferred cities (Dire Dawa and Addis Ababa), making it ready for professional deployment.

---

## ✨ Features

- **Dynamic Cost Estimation** – Input project parameters (location, building type, area, finishing level, floors, construction type) and get an instant estimate.
- **Itemized BoQ Breakdown** – Detailed line‑items grouped by category: Substructure, Superstructure, Finishing, MEP, and External Works.
- **Interactive Dashboard** – Clean, responsive UI with a hero slider, summary statistics, and a sortable BoQ table.
- **Excel Export** – Download the complete BoQ as a formatted `.xlsx` file using SheetJS.
- **Print‑Ready** – Print estimates directly from your browser with a print‑optimized stylesheet.
- **Payment Integration** – Displays supported gateways (eBirr, CBEBirr, Telebirr) and account details for premium services.
- **Social Links** – Integrated links to Telegram, LinkedIn, WhatsApp, Facebook, Instagram, GitHub, X (Twitter), and TikTok.
- **Modern Branding** – Customizable with your logos, color scheme, and background images.

---

## 🚀 How to Use

1. **Fill in the project details:**
   - Select **Project Location** (Dire Dawa, Addis Ababa, or Other).
   - Choose **Building Type** (Residential, Commercial, Warehouse, Institutional).
   - Enter **Total Floor Area** (m²).
   - Select **Finishing Level** (Standard, Premium, Basic).
   - Specify **Number of Floors**.
   - Pick **Construction Type** (RC, Steel, or Mixed).

2. **Generate the estimate:**
   - Click the **“Generate BoQ”** button.
   - The summary and detailed BoQ table will appear below.

3. **Export or print:**
   - Click **“Export Excel”** to download an `.xlsx` file.
   - Click **“Print”** to print the estimate.
   - Use **“Reset”** to clear the form and start over.

---

## 🛠️ Technologies Used

- **HTML5** – Structure
- **CSS3** – Styling, responsive design, print styles
- **JavaScript (ES6)** – Calculation logic, slider, interactivity
- **SheetJS (XLSX)** – Excel export functionality
- **Font Awesome** – Icons
- **Hosted Images** – Logos and hero backgrounds (via ImgBB)

---

## 📦 Installation & Deployment

### Run Locally
1. Download the `index.html` file.
2. Open it in any modern web browser (Chrome, Firefox, Edge, etc.).
3. No server or internet connection is required (except for external assets like images and fonts, which are loaded from CDNs).

### Deploy to a Server
To make the calculator publicly accessible, you can:
- Upload the `index.html` file to any static web hosting service (e.g., Netlify, Vercel, GitHub Pages).
- For a more advanced deployment (with backend database and payment APIs), you can wrap the frontend with a framework (Django, Node.js, PHP) and connect to a database for real‑time price updates.

---

## 🔧 Configuration & Customization

- **Pricing Data** – Base rates, multipliers, and item percentages are defined in the JavaScript (`BASE_RATES`, `CITY_MULT`, `FINISH_MULT`). Update these values to reflect current market prices.
- **Hero Images** – Replace the image URLs in the `heroImages` array with your own backgrounds.
- **Logo & Branding** – Update the `src` attribute of the logo image and modify the header/footer text.
- **Payment Details** – Change the account holder name, phone number, and supported gateways in the payment section.
- **Social Links** – Edit the `href` attributes in the footer to point to your own profiles.

---

## 📄 License

This project is proprietary and developed for EastEdge Engineering. All rights reserved.  
For inquiries about licensing or custom development, please contact the author.

---

## 👨‍💻 Credits

- **Developer:** Eng. Edris Abdella  
- **Company:** EastEdge Engineering  
- **In Partnership with:** Edris and Haykel Construction Partnership PLC  
- **Pricing Basis:** Ethiopian construction market indices – **August 2026**

---

## 📬 Contact & Support

For questions, support, or collaboration, reach out via:

- **Telegram:** [@eastedge_engineering](https://t.me/eastedge_engineering)
- **LinkedIn:** [Edris Abdella Nuure](https://www.linkedin.com/in/edris-abdella-nuure-7aa521177)
- **WhatsApp:** [Click to chat](https://wa.me/qr/FPJETXYVTS5YE1)
- **Email:** (provided upon request)

---

## 🔮 Future Enhancements

- Backend integration with a database for real‑time price updates.
- User authentication and project saving.
- Full Excel export with multi‑sheet breakdowns.
- Payment gateway APIs (eBirr, Telebirr) for premium downloads.
- Multi‑language support (Amharic, English).

---

> *“Precision Bill of Quantities for Ethiopian Construction — from Substructure to Finishing, transparent and reliable.”*