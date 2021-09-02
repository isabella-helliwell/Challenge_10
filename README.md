# Mission to Mars
# 1. Project
  The aim of this project is to add additional information and images to an exsisting web app about Mars.
  For this, we will use BeautifulSoup and Splinter to scrape full-resolution images of Mar's hemispheres and their titles.
  This data is stored on a Mongo database. We also create a web application using FLASK to display the data. The last part of this project
  is to make some changes to the web design with three Bottstrap components.
# 2. Resources
     web application: Jupyter notebook, FLASK
     Software: Python 3.7.6, Splinter, BeautifulSoup, BootStrap
     Database: MongoDB
     websites: https://redplanetscience.com/ ,'https://spaceimages-mars.com', 'https://galaxyfacts-mars.com' , 'https://marshemispheres.com/'


# 3. Summary
   The first part pf the code was given. For the challenge part of the code, I used BeautifulSoup and Splinter to scrape full-resolution
   images of the Mars's hemisphere and also their titles.
   After using DevTools to inspect the webpage, and find the full resolution images of each of the hemispheres, I used jupyter notebook to write
   the code to check for any errors.
   After this step, I updated the scraping.py file to create a function that will scrape the hemisphere data and return the scraped data as a list
   of dictionaries with the url string and title for each hemisphere image.
   Finally, I modified the index.html file to access my database, and retrieve the images and titles.
   I tested to see if the website is mobile-responsive.(ipad.jpg and iphonex.jpg)
   I also modified some web design attributes such as the "scrap button" color, 'Mars Data" table borders and colors. I added background pictures,
   background color and I also created thumbnails for the 4 images of the mars hemispheres.

# 4. Result web app
## 4.1 Results showing the 4 full size images

Before created the thumbnails for the 4 mars hemisphere images, the full images are as shown here:

![mars_hem1](https://user-images.githubusercontent.com/85843030/131866099-c670aee9-c78e-490b-8369-47d28a7ffea1.jpg)
![mars_hem2](https://user-images.githubusercontent.com/85843030/131866138-d8285eb3-ab44-450b-a297-ca39911126ac.jpg)



## 4.2 Final result of the web app, including design attributes and thumbnail images


![image](https://user-images.githubusercontent.com/85843030/131760960-dcf64995-d488-42ad-9783-e8853e00d0c5.png)
![mars_web2](https://user-images.githubusercontent.com/85843030/131761590-0b37058f-aec9-4196-af71-197c5d0762e6.jpg)


     
