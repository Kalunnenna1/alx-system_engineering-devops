0x11. What happens when you type google.com in your browser and press Enter

![alternative text](https://i.imgur.com/i9ivkdo.png)

![alternative text](https://i.imgur.com/R8R3sqC.png)

Background Context
Being a Full-Stack Software Engineer means you’re comfortable interacting with any layer of the stack.

A way to easily assess this is to simply ask an engineer to explain how a software system works. They can have a general overview of the flow or can choose to dig deep in a certain area.

Let’s practice by exploring the infrastructure side (network, servers, security…) of the question.


What happens when you type google.com in your browser and press Enter?

Every day, we surf the internet, we open up our browsers, and visit websites of our choice. 
The Internet is a global system of interconnected computers that uses the internet protocol suite to communicate between networks and devices. It has made our world a global village that draws everyone closer. The internet has a wide range of information resources and services such as the interlinked hypertext document and the application of the World Wide Web (www) etc.
Ever ask yourself what happens when you type google.com in your browser and press enter?
In this blog, I will give a brief of what happens behind the scene in our browsers and how information is being disseminated via the internet.
What happens when you type google.com is that the browser extracts the domain name from the URL, and the browser queries the DNS for the IP address of the URL. Before I proceed, a brief explanation of the IP address and how its works.
Every machine on the internet has a unique number assigned to it, called an IP address. Without this unique IP address on your machine, you will not be able to communicate with other devices, users, and computers on the internet. This IP address consists of 4 numbers separated by periods e.g. 251.0.122.0.
After the browser queries the DNS for the IP address of the URL, before then the browser will have temporary storage of information about previous DNS lookups on a web browser known as cached domains, and the operating system will have cached queries from any number of applications. If the browser does not have a cached copy of the IP address, then a request is sent off to the system’s configured DNS server. Here, there would be no need for a lookup since the client machine already knows the IP address for the DNS server
Note: The reason why a domain name is used to identify a location on the Internet rather than the numeric IP address is that it’s much easier to remember (a web address is easily remembered than a number)


Now, when you type google.com in your browser and press enter:
a.	It will generate an HTTPS request with headers like (accept, cookies, etc.) – HTTPS is a scheme that stands for Hypertext Transfer Protocol Secure. HTTPS tells the browser to make a connection to the server using Transport Layer Security (TLS) which is an encryption protocol that protects data when it moves between computers. With HTTPS, all communications between your browser and the website are encrypted.

b.	Secondly, the Domain google.com is the domain name of the site. It’s the address of a website that internet users type in the browser URL bar to visit a website.
In a layman’s understanding, if your website was a house, then your domain name will be its address.

