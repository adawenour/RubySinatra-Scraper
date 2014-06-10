# Data Scraping And More With Ruby, Nokogiri and Sinatra!

***

Building a web scraper for scraping and parsing data from websites without an available api or RSS feed to access. I will do this by accessing css selectors from the DOM and extracting the data using the Nokogiri tool alongside ruby. I will then take this information and build a sample application, first as a command line tool with ruby and then as a full Sinatra web app.

The scraper will be scraping a concert sites info to dynamically update concern listings name,location,time,price and will indicate whether they are sold out or not if price is nil in the source code as well as stricking out the sold out concerts name in the application, which will out put the view in a bootstraped listed table. The users will also be able to click on a link and buy tickets for concert that are available using the app.



