# Presentation of the project

## General Objectif

The system is split into three parts :

1. Client to take statistic during a game
2. Camera/PI to record the game and
	* Stream it to the client to save it for later use
	* Stream to the main server
3. A Server to host league informations
	
The main purpose of this system is create a Client to take statistic of a volley ball
game while filming with an external Camera. The time when statistic are happening on the
client are sync with the video tape. The use of this is to quickly filter the video around QUERY
to make better and fast analyse of the game afterward. Like i want all the footage of player
X attacking in the middle and failling to score. And the server is use to store all information
about a league and share footage to other team.

# Specific Objectif

### Client
* Live Game Statistic
	* Point per Point base stat by default
	* Can add interactive court to take trajector of hit, serve ...
	* Can be done for one team of both ( if one team can link to other team stat file)
	* Can link to a video stream to sync each action to a time in video

* Game Statistic Analysation Tool
	* Generate a official game sheet for the league
	* Can display table with the stat of each player
	* Can scroll the game stat Point per Point
	* Filter on player or specific action
	* See chart about low point during the game
	* Will all this the video show what your are looking at
		* Find correct video sequence for stat we are looking at
		* Filter video for stats we want to analyse

* Customize automatic reports
	* Create script to automatically create a detail report about the game
	* Can include video

* Bind client to a league server to host data about the game
	* Share / See live stat from other game you have access with the server

* Portal to League database information

### Video Recording Tool/Server

* Add other camera (http,usb) to have mutiple angle
* Record locally or stream it main server
* Can be bind to client
	* To recieve start/end of point to cut video
	* To redirect video to client ( like past 30 sec )
	* Client directly sends action events marker/oppose to store locally

### League Server

* Database for all Volley-Ball League information
	* League : game stat, video , Calender of Season
	* Player : player who plays on team, link to game stat/info 
	* Club : all team of club link to season from league
* Allow people to acces live information from linked live game
* Connect client/camera to a database to display live information
* Streaming of live game with content layer and multi camera/definition

### WebSite

* Display information about the system ( Princing , how to use it )
* Portal to access Server/database with login instead of the client
* Portal/Tool to admin the League information

