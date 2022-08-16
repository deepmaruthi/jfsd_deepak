# jfsd_deepak
This is our JFSD project
it is a movie app made with HTML, CSS, JavaScript. It pulls movies from The Movie Database using API calls. Users have the option to view the top playing movies, sort them by genre or search for other movies using the search function.
<img width="2251" alt="image" src="https://user-images.githubusercontent.com/93238702/184845019-5b1ef0ec-3fda-4b37-b868-8049431c28d7.png">

This is a movie app made with HTML, CSS, JavaScript using API calls from The Movie Database. It uses API calls to get movies from The Movie Database. Users can view the most popular movies, arrange them by genre, or use the search function to find other titles.
<img width="2328" alt="image" src="https://user-images.githubusercontent.com/93238702/184845123-1a136b98-b5fe-4e3a-9edf-520e50b65f56.png">
Challenge: One of the challenges was making sure that the model would display details on whichever movie was clicked on. Originally, the modal would only display the details for most recent movie (first movie from left to right) no matter which poster was clicked on. This was true without regard to whether the movies were sorted by genre or displaying the latest movies.
Solution: While building the HTML string, I had to include i in the modal portion of the new HTML string to target each clicked poster<img width="4259" alt="image" src="https://user-images.githubusercontent.com/93238702/184845199-27289acc-f8da-4200-8f00-9c97043e1aa8.png">
Technical Information<img width="529" alt="image" src="https://user-images.githubusercontent.com/93238702/184845243-4a856d77-3903-4468-8c14-0688297eb126.png">
To get the data for each movie, I had to run $.getJSON twice, once for the results and the second time to get particular  data for each of those results. Additionally, I used a "for" loop after the first one to target where the data from movieSearchResults is. To make it possible for the app to display movies categorized by genre and searched movies, I initiated an empty HTML string and then built a new HTML string to overwrite it (using .append()``). To change the label on the page accordingly, I had it attached via .html()to themovieGenreLabelid from theindex.htmlfile. You can seeconsole.log()` throughout the code snippet, because I was testing my code at every point to make pinpointing bugs easier.
<img width="5279" alt="image" src="https://user-images.githubusercontent.com/93238702/184845287-eb53511c-1a29-403d-bb5c-038c1f945b3e.png">
Movies are the top source of entertainment, but it can become a hassle to choose which movies to watch as there are countless options. We aim to provide our users recommendations and suggestions, and  also provide a streamlined service and access to many movies across the world. 

This project is to develop a successful  and to  perform a basic movie booking app with OTT platform  to satisfy the customer .
requirements of assigning jobs. It has been developed in HTML, CSS, JavaScript and the database has been built in My SQL server keeping in mind 
the specifications of the system. 
The user will be able to book the ticket using this app . The relationship between company manager, employee, and 
customer satisfy a good communication to complete ticketing process
<img width="2280" alt="image" src="https://user-images.githubusercontent.com/93238702/184845318-e7077e6a-4158-4592-8d7b-bbf24c6559f2.png">
