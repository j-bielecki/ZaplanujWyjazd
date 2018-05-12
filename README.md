# ZaplanujWyjazd
Just another Android application to help you plan your travel. This app could be useful if you want to get the shortest or the fastest path on the map based on places wchith you have choosen. The application solves Traveling Salesman Problem by trying all posible paths and choosing the best one. Contains a local database (SQLite) with most popular tourist places in Lublin (Poland). It also let you adding your places by the GUI or by loading the configuration file with your places. 
This app ensures internationalization by including all subtitles in separate xml files for each language (Polish and English).  
Using: 
-Google Maps for Android, 
-Google Distance Matrix service, 
-Google Directions service.  

Communication with all those services is based on http protocol. We get a json file as response, which is parsing to get all necessary data.
