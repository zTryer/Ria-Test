# Ria-test

- Scrapes details of used cars from the AutoRia website.
- Extracts information such as URL, title, price in USD, odometer reading, username, car number, VIN (Vehicle Identification Number), image URL, images count, phone number, and datetime found.
- Saves the scraped data to a PostgreSQL database.

Schedule Jobs:
- The spider is scheduled to run daily at 12:00 PM to record data from the website.
- The schedule is modified through a file

## Getting Started

1. Install the required dependencies:

```bash
pip install -r requirements.txt
```
2. Change data in .env to your's database
3. Run the app
