﻿# book_scrap
# 📚 Books to Scrape - Web Scraping Project

This project demonstrates a simple web scraping task using Python.  
It scrapes book data (title, price, and image URL) from [Books to Scrape](https://books.toscrape.com/), a website built for web scraping practice.

---

## 🔍 What It Does

- Scrapes:
  - Book titles
  - Prices (removes unwanted characters like `Â`)
  - Image URLs
- Saves the data into a `CSV` file using `pandas`
- Uses simple, readable code — beginner-friendly!

---

## 🧰 Tools & Libraries

- `requests` — to fetch the web page
- `BeautifulSoup` — to parse and extract HTML elements
- `pandas` — to structure and save the data

---

## 💡 How to Use

1. Clone this repository  
   `git clone https://github.com/your-username/books_to_scrape.git`

2. Navigate to the folder  
   `cd books_to_scrape`

3. Run the notebook  
   `books_scraper.ipynb` using Jupyter Notebook or VS Code

---

## 📦 Sample Data

| Title                          | Price   | Image URL                    |
|-------------------------------|---------|------------------------------|
| A Light in the Attic          | £51.77  | http://...                   |
| Tipping the Velvet            | £53.74  | http://...                   |

---

## 🛠 Future Improvements

- Add pagination to scrape multiple pages
- Visualize top-rated books
- Clean and standardize price formats further

---

## 📁 Output

The final CSV file will be saved as: `books_data.csv`

---

## ✅ Status

✔️ Completed - first version ready for portfolio

---

## 📬 Contact

For questions or feedback, reach out:  
**Samson Okunlola**  
📧 samsonokunlola1@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/okunlola-samson-453b56218)  
🔗 [GitHub](https://github.com/Bsam-lab)
