# Best Movies Scraper

This Python script scrapes information about the top-rated movies from the Beyazperde website and saves the data into a CSV file. The script is designed to loop through multiple pages, extract detailed movie information, and store it in a structured format.

---

## Features

- **Scrapes 30 pages of movie data** from the Beyazperde website.
- **Extracts the following details for each movie**:
  - Title
  - Duration and Genre
  - Director(s)
  - Cast (actors)
  - Original Title
  - Summary
  - User Rating
- **Saves the data** into a CSV file for further analysis or visualization.

---

## Requirements

The script uses the following Python libraries:
- `requests` for making HTTP requests to the website.
- `BeautifulSoup` from `bs4` for parsing the HTML content.
- `pandas` for storing and saving the extracted data in CSV format.

Install the required libraries using:

```bash
pip install requests beautifulsoup4 pandas
```
---

## How to Use

### Clone the Repository:

```bash
git clone https://github.com/your-username/best-movies-scraper.git
cd best-movies-scraper
```

### Run the Script:

```bash
python scraper.py
```

---

## Notes

- The script assumes that the structure of the Beyazperde website remains consistent. If the website's structure changes, you may need to update the HTML selectors used in the script.
- If user ratings are not available for a movie, the script will display "Rating not found" in the output.
- The script is intended for educational purposes and should comply with the website's terms of service.

---

## Contributing

We welcome contributions to improve the script! You can contribute by:

1. **Reporting Issues**: If you encounter bugs or problems, please open an issue on the repository.
2. **Suggesting Features**: Have ideas for new features or improvements? Let us know!
3. **Submitting Pull Requests**: Feel free to fork the repository, make changes, and submit a pull request.

---

## License

This project is licensed under the **MIT License**. You are free to use, modify, and distribute the code as per the terms of the license.
---

## Contact

For further questions or feedback, feel free to reach out by opening an issue on the GitHub repository.

---

