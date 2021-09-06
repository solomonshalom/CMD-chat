# CMD Chat
An chat application made in python that can be used in the command line, the code can support multiple clients on one server. The application also allows you to change the IP and Port of your server.

# Prerequisite

- Atom/Visual Studio Code

The main part of coding, an IDE. I would recommand, [Atom](https://github.com/atom) or [Visual Studio Code](https://github.com/microsoft/vscode). The reason I would recommand this IDE because of it's ease of access and tons of extensions.

- Python

Python is necessary for the code to run as it is built upon python. To download it, simply download the installer and install all the files such as PIP and other required files/extensions. 

# Server IP and Port
The current IP is just ```Localhost``` which can be changed to the IP you by opening the CMD on the file directory, and type ```python server-side.py <ip> <port>``` and for the client side, you have to type ```python client-side.py <ip> <port>```. Note that the IP of the server should be same of the client-side in order to chat.

# Running The Code
To run the code, open the command line in the file directory and type ```python Client-Side.py <ip> <port>``` this should activate the code and turn your command line to the client based command line which means you can now send messages to people who are connected to the server. If you want to host the server, you can type ```python Server-Side.py <ip> <port>``` and you can view all the clients connected to your server.
