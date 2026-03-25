# eBay Data Downloader

## Overview
`ebay-dl.py` is a Python script that downloads product listing data from eBay search results and saves the data to a file.

The script:
- takes a search term as input  
- loops through multiple pages of eBay results  
- extracts key information for each listing, including:
  - name  
  - price  
  - shipping cost  
  - condition  
  - number of items sold  
  - free returns status  
- stores the results in a structured format  

By default, the script outputs a **JSON file**, and optionally can also generate a **CSV file**.

Link to Project: 
https://github.com/mikeizbicki/cmc-csci040/tree/2026spring/project_02_webscraping

**Note:** 
I was only able to retrieve page html once throughout the entire project before being blocked with a Pardon Our Interruption result with each subsequent attempt. Thus, I was unable to retrieve any scraped valid scraped data. 
