# Web Scraping with Python: A Basic Tutorial

This tutorial is designed to introduce you to the basics of web scraping with Python. This is split into two parts:

1. **Python and Web Scraping 101**: Provides foundational Python skills necessary for web scraping, along with an introduction to web scraping concepts and techniques.
2. **CEDR_Calder Web Scraping Tutorial**: Focuses on practical exercises in web scraping using different tools such as Selenium and curl_cffi.

---
### Getting Started

To start using the scripts and tools mentioned, click below to open on Colab or download the files and run locally.

 <a target="_blank" href="https://colab.research.google.com/github/Center-for-Education-Data-and-Research/scraping_tutorial/blob/main/python_and_web_scraping_101.ipynb">Python 101 -->
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open Python 101 In Colab"/>
</a>

 <a target="_blank" href="https://colab.research.google.com/github/Center-for-Education-Data-and-Research/scraping_tutorial/blob/main/CEDR_CALDER_webscraping_tutorial.ipynb">Webscraping examples -->
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open Webscraping Examples In Colab"/>
</a>

---

## 1. Python and Web Scraping 101

This section covers the fundamentals of Python, which are essential skills for working in data science, manipulating data, and performing web scraping. Topics include:

- **Why Python?**: Discusses the benefits of using Python for data-related tasks.
- **Python Basics**:
  - **Whitespace and Syntax**: Importance of indentation in Python.
  - **Data Structures**: Strings, lists, tuples, and dictionaries.
  - **Control Structures**: Conditional statements and loops.
  - **Functions**: Defining and using Python functions.
- **Introduction to Web Scraping**:
  - **HTML Basics**: Understanding HTML elements and structure.
  - **XPath & CSS Selectors**: Techniques for navigating and selecting HTML content.

## 2. CEDR_Calder Web Scraping Tutorial

This section provides hands-on exercises using different tools to gather and manipulate data from web pages:

- **Web Scraping with Selenium**: Automate interaction with web pages, extract book titles and other details from an example site.
- **Capture and Save Data**: Instructions on saving scraped data to CSV.
- **Web Scraping with HTTP2**: A more efficient method without relying on JavaScript or Xpath.
- **Accessing APIs Directly**: Reverse engineering to utilize APIs for data collection.

### Tools and Libraries

- **Selenium**: Used for automating and interacting with browsers.
- **curl_cffi**: A Python HTTP client library offering advanced features and session support.
- **selectolax**: An HTML parser to efficiently traverse and manipulate HTML.
- **Rich**: For better console output and logging.

### Practical Exercises

- Scrape book titles, prices, and availability from `books.toscrape.com`.
- Save extracted data to a CSV file.
- Use APIs to get structured data directly from a website.

---

## Resources:

### Documentation:
- [Python](https://docs.python.org/3.12/index.html)
- [Pandas](https://pandas.pydata.org/docs/)
- [Selenium](https://www.selenium.dev/documentation/)
- [Curl_cffi](https://curl-cffi.readthedocs.io/en/latest/)
- [Selectolax](https://github.com/rushter/selectolax)
- [Insomnia](https://docs.insomnia.rest/)
  
### Tutorials and Practice
- [John Watson Rooney @youtube](https://www.youtube.com/@JohnWatsonRooney)
- [CSS Diner - CSS selector challenges](https://flukeout.github.io/)



### License

This tutorial is for educational purposes only. Always ensure you have permission to scrape any website and respect the site's terms of service.