# ApexExchange | Global Currency Conversion & Financial Dashboard

**ApexExchange** is a responsive web application built for multi-currency conversion, real-time exchange rate calculations, and financial remittance estimation. It features a dark-mode glassmorphism UI, fluid interactive elements, API-driven market data, and an offline fallback system.

---

## 📌 Project Context & Overview

* **Project Title**: ApexExchange: Advanced Global Currency Conversion & Financial Dashboard
* **Author / Developer**: Adrian Cajeda Aduana
* **Course & Program**: Elective III - Git Workshop: Basic Version Control | Bachelor of Science in Computer Engineering (BSCpE)

ApexExchange provides dynamic currency calculations between global currencies including USD, EUR, GBP, PHP, JPY, AUD, and CAD. The application integrates live rates via the Frankfurter Forex API while maintaining local fallback configurations (enforcing a fixed **1 USD = 63.54 PHP** rate benchmark and offline mode conversion).

---

## 🚀 Key Features

- **Live & Offline Currency Converter**: Converts amounts across major currencies using live rates or offline fallbacks. Automatically calculates USD to PHP conversions at the enforced **63.54 PHP** base rate.
- **Popular Exchange Benchmarks**: Displays quick market rates for key trading pairs (USD/EUR, USD/GBP, USD/PHP at 63.54, and USD/JPY).
- **Fee & Remittance Estimator**: Calculates 1.5% institutional conversion fees and displays the exact net amount recipients receive.
- **Glassmorphism UI Design**: Built with Tailwind CSS, custom modern glassmorphism panels, FontAwesome icons, and Google Fonts (Figtree).

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, JavaScript (ES6+), Tailwind CSS (via CDN)
- **Icons & Fonts**: FontAwesome 6.4.0, Google Fonts (Figtree)
- **API Integration**: Frankfurter Forex REST API
- **Version Control & Hosting**: Git, GitHub (`AdrianAduana/moneyexchange`), GitHub Pages

---

## 📂 Repository Structure

```text
ApexExchange/
├── index.html         # Main dashboard, currency converter, and benchmark scripts
├── about.html         # About page and project features outline
└── README.md          # Project documentation and setup guide
```

---

## 💻 Local Setup & Development

1. **Clone the Repository**:
   ```powershell
   git clone https://github.com/AdrianAduana/moneyexchange.git
   cd moneyexchange
   ```

2. **Open in VS Code**:
   ```powershell
   code .
   ```

3. **Run Locally**:
   - Right-click `index.html` in VS Code and select **Open with Live Server** (or use the Live Preview extension).
   - Open your browser at `http://127.0.0.1:5500/index.html`.

---

## 🚢 Deployment & Git Workflow

This project deploys automatically to **GitHub Pages** from the `main` branch.

### Feature Branch to Production Deployment

1. **Stage and Commit Changes**:
   ```powershell
   git add index.html
   git commit -m "Enforce 1 USD = 63.54 PHP with correct script DOM attachment"
   ```

2. **Merge Feature Branch into Main**:
   ```powershell
   git checkout main
   git merge feature-about
   git push origin main
   git checkout feature-about
   ```

3. **View Deployed Site**:
   - Visit the live site at `https://adrianaduana.github.io/moneyexchange/`.
   - *Note:* Perform a hard refresh (`Ctrl + Shift + R` on Windows/Linux or `Cmd + Shift + R` on Mac) to bypass local browser cache after new deployments.

---

## 👤 Author

* **Adrian Aduana** — *Computer Engineering Student*
* GitHub: [@AdrianAduana](https://github.com/AdrianAduana)
