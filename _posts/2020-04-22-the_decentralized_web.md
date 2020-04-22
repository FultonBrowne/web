---
title: The decentralized web

---
Most of the web and therefore, what most of us work on is centralized.  There is a client and there is a server.  The client talks to the server, the server gives the client data.  
If the server goes down so does the client. This is the system on top which 99% of apps are made and it was served us well for years, but in some cases it just will not work. Sometimes there too many users and not enough resources. This has recently been the concern of the internet backbone itself and if that went down, we would all have problems. To put it in another context, let’s say you’re running an open source project that relies on a backend.  Most people don’t have a suitable network connection or computer for running even the most basic of web services and cloud services aren’t free. This is where the decentralized web comes in.  Not relying on any single server, computer, or network, the sites on the decentralized web are basically server outage proof. 
 
Decentralized technologies have existed longer than the internet itself with the 1972 implementation known as the Mix Network.  It was used for completely private email that uses a decentralized system to authenticate messages.  Many other networks have been created based off of the basic principles of Mix.  One example is the Onion Routing System and the Tor Browser. There is also decentralized file sharing.  One of the first popular ones was Gnutella, released on March 14, 2000.  It was released as a replacement to Napster which, you know what happened.  More recent systems include ipfs.io and Rardigrade.  These work by storing files with crowd hosted storage.  It is possible to run a static site on these services, something I’ll do here later in this post. 
Last of all is blockchain, I could do an entire post on blockchain (and I will) but here is a quick overview:  
>A blockchain is a growing list of records, called blocks, that are linked using cryptography.  Each block contains a cryptographic hash of the previous block,[6] a timestamp, and transaction data (generally represented as a Merkle tree).

 - [Wikipedia](https://en.wikipedia.org/wiki/Blockchain) 
We will not be going into blockchain based static sites or apps today, but you can expect that in the near future. Ok, let’s get into some coding…
 
We are going to deploy a simple static site using decentralized technologies, storing a basic site on IPFS, a decentralized storage protocol.  This is pretty easy.  First, we need a static site, because I’m lazy I’m going to make a really basic site. 
```
<title>I love IPFS</title>
<h1>Hello IPFS world</h1>
```
You need to download the IPFS utilities and appropriate browser extension [here](https://ipfs.io/#install). Then make a directory and place the html file there, go to ipfs status (there’s a button to that in the browser extension and the hot bar dropdown), select the files tab and upload the folder by hitting 'add'.


![2020-04-03-167405.png](https://fulton.software/web/assets/2020-04-03-167405.png)

![2020-04-03-196768.png](https://fulton.software/web/assets/2020-04-03-196768.png)
 Once that is done you can right click and select ‘share file’ or 'folder' to get the link and view the site. Just as a note, ALL ipfs sites appear as ‘localhost 8080’. It’s just a gateway to IPFS. If you would like to test this on other gateways you can do that [here](https://ipfs.github.io/public-gateway-checker/), you can also view my example on a public gateway [here](https://ipfs.io/ipfs/QmWrv1Ah21wo3McNVBJ6ZVuVR3aBtEvY7w5a28MtoZ27fY?filename=index.html). You can add more file to your directory and use the HTML like any other website. In the near future, I will be deploying my blog to ipfs so stay tuned for that. 
 
The decentralized web is a fantastic set of technologies I can’t wait to learn more about. Next, you can except some static sites on the blockchain, decentralized execution of docker containers, blockchain dApps, and decentralized cloud providers. If you have questions or comments feel free to post a GitHub issue on fultonbrowne/web. 
Have a fantastic rest of your day!  Stay safe and inside.  Thanks.

if you want you can buy me a coffee [here](https://www.buymeacoffee.com/28EcqNL) or help support me by buying some of the computers I am selling on ebay [here](https://www.ebay.com/itm/Dell-precision-3610-16-gigs-ram-6-core-zeon-e5/153834910618) and [here](https://www.ebay.com/itm/153834406902) that would be awesome, I hope to write a post about once a week, so see you then :]