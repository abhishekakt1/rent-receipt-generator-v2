# 🧾 Rent Receipt Generator — India

A free, browser-based rent receipt generator built for the Indian financial year (April–March). Generate professional, print-ready rent receipts in seconds — no signup, no backend, no cost.

**Live Demo:** [https://YOUR-USERNAME.github.io/rent-receipt-generator/](https://YOUR-USERNAME.github.io/rent-receipt-generator/)

---

## ✨ Features

- **Quarterly receipts** aligned to Indian FY (Q1: Apr–Jun, Q2: Jul–Sep, Q3: Oct–Dec, Q4: Jan–Mar)
- **Monthly receipts** — pick any individual months
- **Selective receipts** — generate just 1, 2, or 3 quarters/months as needed
- **Landlord PAN card** support for HRA tax exemption compliance
- **Amount in words** auto-generated (Indian numbering: Lakh, Crore)
- **4 receipts per A4 page** — print and cut
- **Revenue stamp** placeholder + Landlord signature line
- **Other charges** field (maintenance, parking, etc.)
- **No wasted space** — blank slots are hidden, unused page area stays empty for reuse
- Completely **free and open source**

---

## 🖥️ Live Usage

Just visit the link and fill in the form:

1. Enter **landlord** name, PAN (optional), and property address
2. Enter **tenant** name and monthly rent
3. Select the **financial year** and **period** (quarterly or monthly)
4. Click **Preview Receipts**
5. Click **Print** — receipts are A4-ready, 4 per page

No installation. No account. Works entirely in your browser.

---

## 📁 Project Structure

```
rent-receipt-generator/
│
├── index.html        ← The entire app (single self-contained file)
└── README.md         ← This file
```

This is intentionally a **single-file app** — no dependencies, no build tools, no npm. Just one HTML file that works anywhere.

---

## 🚀 Deployment (GitHub Pages)

This project is hosted on GitHub Pages. To deploy your own copy:

1. Fork this repository
2. Go to **Settings → Pages**
3. Set source to **Deploy from branch → main → / (root)**
4. Your site will be live at `https://YOUR-USERNAME.github.io/rent-receipt-generator/`

No workflow file needed. GitHub Pages serves static HTML directly — no build step required.

---

## 🛠️ Local Development

No setup needed. Just open the file in any browser:

```bash
# Clone the repo
git clone https://github.com/YOUR-USERNAME/rent-receipt-generator.git

# Open in browser
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

---

## 📋 HRA Compliance Notes

- Rent receipts are required to claim **HRA exemption** under Section 10(13A) of the Income Tax Act
- If annual rent exceeds **₹1,00,000**, the landlord's **PAN must be included** on the receipt
- This generator includes all mandatory fields: landlord name, PAN, tenant name, property address, period, and amount

---

## 🤝 Contributing

Contributions are welcome! If you find a bug or want to suggest a feature:

1. Open an **Issue** describing the problem or suggestion
2. Or fork the repo, make your changes, and open a **Pull Request**

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

*Created by [Abhishek Tripathi](https://github.com/YOUR-USERNAME)*
