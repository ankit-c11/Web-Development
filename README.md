# MusicWiki App
### The app presents an **organized collection of songs**, grouped primarily under different *Genres*. 
Under each genre, the songs are further grouped under *Albums* and *Artists*. Additionally, there 
is a third tab *Tracks* that lists all the tracks under this genre ***at once***

- Exploring the app features:

    - ### Home Screen
	The home screen shows the top genres to the user and the list expands to show all the available genres.
	To make things convinient for the users, *a _search bar_ has been added* so that users can directly search
	for their choice of genre.
	
	:point_right: Clicking on any genre displays a new genre detail screen to the user.
    
    - ###Genre Detail Screen
	 This screen shows the following:
	 - The name of genre selected on the top left corner.
	 - An info button at top right corner, that shows the information about the genre, when clicked.
	 - Three tabs, *Artists, Albums and Tracks*, only one of which can be selected to be on display at a time.
	   -**Artists**: If selected, lists the various artists who have songs in the selected genre.
           -**Albums**: If selected, lists all the albums having songs of the selected genre.
	   -**Tracks**: Lists all the tracks under this genre.
	 > For all the three tabs avaiable, a different layout for presenting the track/album/artist title and the corresponding cover image has been designed.
    - ### Album Detail Screen
	This screen has the tracks from the chosen album, tracks belonging to the initially chosen genre. The features are:
	- A back button on top left corner, that takes the user back to the genre detail screen.
	- An info button on top right corner, that displays the album information to the user, when clicked.
	- The main screen shows:
	  - The album cover image.
	  - The album title.
	  - The artist and the number of plays from the album.
	  - The other genres this album belong to, can be swiped if exceeds the screen width.
	  - List of all the tracks in the album, with track title, artist name and album cover image.
    - ###Artist Detail Screen
	This screen has the tracks by the chosen artist, tracks belonging to the initially chosen genre. The features are:
	- A back button on top left corner, that takes the user back to the genre detail screen.
	- An info button on top right corner, that displays the artist information to the user, when clicked.
	- The main screen shows:
	  - The artist's image.
	  - The artist's name.
	  - The number of plays for the artist and their follower count.
	  - The other genres this artist has songs in, can be swiped if exceeds the screen width.
	  - List of all the tracks by the artist, with track title, artist name and album cover image.

- ### Assumptions
>
    :point_right: No user would like to manually look for his choice genre in a large list of genres,
		  a **search operation is desired**.
    :point_right: Users might not be interested in knowing about the genre or the album and even the artist.
		  Keeping the textual **information behind a info button gives a better appearance**. 
