# Context
I was tasked to scrape the Y-combinator founders. It's great to have an example to learn from. I found [this](https://github.com/dit-x/y-combinator-scraper) to help me get started. I've streamlined the repo to make the code more readable and simpler. If you want the full bells and whistles, checkout his original repo.
# Skills Requirements
You will have 3 main skills to get started. I've attached tutorial links to learn more about each resource:
1. [BeautifulSoup4](https://www.youtube.com/watch?v=gRLHr664tXA) for HTML extraction
2. [Selenium automation](https://www.youtube.com/watch?v=Xjv1sY630Uc) for scrolling pagination
3. [Multi-threading](https://www.youtube.com/watch?v=IEEhzQoKtQU) for SPEEEED!

# Setup
1. install packages from requirements.txt file
2. If you want to look at the results as of ```W23```, start by running the cell which reads from ```y_company_page_urls.txt```. This will load the companies into a variable called ```y_company_page_urls```
3. If you want to run any cohorts after that, add it to the variable called ```all_batches```

# Troubleshooting
The image below indicates the imformation to be scraped for analysis. If the script fails in the future, it's likely that the HTML class has changed. Watch the above [BeautifulSoup4](https://www.youtube.com/watch?v=gRLHr664tXA) video to learn how to tweak the code for yourself.

![Alt text](https://user-images.githubusercontent.com/55639062/161443204-ae7fc423-f1d3-4512-bb56-7bef85f3691e.png)