# FILMSTER

Filmster is an interactive Social Networking web application for sharing Movie ratings and reviews.
It is built on python based DJANGO web framework with search and genre filter functionality using API integration.

### Installation

Using the terminal in the folder, type the following command

bash
python manage.py runserver


## Description

The website fetches the list of movies from the TMDb API and displays it in a no nonsense fashion on the homepage.

Some of the functionalities of the website are:

### Homepage
The homepage or rather every page contains a navbar which can be used for multiple purposes. Other than that the homepage has the new released and currently popular movies shown. We can browse the homepage to know which movies are trending and read or write their respective reviews. The homepage looks like this:

![alt text](https://github.com/kartik31002/FILMSTER-Movie-Review-Website/blob/main/Screenshots/2022-08-07.png?raw=true)
![alt text](https://github.com/kartik31002/FILMSTER-Movie-Review-Website/blob/main/Screenshots/2022-08-07%20(11).png?raw=true)
![alt text](https://github.com/kartik31002/FILMSTER-Movie-Review-Website/blob/main/Screenshots/2022-08-07%20(12).png?raw=true)
### Search
The search bar searches the entered keyword in the API and gives back movies which have the keyword in their title and displays them in a similar fashion as the homepage. An example for the keyword "fight":

![alt text](https://github.com/kartik31002/FILMSTER-Movie-Review-Website/blob/main/Screenshots/2022-08-07%20(14).png?raw=true)
### Genre Selection
We can also display movies by their genre. With a range of 14 different genres, we can see the movies according to the selected genre similar to the home page. Here is the screenshot:

![alt text](https://github.com/kartik31002/FILMSTER-Movie-Review-Website/blob/main/Screenshots/2022-08-07%20(4).png?raw=true)
### Register a user
To write reviews we have to be registered with the sites database. To register we have to click on the register button on the navbar and fill the registration form. We will be automatically logged in and we can continue to browse the website. The registration page looks as follows:

![alt text](https://github.com/kartik31002/FILMSTER-Movie-Review-Website/blob/main/Screenshots/2022-08-07%20(5).png?raw=true)

Redirected to Homepage:

![alt text](https://github.com/kartik31002/FILMSTER-Movie-Review-Website/blob/main/Screenshots/2022-08-07%20(6).png?raw=true)
### Login
If we are already registered. We can login to our account using the login button on the navbar and entering our credentials. If we are not logged in and we want to write a review, we are automatically redirected to the login page. Here is a screenshot of the login page:

![alt text](https://github.com/kartik31002/FILMSTER-Movie-Review-Website/blob/main/Screenshots/2022-08-07%20(13).png?raw=true)
### Individual Movie Page:
To write a review about a movie or to see the reviews given by other users, we have to click on the Reviews & More button on the respective movie. Here you can see the IMDB rating of the movie and a little overview about it. Under that we have the space to write a review. All the written reviews are displayed at the bottom of the page. Here is how this works:

![alt text](https://github.com/kartik31002/FILMSTER-Movie-Review-Website/blob/main/Screenshots/2022-08-07%20(7).png?raw=true)

Writing a review:

![alt text](https://github.com/kartik31002/FILMSTER-Movie-Review-Website/blob/main/Screenshots/2022-08-07%20(9).png?raw=true)

Posted reviews are displayed here:

![alt text](https://github.com/kartik31002/FILMSTER-Movie-Review-Website/blob/main/Screenshots/2022-08-07%20(10).png?raw=true)
