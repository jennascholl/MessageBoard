# Overview

In order to further my learning as a software engineer, I created this project to learn and demonstrate basic knowledging of networking applications.

This is a simple message board that allows active users to send messages to each other using a server and a client. To use, you will need to begin by running the server. Then, run the client code from a new terminal to connect to the active server and start sending messages. You will need to run the client code from multiple terminals to send messages to/from multiple users. 

My purpose in writing this software is to get an idea of how networking is accomplished in Python so that I can use and expand upon this knowledge in future projects.

[Software Demo Video](https://youtu.be/Fy_iwFMhtn4)

# Network Communication

This project utilizes client/server communication.

I used Transmission Control Protocol (TCP) and port number 2022.

Messages are sent between the client and server as bytes, using the built-in encode() and decode() methods.

# Development Environment

This code was written in Visual Studio Code using Python. 

# Useful Websites

{Make a list of websites that you found helpful in this project}
* [Simple GUI Chat in Python](https://www.youtube.com/watch?v=sopNW98CRag&t=636s&ab_channel=NeuralNine)
* [Python Server Libraries](https://docs.python.org/3.6/library/socketserver.html)

# Future Work

* Provide support for multiple kinds of requests that the server can respond to
* Modify the server to obtain information from a local file or database in response to a request from the client