
# Puppeteer Web Scraper

This project is a Node.js web scraper built with [Puppeteer](https://pptr.dev/), designed to scrape book titles and descriptions from a webpage and save the data to a JSON file.

## Prerequisites

- [Node.js](https://nodejs.org/) (v14 or later recommended)
- NPM (comes with Node.js)

## Setup

1. Clone this repository:
   ```bash
   git clone <your-repo-url>
   ```

2. Install dependencies:
   ```bash
   npm install puppeteer
   ```

## Usage

1. Open `index.js` and replace `'you-url-here-with-hee'` with the URL of the webpage you want to scrape.

2. Run the scraper:
   ```bash
   node index.js
   ```

3. After the script runs, you should see `books.json` created in your project folder, containing the scraped book data in the following format:

   ```json
   [
     {
       "title": "Book Title 1",
       "desc": "Book description 1"
     },
     {
       "title": "Book Title 2",
       "desc": "Book description 2"
     }
   ]
   ```

## Code Explanation

- The script opens a browser using Puppeteer and navigates to the specified URL.
- It extracts book titles and descriptions from elements matching `.service-item` on the page.
- The extracted data is saved in a `books.json` file.

## Connect with Me

[![Fiverr](https://img.shields.io/badge/Fiverr-1DBF73?logo=fiverr&logoColor=white)](https://www.fiverr.com/your-profile-link) **Fiverr Profile**

[![Upwork](https://img.shields.io/badge/Upwork-6FDA44?logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/~your-profile-link) **Upwork Profile**

## License

This project is open-source. Feel free to use and modify it as needed.

---

### Notes:
- Replace `<your-repo-url>` with your GitHub repository link.=
- The badges from Shields.io will automatically display the icons alongside the text for Fiverr and Upwork.
