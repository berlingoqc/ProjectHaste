# Presentation of the actor

The presentation of the actor is a definition of every external user
to the system while the system just look like a black boxe , it's
a definition for the later step for building a Use Case Model

### Actors

Drop down of all the actor with a description of what they can do
on the different part of the system. First the user is the basic
configuration for offline ( without an account on a league server )

### User

When use the client without a account to a league server you
can use all the part of the client describe in Def_sys but
the data can only be stored locally on your system like the
video witch can be stored in the pi depending on the conf.
The user can share those file with external storage. First,
export to universal format for the text data and video.

### Player

A player is a type of account on a server league. He must
be link to a Team for a specific season. When he is connect
if allowed by the trainer he can share is data with the client
to the remote server after the game as file or with a live stream

### Trainer

Like the player but also can managed specific tools for scripting
reports and is haved full right on the team for the season he's
linked to. Like adding player account , remove player from team ,
alow player account to add data / stream from their client ,
Can sent praticing schedule to calender and set the training
program for the team

### League administrator

The big administrator of the league server. He add all the base
information in the database from the WebSite portal. He can monitor
and valid information send from various trainer and players. Control
the calendar and etc ...

### Guest

Guess is a user of the website who is not login , he can see public
information about league and watch live stream that the gotten from
shared URL

### Fan

The fan is basically a guest user but with a register account to allow
him to follow public team or player.

### Scoot

Like a fan account but also can be allowed by player to see footage
or stat from player.

![Shema Actor](Actor_Shema.png)


