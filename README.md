# How Does the Web Work?
If you are working in web development or cybersecurity or information security, you must have a basic understanding of webpage and what’s going on behind the scenes.
If you don't know how the web and backend work, how you are going to secure.  Below I discuss some basic things to understand how web works.
Let's dive right in…

- **Contents**
  - What is Web?
  - Components of Web
  - How does the web work?
  - How does information be transmitted on the web/internet?
  - How does TCP/IP work for the Web?

# What is Web? 
  - The Web is known as a client-server system. Your computer is the client and the remote computers that store electronic files are the servers.
  - Here are some important terms or components of web to have a deep understanding of secret of the World Wide Web...

# Components of Web
 - **Client**
   - It means an application, such as Chrome or Firefox, that runs on a computer and is connected to the internet. Its job is to take requests and send them to another computer called a web server.
Although we typically use a browser to access the web, you can think of your whole computer as the “Client” piece of the client-server model. Every client computer has a unique address called an IP address that other computers can use to identify it.

 - **Server**
    - It is a remote computer which provides information or particular services and also has an IP address.  A server waits for requests from other machines (e.g. a client) and responds to them.
The server has special server software installed and running which tells it how to respond to incoming requests from your browser. The primary function of a web server is to store, process and deliver web pages to clients.
There are many types of servers, including web servers, database servers, file servers, application servers, and more.
(In this paper, we’re talking about web servers.)

 - **IP Address**
   - It is a unique address that identifies a device on the internet or on the local network. Every computer on the internet has an IP address that it uses to identify and communicate with other computers.  It looks like this
104.16.66.85

 - **An internet connection**
   - This is provided by an ISP and connects you to the internet to reach to any Website.
Internet Service Provider. ISP is the middle man between the client and servers. When your browser gets a request from you to go to www.github.com, it doesn’t know where to look for www.github.com. So it’s the ISP’s job to do a DNS (Domain Name System) lookup to ask what IP address the site you’re trying to visit is configured to.

 - **DNS**
   - Domain Name System. A distributed database which keeps track of computer’s domain names and their IP addresses on the Internet. DNS exists so users can enter www.github.com instead of an IP address.
  
 - **Domain Name**
   - Users use the domain name (e.g.
www.github.com to get to a website on the internet. When you type the domain name into your browser, the DNS looks up the IP address for that given website. It’s like the phonebook of the internet having the name (domain name) and phone number (IP address) of everyone.
when you click on the name it will directly call the phone number you do not need to memorize the IP address.

 - **Protocols**
   - They are the certain set of rules that the client-side (browser) and server-side follow to communicate with each other.
  
 - **TCP/IP**
   - Transmission Control Protocol/Internet Protocol is used for communications protocol. TCP/IP is used as a standard set of rules for transmitting data over networks.
  
 - **Ports**
   - They are virtual places within an operating system where network connections start and end. Ports are software-based and managed by a computer's operating system. Each port is related with a specific process or service. Ports allow computers to easily differentiate between different kinds of request: emails go to a different port than webpages,, even though both reach a computer over the same Internet connection.
   - Suppose Adam transfers an MP3 audio recording to John using the File Transfer Protocol (FTP). If Johne's computer passed the MP3 file data to John's email application, the email application would not know how to interpret it. But because Adam's file transfer uses the port designated for FTP (port 21), John's computer is able to receive and store the file.
Meanwhile, John's computer can simultaneously load HTTP webpages using port 80, even though both the webpage files and the MP3 sound file flow to John's computer over the same WiFi connection.

  - **Host**
    - A computer connected to a network — it can be a client, server or any other type of device. Each host has a unique IP address. For a website like www.google.com, a host could be the web server that serves the pages for the website.
   
  - **HTTP** 
    - Hyper-text Transfer Protocol. The protocol that web browsers and web servers use to communicate with each other over the Internet. Web server stores all data of any website in HTTP format.
 
  - **HTTPs**
    - Hypertext transfer protocol secure (HTTPS) is the secure version of HTTP, which is the primary protocol used to send data between a web browser and a website. HTTPS is used to encrypt the data for security. This is p important when users transmit sensitive data, such as by logging into a bank account, email service, or health insurance provider.
Any website, especially those that require login credentials, should use HTTPS.

 - **URL**
   - Uniform Resource Locators. URLs identify a particular web resource. A simple example is
https://github.com/someone. The URL specifies the protocol (“https”), host name (github.com) and file name (someone’s profile page).

# How Web Works?
  - You type a URL into your browser.
