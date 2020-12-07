# CCPS530-Term-Project
Option 2 - Weather Service Application


    Create a single page web site that displays weather related information for the following cities: Toronto
    Manhattan, Rio de Janeiro, Monte Video, Paris, Berlin, Rome, Cairo, Seoul, Shanghai, and Tokyo. The
    weather information may be retrieved from OpenWeatherMap (http://openweathermap.org). A free
    account may be created for the purpose of this project. There may be limits on the number of calls on
    OpenWeatherMap. Hence an ajax call may be used to load each city. There may be a delay of 10 or
    more seconds between subsequent ajax calls for the next city.
    Temperature information may be displayed in a tabular form or on a map. The library Leaflet
    (http://leafletjs.com/) provides the ability to display interactive friendly maps. The mapping service
    used is OpenStreetMap (www.openstreetmap.org). This is a free, open source mapping service.
    This web site should support a certain level of security. In order to use this site there should be login to
    access this site.

Video Demo of the Weather App\
https://streamable.com/8hqz4v


Package.json exhibits which dependencies (packages) are requried for running this project with node  

**As follows:  **

 body-parser  
 ejs  
 express  
 express-session   
 mongoose  
 passport-local  
 passport-local-mongoose  

App.js initializes port 3000 server and routes following views (contained in view folder)\
home.ejs\register.ejs\login.ejs\weatherapp.ejs



