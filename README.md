# Chat-Application
A Java Chat application that makes use of sockets and multicast addresses to send messages via the command line.

# Setup
## Requirements
1. JDK Installed. Click [here](https://www.oracle.com/java/technologies/javase-downloads.html) to install JDK.
2. Command Prompt 

## Steps
1. Make sure you have the java JDK path pre-configured in your environment variables. To configure the JDK path, click [here](https://www.javatpoint.com/how-to-set-path-in-java).
2. To clone this repository, open your command prompt and navigate to the folder you wish to save your project. Use the command ``git clone git@github.com:CyprianKyalo/Chat-Application.git`` to clone the repository.


### The project models two different types of communication:

### a) The Client-Server model
1. To simulate a Client-Server type of communication, open your command prompt and run the command ``javac MyServer.java``, then after successfully running that, run the command ``javac MyClient.java``.
2. If both commands are successful, run the command ``java MyServer``, then in a separate command prompt run the command ``java MyClient``.
3. After running those two commands, a connection is established where you can now start sending messages from the Server to the Client and vice versa.

### a) The Groupchat communication model
1. To simulate a GroupChat, open your command prompt and run the command ``javac GroupChat.java``.
2. After that, open several command prompts and run the command ``java GroupChat <multicast-host> <port-number>``. In ``<multicast-host>`` fill in a multicast address of your choice, and in ``<port-number>``, fill in a port number of your choice. Example, ``java GroupChat 224.0.0.0 330``.
3. After running the commands successfully, you will be prompted to enter your name. Since you are simulating the application on a local environment, you can key in different names.
4. Start sending messages successfully.
