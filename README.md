# Restaurant Menu Web Server

A web server for restaurant menu application. The webserver was built using Python and SQLalchemy without additional external frameworks.

### Web Capabilities:
- Displayed list of restaurants from PostgreSQL
- Create new restaurants and save it into the database
- Edit existing restaurants name 
- Delete existing restaurants name

## Requirements
___
You will need the following dependencies installed on your system to run the web server:
- Python 2.7
- PostgreSQL
- SQLalchemy
- cgi

You will also need to make sure that your system port ```8080``` is available. The webserver will run on port ```8080```. 

## How to run the web server
___
to run the web server, simply execute the following command line:
```
python web_server.py
```
Then, you can access the web by entering the url ```http://localhost:8080/restaurants``` to your chosen browser.

To stop the web server, simply do ```ctrl+C```.
