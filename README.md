# ChatRoom
A real-time web based chat application with room functionalities built with NodeJS, Socket.io, ExpressJS, and Moment.
Features:
1) Multiple independent chat rooms.
2) Users greeted when joining the chat. Other users cannot see this.
3) When a new user joins a room, all existing users of that room are notified.
4) One to many conversations in the specific room/lobby.
5) New messages are displayed without reloading the app.
6) When user leaves a room or closes the tab, all existing users of that room are notified.


Homepage with Username and Room details:

![alt text](https://github.com/dagrtaru/ChatRoom/blob/master/Snapshots/1.jpg)

A new user Arunarka joins the Javascript room in which user John was already present:

![alt text](https://github.com/dagrtaru/ChatRoom/blob/master/Snapshots/2.jpg)

User John greets Arunarka:

![alt text](https://github.com/dagrtaru/ChatRoom/blob/master/Snapshots/3.jpg)

These messages are not visible to user Kevin who is in Python room:

![alt text](https://github.com/dagrtaru/ChatRoom/blob/master/Snapshots/4.jpg)

Future features might include:
1)Creation and Login of users
2)Private 1-to-1 messaging option
