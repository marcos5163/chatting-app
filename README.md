# chatting-app
Chatting app using multi-threading and socket programming

The server runs an infinite loop to keep accepting incoming requests.
When a request comes, it assigns a new thread to handle the communication part.
The sever also stores the client name into a vector, to keep a track of connected devices. The vector stores the thread object corresponding to the current request. The helper class uses this vector to find the name of recipient to which message is to be delivered. As this vector holds all the streams, handler class can use it to successfully deliver messages to specific clients.
Invoke the start() method.
