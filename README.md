# Web Application and Development Project - Planted

The website is a business page for a restaurant called “Planted”. It consists of 8 linked pages: “index.html”, “about.html”, “menu.html”, “gallery.html”, “dom.html”, “stats.html”, “contact.html” and “login.html”.

Each webpage is linked by HTML5. A navigation bar at the top of each page contains a HTML <a> “href” attribute which specifies a relative URL that redirects a user to another page within the website.


## How to Run

The website should be ran while using the Python web server in the same folder to facilitate D3.js elements and to maximize interactive experience. The csv D3 data visualisation will not work otherwise. To run the python webserver:
1.	Navigate to the project folder location through the command prompt.
2.	 Enter "Python -m http.server" on the command line.
3.	Let serve run in the background Leave the server running in the background.
4.	Open browser and enter http://localhost:8000/ in the search bar.
5.	Open the site page.

The Instagram and Facebook social media icons on seen on “index.html” do not link to another page.

The “bookings.csv” file found in the project folder contains the data used for the D3 data visualisation in the “left-half” of the stats.html page.

There is also a images folder within the main project folder which contains all images used for the website.


The navigation bar is found within the <header></header> tags on each page.  The navigation bar is created by placing the link between unorder list tags <ul> and further wrapping each <a> “href” link within a listed item <li> tag.  

The CSS properties for the navigation bar is done via external CSS. The style sheet named “style.css” can be found in the main project folder. It is linked to each page via <link> tag which is wrapped by the <header></header> tags and contains a “href” attribute to the CSS file. I chose to use external CSS for the navigation bar because it was the one element which was include on each page. 
