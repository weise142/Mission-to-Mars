# Mission-to-Mars
## Overview
This project consisted of writing a Python script to scrape text and images from websites that discussed NASA's mission to Mars. Once I scraped this information, I then created a Flask web application with a rendered HTML template designed using Bootstrap to display the data in a centralized location so we do not have to gather it manually. The scraped data was stored in a non-relational MongoDB Database. I also created the application so that each time a button was clikced, the scraping occurred once again so the most up to date information was being pulled from the webpages, however, this button only works if the webpages don't change their HTML components. In using Bootstrap, I was able to create a web page that works on all sorts of devices such as phones when not being used on a computer.
## Resources
- Webpages Scraped
  - https://data-class-mars.s3.amazonaws.com/Mars/index.html
  - https://spaceimages-mars.com
  - https://galaxyfacts-mars.com
  - https://marshemispheres.com/
- Software and Packages Used
  - Python
  - Jupyter Notebook
  - Pandas, Beautifulsoup, Splinter, Chromedrivermanager, Flask, PyMongo
  - MongoDB
  - HTML
  - Bootstrap
## Summary
The final application was a fully functional web application using Flask that included images, an informational table on Mars in comparison to Earth and the latest article titles with summary from NASA's webpage. As stated earlier, when  we use the scrape new data button the newest information is scraped from these websites and updated on the application and the database in MongoDB. 
![This is an image](https://github.com/weise142/Mission-to-Mars/blob/main/table%20Mars.PNG)
![This is an image](https://github.com/weise142/Mission-to-Mars/blob/main/Newest%20article.PNG)
The scraping of these websties includes the Title of article followed by a brief summary of the article, includes a table with facts on Earth and Mars and picture thumbnails with their titles. Additionally, the MongoDB database will be updated each time new data is scraped and will include a last modified date when saved so we know when the most recent update occurred and track the progression of the data.
