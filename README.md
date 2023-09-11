## Review_Scrapper_Project

#### Introduction:
###### This project, Reviews Sentiment Analysis (RSA), is built upon review scraping technology. The project's primary goal is to assist users in making informed decisions about purchasing products based on reviews provided by people. We have utilized libraries such as BeautifulSoup, Requests, Cross-Origin, and more.

#### Project Overview:
###### Sentiment analysis is a process that identifies and extracts subjective information from source materials, helping businesses gain insights into the social sentiment surrounding their brand, product, or service while monitoring online conversations. In this project, we conducted sentiment analysis on Flipkart reviews using web scraping techniques. We extracted reviews for a specific product on Flipkart and used this data to inform purchasing decisions.

#### Steps involved:
###### •	Go to a Flipkart website
###### •	Search for a particular product
###### •	Locate reviews of a particular product
###### •	Scrap all those reviews in the local system

#### Libraries/Functions used:

###### 1.	**Flask**: Flask is a micro web framework for Python used to develop web applications. It is lightweight and easy to use for building web services and APIs. It is the main library used for creating a web application in this code.

###### 2.	**Request**: The request object is provided by Flask and contains information about the current HTTP request made to the web application. It is used to access data sent by the client.

###### 3.	**Jsonify**: It is a function in Flask that is used to convert Python dictionaries or objects into JSON format, which can be sent as a response from the web server.

###### 4.	**Flask_cors and cross_origin**: These libraries are used for enabling Cross-Origin Resource Sharing (CORS) in a Flask application. CORS is a security feature that controls which web domains can access resources on a web page.

###### 5.	**Requests**: The requests library is a popular Python library used for making HTTP requests to web servers. It is used to send HTTP requests to external websites and retrieve data.

###### 6.	**BeautifulSoup**: It is a Python library used for web scraping. It allows you to parse HTML and XML documents, extract data from them, and navigate their structure.

###### 7.	**urlopen (imported as uReq)**: urlopen is a function from the ‘urllib.request` module that is used to open URLs. In this code, it is used to open web pages for scraping with BeautifulSoup.


#### Conclusion:

###### Through sentiment analysis, I extracted reviews from the Flipkart website for a specific product and saved them to my local system. These reviews can be utilized for sentiment analysis and aid in making informed decisions regarding the purchase of the product.
