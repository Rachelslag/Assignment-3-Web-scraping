# Web-Scraping Assignment

For this assignment, I decided to scrape 16 different Wikipedia pages. The Taiwanese government recognizes 16 different indigenous groups, and I scraped the webpage for each tribe. For each tribe, I extracted:

- The **tribe name** (as the title of the Wikipedia page).
- The **content of all the paragraphs** (from the main body of the article).
- The **last modified date**, since no author or publication date is available on Wikipedia.

**Source**: Wikipedia (individual pages for each indigenous tribe in Taiwan).
**Size**: The corpus consists of 16 rows (one for each tribe) and 3 columns:

---

## Data Cleaning

To ensure that the text was usable for analysis, the following cleaning steps were performed:

1. **Removal of empty lines**: Any blank lines or excessive newline characters within the text were removed.
2. **Whitespace cleaning**: Leading and trailing whitespace was stripped from all fields.

---

## Terms and Conditions

The scraping process complies with Wikipedia's [Terms of Use](https://foundation.wikimedia.org/wiki/Terms_of_Use). Wikipedia explicitly allows:

> "You are free to:
>
> - Read and Print our articles and other media free of charge.
> - Share and Reuse our articles and other media under free and open licenses.
> - Contribute To and Edit our various websites or Projects."

The scraped data will only be used for educational purposes in this assignment.

