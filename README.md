Deployed on Heroku:
    https://newsfittoscrape.herokuapp.com/ 



# NewsFitToScrapeDD
All The Good News

<!-- Whenever a user visits the site and clicks on the scrape articles button, the app will scrape articles from the New York Times -->

The first article will be displayed with an image and summary of the article. The user can click on the read article button to read the complete article which opens in a new tab.

All the comments for the article are displayed with the option to delete each comment by clicking on the delete button.

The user has the option to enter their name and comment.

At the beginning of each article the user can navigate thru all articles scraped by scrolling through the articles.


Technology Used.

Express is used for routing Mongodb to store the articles and comments. Mongoose is use to build the models for the articles and comments. Cheerio is used to scrape the website for articles. Body-Parser to extract the name and comment from the site to store in the comments collection. Twitter bootstrap to style the site.

***********************************************************************************
