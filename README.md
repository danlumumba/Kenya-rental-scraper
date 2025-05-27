# 🏠 Kenya Rental Listings Scraper

This project is a Python web scraper that extracts rental property listings from [Property24 Kenya](https://www.property24.co.ke/). It collects data such as property title, location, number of bedrooms and bathrooms, house size, price and description. The data is saved to a CSV file for further use like analysis and visualization with excel or PowerBi.

---

## 📌 Features

- Scrapes multiple pages of rental listings from Property24 Kenya.
- Extracts key property details:
  - 🏡 Title
  - 📍 Location
  - 🛏️ Bedrooms
  - 🛁 Bathrooms
  - 📐 House Size
  - 💬 Description
  - 💰 Price
- Saves the data into a structured CSV file.
- Handles 404 pages and interruptions gracefully.
- Skips empty or incomplete entries.

---

## ⚙️ Requirements

Install the required libraries using pip:

```bash
pip install requests beautifulsoup4 pandas

