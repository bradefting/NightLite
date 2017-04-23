# NightLite

NightLite is a web application that allows users to search and share the best locations for stargazing. The app uses ESRI's light pollution map to provide stargazers with locations with the darkest skies so they get a better view of the stars.

Link to website deployed site: [https://bradefting-nightlite.herokuapp.com/](https://bradefting-nightlite.herokuapp.com/)

![Image of NightLite home page](https://github.com/bradefting/NightLite/blob/master/public/imgs/NightLite_site.png?raw=true)

### Features

1. From the home page, guest users can access the explore page to learn more about light pollution or they can login.
2. The explore page provides a brief description of light pollution and shows a visual comparison of how it affects the night sky for stargazers.
3. The login page allows users to create a new account or to login with their existing credentials.
4. After logging in, users have access to the light pollution map that displays observation points created by users. Users can search for specific locations by entering a zip code, city, or mailing address. As users scroll the page, they'll see more information about each plotted observation location including a star rating from the user that posted the observation and comments about the location from other users. On this page, users can also add, update, and delete any of their observations and comments and administrative users have the privilege of adding, updating, and deleting the comments and observations of all users.

### Technologies

1. **ESRI ArcGIS:** Light pollution map that visually displays how much light pollution is in a given area. Also used to plot observation points on the map given the coordinates of the point.
2. **PostgreSQL:** Relational database that stores user information, observations, and comments.
3. **Materialize:** Used to create the front-end design.
4. **Express:** Framework used to create RESTful routes.
5. **Heroku:** Used to deploy the application.
6. **Pivotal Tracker** Project management software used to create and prioritize stories, track progress of stories, and organize tasks among team members.  

Video walkthrough of the app: [https://www.youtube.com/watch?v=aJO_bQ4lRUc](https://www.youtube.com/watch?v=aJO_bQ4lRUc)

---
NightLite Whiteboard Wireframes: <a href=https://github.com/bradefting/NightLite/blob/master/public/imgs/NightLite_Wireframe.JPG?>NightLite Whiteboard Wireframes</a>

---
