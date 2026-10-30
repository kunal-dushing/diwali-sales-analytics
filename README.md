**Live Demo:** https://kd-diwali-sales-analytics.vercel.app

# Diwali Sales Analytics Dashboard

An interactive dashboard for exploring Amazon-style Diwali sales offers and order performance. This is a learning project built with synthetic practice data; it is not affiliated with Amazon and does not show live Amazon offers.
## Features

- Explore 500 synthetic Diwali order records
- Filter by festival phase, category, city, and sales channel
- View revenue, profit, units sold, and profit margin
- Compare revenue and profit by festival phase
- Explore average discounts by category and revenue by product
- Responsive light theme with a festive color palette

## Tech Stack

- HTML, CSS, and vanilla JavaScript
- CSV data file
- Canvas charts drawn in JavaScript
- GitHub repository and Vercel static hosting

## Local Preview

Keep `index.html` and `diwali_orders.csv` together in the same folder. Open the folder in a local web server so the browser can load the CSV. For example, with Python installed, open PowerShell in this folder and run:

```powershell
py -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Deploy

The repository is connected to Vercel. Commit updated files to the `main` branch on GitHub; Vercel will build and publish the new version automatically.

## Project Files

```text
web_dashboard/
├── index.html          # Dashboard layout, filters, and charts
├── diwali_orders.csv   # Synthetic practice order data
└── README.md           # Project overview and instructions
```

## Data Note

All order, price, discount, revenue, and profit values are synthetic and intended for practice. They are not current or historical Amazon sales or offers.



