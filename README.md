# Movie Trailer Website

This contains 3 python files which are used to create a movie website that stores data such movie title, storyline, poster, and trailer.

## How to run application
Open the "Marvel.py" file. In the file, you will see multiple instances of various Marvel movies. To run the file, be sure to call the movies class and list all the instances within the Marvel file that should appear on the webbrowswer.

i.e. `movies = [IronMan, IronMan2, IronMan3]`

Be sure to include `fresh_tomatoes.open_movies_page(movies)` so that the file will run the above arguments through the **fresh_tomatoes** module.

## Contents:

### Fresh_Tomatoes
This file was created by adarsh0806, The original code can be found [here](https://raw.githubusercontent.com/adarsh0806/ud036_StarterCode/master/fresh_tomatoes.py).
This file was generated to created to make a website to show the following items:
* Movie title
* Movie poster
* Movie trailer

### Media
In the media file, contains a class `Movie` which has 2 constructors that can helps store movie information.

The first constructor contains 4 instance variable which are  used to store movie information.
* _self.title = movie_title_
* _self.storyline = movie_storyline_
* _self.poster_image_url = poster_image_
* _self.trailer_youtube_url = trailer_youtube_

The second constructor will open a webbrowser to play the trailer to the video to the specific instance.

### Marvel

The Marvel file was created for instances that calls upon the __media__ and __fresh_tomatoes__ files in order to populate a website with Marvel-related movie trailers.
