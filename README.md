# Chat-App
This application is a simple version of a chatting application made using socket.io. The application opens up with a UI that asks the user to put a username and a chatroom name. Two users with the same username cannot exist in the same room and I used validation to ensure that it would never happen. The users are stored inside an array instead of a database as it is a very temporary process. The application uses sockets to ensure that real time communication could happen between different users on the same server. A socket is one endpoint of a two way communication link between two programs running on the network. The socket mechanism provides a means of inter-process communication (IPC) by establishing named contact points between which the communication take place.Socket are generally employed in client server applications. The server creates a socket, attaches it to a network port addresses then waits for the client to contact it. The client creates a socket and then attempts to connect to the server socket. When the connection is established, transfer of data takes place.

How to Run the application:
- Download the files
- go into the file directory and run "npm i"
- run "node app.js"
or just go to "https://thawing-plains-12308.herokuapp.com/"

Below is an attached  picture of the application:

![image](https://user-images.githubusercontent.com/46281169/67625850-b10c0c00-f811-11e9-9c5a-3056e1617fda.png)


<img width="1440" alt="Screen Shot 2022-07-12 at 6 59 21 PM" src="https://user-images.githubusercontent.com/98848760/178507846-68e7450b-5017-4452-8e8f-11ed245cef2d.png">

