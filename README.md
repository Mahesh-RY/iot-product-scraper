# IoT Product Scraper

This project scrapes IoT product details from product pages and saves them into **Excel**, **Word**, and **Text** formats.  
Each product is automatically assigned a structured **Product ID** (e.g., `NCRTek-BLE-001`) based on the technology abbreviation.

## 🚀 Features
- Extracts:
  - Product Name
  - Supplier Name & Link
  - Prices (structured)
  - Product Images
  - Auto-generated Product ID
- Saves results into:
  - Excel (`.xlsx`)
  - Word (`.docx`)
  - Text (`.txt`)

## 📂 Project Structure
```
IoT-Product-Scraper/
├── notebooks/
│   └── iot_product_scraper.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

## ⚡ Usage
1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/IoT-Product-Scraper.git
   cd IoT-Product-Scraper
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/iot_product_scraper.ipynb
   ```
4. Enter a product URL when prompted.

## 📊 Output
- Excel: `product_data.xlsx`
- Word: `product_data.docx`
- Text: `product_data.txt`
