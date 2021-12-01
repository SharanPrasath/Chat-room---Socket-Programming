
# Chat-room---Socket-Programming

#ABSTRACT

●	·Chat rooms are Web sites or programs that allow people to send text messages to one another in real time. The chat room works as a virtual room, where groups of people send messages that others can read instantaneously.

●	We are going to build a chat room which is an interface that allows two or more people to chat and send messages to everyone in the room. The aim is to do a chat room server and allow multiple clients to connect to it using sockets in Python.

●	·        The idea is to use the socket module which comes built-in with Python and provides us with socket operations that are widely used on the Internet, as they are behind any connection to any network.

●	·        This involves a client server architecture where there is one server which keeps listening to new client connections formed and messages sent by them, and broadcasts it to the other clients.

●	Motivation to this project is to make communication inside an organization or office or company more reliable and easy to use.


Client:
●	·         Always initiates requests to servers.

●	·         Waits for replies.

●	·         Receives replies.

●	·         Usually connects to a small number of servers at one time.

●	·         Usually interacts directly with end-users using any user interface such as graphical user interface.

Server:
●	·         Always wait for a request from one of the clients.

●	·         Serves clients' requests then replies to the clients with the requested data.

●	·         A server may communicate with other servers in order to serve a client request.

●	·         If additional information is required to process a request (or security is implemented), a server may request additional data (passwords) from a client before processing a request.

●	·         End users typically do not interact directly with a server, but use a client.
 

 


#Requirement Analysis


Hardware Requirements 
<ul>
 <li>Processor	2.4 GHz Clock Speed</li>
<li>RAM	1 GB</li>
 <li>Hard Disk	500 MB (Minimum Space)</li>
</ul


Software Requirements
<ul>

 <li>Operating System Version	Windows 7 and Above</li>
<li>Platform	Jupyter Notebook</li>
 <li>Backend	Python</li>
<li>Special Tools	Socket, Threading, colorama,Playsound
 Server	Server</li>
 
 </ul>


References:
<ul>
 <li>GeekforGeeks</li>
 <li>W3schools</li>
 <li>Python Documentation.</li>
</ul>
