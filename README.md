## ProjectHaste

Amateur project to build a cross-platform application (IOS,UWP,Android) to take detail
volleyball statistic while filming with a rasberry pi the goal to record with a pi
is to allow multiple video stream to be redirect to a remote server for streaming with
a nice layout like on tv and to create a sync file to link to player action/statistic
to a time in the video(start/end) to easily QUERY the video to see the action we want
like every time player X kill the ball from the middle. Also a league remote server is
used to store information about the league. The main feature we wish to work on is a set
of QUERY to easily grep and find information about the game in the league like i talked
for the video earlier.

For more details go in the "Doc" section of the repository , it contains all the definition
of the system ( UML like )

I'm using the README to keep track of what is to do next and what have been done

Technologie planning to use ATM
---

build a backend library in Go for the client and to bind the function to Java and
Object-C for the front-end of the client app for mobile device.
Also for desktop application the same Go library and a local webserver.

The server for league will be host indenpendtly from website and will contains
the api for quick data information abouts league. Written in go

HTML/CSS/JS front-end and backend in Go for the website

For the rasberry pi camera mostly bash script for camera control by a go serve

The first step is the take this slow by making a UML model first
---

- [x] Definition of the system
- [x] Definition of the actor
- [ ] Use Case
- [ ] GUI Design
... other step no yet def ...

Those are the first things for now December 10 to accomplish before going further

After this i guess the main system to build is the backend go library for taking
volley-ball statistic and saving them locally in a local database. With the query
system to quickly acces information from this DB.

After this i wich to build to database for a league server to sync each game DB
to the league server.

...

What is the definition of the system
---

A quick pitch/summary of every part of my system. Its were i put the main idea
for the use of the system.

Who are those actor
---

The actor are every type of external user to the system and the relation between
those actor and the system. Like what each can do and cannot do

What is the Use Case
---

Before build our GUI or men-machine interface we need to make a use case "diagram"
The step in this are :
	* Identify the actors
	* Identify all the utilisation case of every system
	* Assemble them in package
	* Add the relation between those case
	* Finallize the diagrams by adding the actor
After we all this it will be more easy to build our GUI with all the feature
listed in objeAfter we all this it will be more easy to build our GUI with all the feature
listed in objectif.

