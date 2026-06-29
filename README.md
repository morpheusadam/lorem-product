<div align="center">

# 🛍️ Lorem Product — WooCommerce Sample Product CSV

### Ready-to-import dummy WooCommerce products (simple, variable & variation rows) in CSV format — with English and Persian sample data and free demo images for theme building, UI testing, and store demos.

<p>
  <img src="https://img.shields.io/github/license/morpheusadam/lorem-product?style=for-the-badge&color=4c1" alt="License" />
  <img src="https://img.shields.io/github/stars/morpheusadam/lorem-product?style=for-the-badge&color=ffca28" alt="Stars" />
  <img src="https://img.shields.io/github/forks/morpheusadam/lorem-product?style=for-the-badge&color=42a5f5" alt="Forks" />
  <img src="https://img.shields.io/github/last-commit/morpheusadam/lorem-product?style=for-the-badge&color=8e44ad" alt="Last commit" />
  <img src="https://img.shields.io/github/repo-size/morpheusadam/lorem-product?style=for-the-badge&color=e67e22" alt="Repo size" />
</p>

<p>
  <img src="https://img.shields.io/badge/WooCommerce-Sample%20Data-96588A?style=for-the-badge&logo=woocommerce&logoColor=white" alt="WooCommerce" />
  <img src="https://img.shields.io/badge/WordPress-Import%20Ready-21759B?style=for-the-badge&logo=wordpress&logoColor=white" alt="WordPress" />
  <img src="https://img.shields.io/badge/Format-CSV-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="CSV" />
  <img src="https://img.shields.io/badge/i18n-EN%20%2B%20FA-0A7BBB?style=for-the-badge&logo=googletranslate&logoColor=white" alt="English + Persian" />
</p>

</div>

---

## 📖 Overview

**Lorem Product** is a set of **sample / dummy WooCommerce products in CSV format**, ready to drop straight into the **built-in WooCommerce Product CSV Importer** (*Products → Import*). Each row follows WooCommerce's official import column layout — including **simple, variable, and variation** product types with SKUs, prices, sale prices, stock, dimensions, categories, tags, attributes (Color / Size / Material), and image URLs — so you get a realistic-looking catalog in seconds instead of typing test products by hand.

It is made for **WooCommerce theme developers, plugin authors, freelancers, and store owners** who need believable placeholder products to build layouts, test product-grid and single-product UI, demo a store, or QA an import workflow. The repository ships **two parallel datasets** — `english.csv` (English sample text) and `product.csv` (Persian / Farsi sample text) — plus a folder of **free demo images** you can host yourself and reference from the CSV.

> 🔎 **Keywords:** WooCommerce sample products, WooCommerce dummy data, WooCommerce CSV import, sample product CSV, WooCommerce demo data, variable product example, WooCommerce test data, lorem ipsum products, WordPress store demo, e-commerce placeholder products.

---

## ✨ Features

- 🧩 **Official WooCommerce import format** — full column header row, importable as-is via *Products → Import*.
- 🔀 **Variable & variation products** — example variable product with Color / Size / Material attributes and child variation rows linked by `Parent` SKU.
- 🌍 **Bilingual datasets** — `english.csv` (English) and `product.csv` (Persian / Farsi) with matching structure.
- 💰 **Realistic commerce fields** — regular & sale prices, sale date windows, stock levels, low-stock thresholds, weight & dimensions, tax status.
- 🏷️ **Categories, tags & attributes** — pre-filled so product filters and grids look populated.
- 🖼️ **Bundled demo images** — 23 free stock photos in [`img/`](img/) to self-host and link from the `Images` column.
- 🪶 **Zero dependencies** — just CSV files; no plugin, build step, or database script required.

---

## 🛠️ What's Inside

| File / Folder | Description |
| --- | --- |
| `english.csv` | Sample WooCommerce products with **English** text |
| `product.csv` | Sample WooCommerce products with **Persian / Farsi** text |
| `img/` | 23 free demo product images (`.jpg`) for self-hosting |

Each CSV contains a variable parent product (e.g. *AI Lab Jacket*, SKU `VR-001`) plus its variation rows (Blue/Green × M/L, different materials), demonstrating how WooCommerce expects parent/variation relationships, attributes, and per-variation pricing and stock.

---

## 🚀 Getting Started

### Prerequisites

- A **WordPress** site with **WooCommerce** installed and active.

### Import the products

1. Clone or download this repository:
   ```bash
   git clone https://github.com/morpheusadam/lorem-product.git
   ```
2. In WordPress admin, go to **Products → Import**.
3. Upload **`english.csv`** (or **`product.csv`** for Persian data) and click **Continue**.
4. Map the columns (WooCommerce auto-maps the standard headers) and run the import.
5. Your sample catalog appears under **Products** — ready for layout, demo, or QA work.

### About the images

The CSV `Images` column points to absolute URLs (e.g. `https://lavzen.com/wp-content/uploads/demo/...`). To use the bundled photos instead, upload the files from [`img/`](img/) to your own Media Library or server and update the image URLs in the CSV before importing.

---

## 🗂️ Project Structure

```text
lorem-product/
├── english.csv     # WooCommerce sample products (English)
├── product.csv     # WooCommerce sample products (Persian / Farsi)
└── img/            # 23 free demo product images (.jpg)
```

---

## 🤝 Contributing

Contributions are welcome! Open an [issue](https://github.com/morpheusadam/lorem-product/issues) or submit a pull request with additional sample products, more product types (grouped / external), or extra language datasets.

## 📜 License

Distributed under the **MIT License** — see [`LICENSE`](LICENSE) if present. The CSV sample data is free to use in your own projects. Bundled images are free stock photos (sourced from Pexels); review the original Pexels license before commercial redistribution.

---

<div align="center">

### 👤 Author — Morpheus Adam

Web developer & cheerful hacker · PHP · Laravel · Go

<p>
  <a href="https://github.com/morpheusadam"><img src="https://img.shields.io/badge/GitHub-morpheusadam-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://sam.zeonic.me"><img src="https://img.shields.io/badge/Website-sam.zeonic.me-4c1?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
  <a href="mailto:morpheusadam95@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

⭐ **If this sample data saved you time, consider giving it a star!** ⭐

</div>
