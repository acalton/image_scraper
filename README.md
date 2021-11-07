# image_scraper
Image scraper service for CS361


Required Python packages:
  Selenium
  Time
  Flask
  
  
Download Chrome webdriver for your Chrome version: https://chromedriver.chromium.org/downloads

  Edit DRIVER_PATH in main.py to reflect location of webdriver on your computer
  
  
Run main.py and route your HTTP request to http://127.0.0.1:5000/result?search_query=hobbit+movie+poster

  Edit hobbit+movie+poster to be your search query
  
  The body of this page has the url to the image
