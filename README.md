# Freelance Invoice Generator

A responsive, single-page freelance invoice generator web application with live preview, QR code payment support, and 1-click **1-Page PDF** and **High-Resolution PNG** export.

Designed for freelancers, independent contractors, and consultants who need clean, professional, single-page invoices without page-break overflow issues.

---

## Features

- **Guaranteed 1-Page Layout**: Specifically calibrated print and render styles prevent awkward page breaks and unwanted blank pages.
- **1-Click High-Resolution PNG Export**: Embedded raster rendering engine (`html2canvas`) generates clean 2x crisp PNG images instantly in your browser without uploading data to external servers.
- **1-Click Print & PDF Generation**: Native browser print styling optimized for clean vector PDF generation.
- **Fully Responsive & Mobile-Optimized**:
  - **Desktop**: Split-pane layout where the left form sidebar scrolls independently while the invoice preview stays fixed in place.
  - **Mobile**: Intuitive segmented tab switcher (**Edit Form** vs. **Preview**) with touch-optimized controls and auto-zooming prevention.
- **Multi-Currency Support**: Switch between PHP (₱), USD ($), EUR (€), GBP (£), AUD ($), CAD ($), SGD ($), and AED (AED) with automatic symbol updating.
- **Dynamic Line Items**: Add, remove, and update invoice items with automatic real-time calculation of subtotals, tax/VAT, and balances.
- **Payment & QR Code Support**: Includes payment details for Bank Wire / Electronic Transfer and GCash QR code visualization.
- **Quick Presets**: Rapidly switch between pre-configured invoice templates or reset to a clean blank state.
- **100% Client-Side & Private**: Runs entirely in the browser. No tracking, no backend servers, and zero telemetry.

---

## Live Demo & Usage

### 1. Run Locally
Open `index.html` directly in any modern web browser (Chrome, Edge, Safari, Firefox). No installation or server required.

### 2. Deploy to GitHub Pages
To use the invoice generator as a web app on your phone or computer:
1. Go to your repository **Settings** on GitHub.
2. Select **Pages** from the left navigation.
3. Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
4. Set the branch to `main` and folder to `/(root)`, then click **Save**.
5. Your live app will be accessible at:
   ```
   https://zyf3rr3r.github.io/Invoice-Generator/
   ```

---

## Project Structure

```
Invoice-Generator/
├── index.html       # Standalone single-page application (CSS, HTML, JS)
├── README.md        # Documentation and usage guide
└── .gitignore       # Git ignore rules
```

---

## License

This project is licensed under the MIT License.
