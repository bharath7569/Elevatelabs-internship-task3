📰 BBC News Headlines Scraper
This Python script fetches the latest news headlines from the BBC News homepage using web scraping techniques.

📌 Description
The script performs the following tasks:

Sends an HTTP GET request to the BBC News homepage using the requests library.

Parses the HTML content of the page using BeautifulSoup from the bs4 library.

Finds all <h2> tags, which commonly contain news headlines on the BBC website.

Extracts and cleans the text from each <h2> tag.

Stores the headlines in a list and writes them to a local text file named headlines.txt.

Prints the number of headlines successfully saved.

<img width="1714" height="715" alt="Screenshot 2025-08-07 134419" src="https://github.com/user-attachments/assets/b7deef7c-cc72-49fa-aabc-4f7d02060b1b" />
<img width="1342" height="657" alt="Screenshot 2025-08-07 135301" src="https://github.com/user-attachments/assets/276ee7c4-4b14-4294-a589-6b74f3fa4874" />

