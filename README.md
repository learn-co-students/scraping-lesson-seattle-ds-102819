# Web Scraping Lesson

## Students Will Be Able To:
 - [x] Describe one or more appropriate use cases for scraping
    - Best reason: the source of the data wants to the data to be public, just hasn't invested in making an API (especially common with government or non-profit data sources)
    - Okay reason, depending on context: you want the data, and there's no (free) way to get it without scraping
 - [x] Explain the ethical context of web scraping
 - [x] Determine the [CSS selector](https://internetingishard.com/html-and-css/css-selectors/) of a given element of a web page
 - [x] Write Python code to extract data from a web page using [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
 
### CSS Selector Rules
 - Start with HTML element type (e.g. `div`, `li`, `p`)
 - If you only want elements with a particular class, add a `.` then the class name  (e.g. `div.header-content`)
 - If you only want elements with a particular id, add a `#` then the id name (e.g. `div#contact-list`)
 - You can stack more than one selector at a time.  For example, if you want to select only `p` tags that are inside of `li` tags with class `addresses`, that would look like `li.addresses p`