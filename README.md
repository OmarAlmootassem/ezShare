# ezShare
ezShare is an android application that revolves around the idea of data sharing. The data we are interested in are sharable images taken by users during an event.In order to gain a better understanding of the project, imagine a scenario where a wedding takes place at a location called ‘ABC Banquet Hall’. Our application would allow an event manager to create an event in a defined proximity of ABC Banquet Hall. The event would then be given a derived event ID which would allow other users to join the event and be the part of  the shareable database. Any image captured during the event can be uploaded onto that certain event database which would be accessible to everyone who has joined the event with the event ID. The database used to hold the event information and pictures is built using MySQL and PHP.

##Main Activity
The design of our main view includes the option to get started with the event as soon as you run the application, the User Interface is designed to help normal users join an event instantly. The Event ID is a 5 digit integer that would be derived for each event. The ‘Create Event’ option is available for a super user or the event manager to create the event. The option to ‘Manage Events’ is also available in order to manage all current and previous events a user has been a part of. 

![Main Activity](https://github.com/OmarAlmootassem/Images/blob/master/ezShare1.png?raw=true)

##Create Event Activity
All users would have the option to create an event as demonstrated in our ‘Main View’. Once the user processes a request for a new event, they will be able to view the ‘create an event’ page. Then event manager would have the option to add an event profile picture, an event name and an event location which is connected to Google maps API. Once a user starts entering the address of their location, a drop down menu would appear which would allow users to choose their desired location. 

![Create Event](https://github.com/OmarAlmootassem/Images/blob/master/ezShare4.png?raw=true)

##Manage Events Activity
Each user will have a list of events they have attended or supervised. The list would also display the Event ID’s for each event. The user would be able to ‘Delete’ and ‘End’ events on this page. Each time a user enters an event or creates one, it will be displayed in the ‘Manage Events’ page. 

![Manage Events](https://github.com/OmarAlmootassem/Images/blob/master/ezShare3.png?raw=true)

##Event Activity
The actual event page will display the Event name, Event ID along with the host name and email address. Users would be allowed to upload images which will be displayed in a grid style, as shown in the “Coding the app” event page. Each picture will have a name tag that displays which user uploaded the image. A circular button with an upwards arrow displayed in the image will be used to trigger the upload image command. 
![Active Event](https://github.com/OmarAlmootassem/Images/blob/master/ezShare2.png?raw=true)
