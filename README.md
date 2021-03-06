<p align="center">📢<sub><sup> <i><b> YOUR SUPPORT IS GREATLY APPRECIATED / </b> <a href="https://www.patreon.com/donPabloNow">PATREON.COM/DONPABLONOW</a> / <b>BTC</b>  3HVNOVVMLHVEWQLSCCQX9DUA26P5PRCTNQ / <b>ETH</b> 0X3D288C7A673501294C9289C6FC42480A2EA61417 </i>🙏 </sub></sup></p><blockquote><p> ⛔️ <sub><b>ARCHIVE PENDING</b>: This endeavour is likely to fail owing to a lack of support. If you find this project interesting, please support it by smashing the "star" button. If the project receives at some interest work on the project will continue.</sub></p></blockquote></br><a href="https://www.donPabloNow.com/#notice"><img src="https://www.donPabloNow.com/notice.wepd"/></a></br></br>

![image](https://user-images.githubusercontent.com/6468571/169415768-b4f3c843-431b-4423-9ff2-012319cba8b4.png)
![image](https://user-images.githubusercontent.com/6468571/169420299-b05fe9a3-4b36-4ea2-b601-0362a781a76f.png)

[![Docker Pulls](https://img.shields.io/docker/cloud/build/web3pablo/dockertor.svg?style=flat-square)](https://hub.docker.com/r/web3pablo/dockertor/)

### Dockertor is the most popular application for running a load-balanced Tor proxy pool inside a Docker container

With The Dockertor you can Mix and match (IP rotation, country selection of the exit node, etc). Linux Privoxy HTTP proxy containerized HTTP and Socks are supported by HAProxy. Docker does not need root privileges.

![image](https://user-images.githubusercontent.com/6468571/169420299-b05fe9a3-4b36-4ea2-b601-0362a781a76f.png)

![image](https://user-images.githubusercontent.com/6468571/169418204-f03647ce-2d32-4ef9-aa21-40216a531893.png)

An Alpine Docker image that runs the multitor program is shown here. It was developed specifically for Alpine. The Proxy that is generated by Multitor is composed of several load-balanced instances of TOR that are always operating in the background in the background.

The purpose of this project is to make available an image that, when combined with Tor, Delegate, and Haproxy, may be used to generate a pool of dynamic IP addresses. This image will install ten Tor clients, ten Delegate (one for each Tor), and Haproxy so that it can handle anything that exposes port 9200 & 9300.

![image](https://user-images.githubusercontent.com/6468571/169417871-d939c20f-1dda-42a6-b72d-a970f77c31d4.png)

Kali Linux is a Debian-based Linux system designed for digital forensics and penetration testing. Kali Linux comes preloaded with over 600 penetration-testing applications, such as Armitage (a graphical cyber attack management tool), Nmap (a port scanner), Wireshark (a packet analyzer), John the Ripper (a password cracker), Aircrack-ng (a software suite for penetration-testing wireless LANs), Burp suite, and OWASP ZAP web application security scanners.

It was designed by Mati Aharoni and Devon Kearns of Offensive Security.
Virtual Machine – In computing, a virtual machine (VM) is an emulation of a computer system. Virtual machines provide the capabilities of a physical computer based on computer architectures. Their implementations may use either specialized hardware or software, or both.

![image](https://user-images.githubusercontent.com/6468571/169417973-f97203c1-37d2-4042-9261-aad47ae8dd41.png)

Tor is a free, open-source program that facilitates anonymous communication. Tor sends Internet data across a free, multinational, volunteer overlay network of over seven thousand relays in order to conceal a user's location and behavior from network surveillance and traffic analysis. Tor makes it more difficult to monitor a user's Internet activity, such as "visits to websites, online posts, instant chats, and other forms of communication." Tor's objective is to protect the privacy and freedom of its users, as well as their ability to communicate in secret, by preventing the surveillance of their Internet activities.

Privoxy — Privoxy is a free, non-caching web proxy with filtering capabilities for enhancing privacy, modifying cookies, and modifying online page data and HTTP headers prior to page rendering. Privoxy is a "privacy-enhancing proxy" that filters web pages and eliminates advertisements. Privoxy may be modified for both solitary systems and multi-user networks. Privoxy may be chained with other proxies and is often used with Squid, among others, to bypass Internet filtering.


![image](https://user-images.githubusercontent.com/6468571/169415607-850d1271-12e1-484c-b73f-11388bf5fde8.png)

This container's basis consists of both a load-balancing Tor pool and an HTTP proxy. No matter how many Tor instances are active, a user can never simultaneously connect to more than one endpoint. Regardless of the amount of active Tor instances, this remains true. This will always remain the case, irrespective of the number of open programs or concurrent processes. At this level, bringing everything together is a breeze (IP rotation, country selection of the exit node, etc). Using the Alpine operating system, an ultra-lightweight Docker image was produced. Privoxy might be regarded a protocol intermediate for HTTP. This is among its numerous applications. HAProxy may be capable of concurrently processing HTTP and Socks traffic provided specific conditions are satisfied. This functionality does not need Docker users to have access to the root user account. Docker does not need root access from its users.

![image](https://user-images.githubusercontent.com/6468571/169418029-901a8e5c-38db-46c8-ad8a-1c8e6ed98dcc.png)

![image](https://user-images.githubusercontent.com/6468571/169420299-b05fe9a3-4b36-4ea2-b601-0362a781a76f.png)

![image](https://user-images.githubusercontent.com/6468571/169418122-bf8191be-2d9b-4b6c-9acf-0100dfee9537.png)


# Application

The tor software's primary purpose was to launch as many TOR processes as possible as quickly as possible. I will most likely offer many examples from real-life scenarios (web browsers, messangers and other). In addition, when doing penetration tests and assessing the security of an infrastructure, I sought for a tool that would strengthen my anonymity. Before you use Tor, you should be aware that it already aims to provide you with a diverse range of streams. It already does load balancing (far better than HAproxy), but its primary objective is to conceal the origin of requests by diverting them to other streams. From this vantage point, it seems to be load distribution. Identifying the source of an attacker may be difficult and time-consuming in many circumstances. 

You will be aware of every activities if you use http/https servers, such as proxy servers, to accomplish your operations. This is because these servers provide access to the underlying network. In contrast, if you have many instances of TOR operating at the same time, your circuit is more likely to be hacked. Tor receiving bandwidth has been increased. The tor setup uses proprietary technology to connect to the TOR network. HAProxy is the only TOR node that uses the syn and syn/ack protocols to check a local connection before joining (also exist nodes). If an error occurs, the socket will attempt to divert traffic to other available sockets so that future events are not disrupted. Even if it transmits traffic to other sockets, it cannot guarantee that the data will arrive at its intended destination. 

Because the TOR network is a distinct entity from Tor, its actions have no bearing on its behavior. If one of the nodes fails and data cannot flow via the exit node, a connection error is generated and the data is relayed over another local socket. If a node fails, data cannot be routed via the exit node. HAProxy distributes network traffic across the local TOR or http-proxy processes operating on a specific system rather than between TOR network nodes. The Onion Router (TOR) is a fantastic security endeavor and an important component of a defense-in-depth approach; but, it does not enable anonymity, which is a significant shortcoming. If a secure connection (such as https) is available, use it while installing TOR.

When you run the program for the first time, it will set your port to a static port that you choose, making it easier for you to map a proxy to. In the event that this is the sole process operating on your machine, you may map the port to 9100 without the requirement for a proxy. i.e. -p=9100:9100.

Begin 5 Tor instances:

```bash

docker run -d -p 9200:9200 -p 9300:9300 web3pablo/dockertor:1.0.3 --Tors=5

```

The HTTP proxy is available on port 9300:

```bash
curl --proxy localhost:9300 http://ipinfo.io/ip
```

Socks may be accessed through port 9200:

```bash
curl --socks5 localhost:9200 http://ipinfo.io/ip
```

To have Tor instances rotate, do the following:

```
docker run -d -p 9200:9200 -p 9300:9300 web3pablo/dockertor:1.0.3 --MaxCircuitDirtiness 30 --NewCircuitPeriod 30
```

Only use US exit nodes:

```
docker run -d -p 9200:9200 -p 9300:9300 web3pablo/dockertor:1.0.3 --ExitNodes {us}
```

[List of available Tor options](https://www.torproject.org/docs/tor-manual.html.en)

To view HAProxy stats page:

```
docker run -d -p 9200:9200 -p 9300:9300 -p 9500:9500 web3pablo/dockertor:1.0.3
```

Then, in a browser, go to http://localhost:9500/haproxy stats and enter your HAProxy login and password. The default username and password are 'haproxy' and 'password,' respectively, although they may be modified using the volume mounting:

```
echo "pss" > pass_file
docker run -d -p 9200:9200 -p 9300:9300 -p 9500:9500 -v "$PWD/pass_file":/run/secrets/haproxy_password web3pablo/dockertor:1.0.3
```

Expected password location: `/run/secrets/haproxy_password`, username: `/run/secrets/haproxy_username`.

#### Docker-compose example:

```yaml
version: '3'
services:
  dockertor:
    image: web3pablo/dockertor:1.0.3
    command: [ '--Tors', '2', '--NewCircuitPeriod', '30', '--MaxCircuitDirtiness', '30' ]
    container_name: dockertor
    ports:
      - "9200:9200"
      - "9300:9300"
      - "9500:9500"
```
![image](https://user-images.githubusercontent.com/6468571/169420299-b05fe9a3-4b36-4ea2-b601-0362a781a76f.png)

![image](https://user-images.githubusercontent.com/6468571/169418260-7311e4c5-356e-4d25-a658-0af37b117e6a.png)

# The most frequently asked questions

## Q: Am I completely anonymous while using Tor?

No, Even with Tor, it is almost hard to maintain perfect anonymity. Even if you're not using Tor, there are a few steps you may do to increase your anonymity. Utilize the Tor Browser with suitably configured software for Tor. Not all of your Internet traffic is encrypted while using Tor; just a portion is. To take use of Tor's security features, applications must be configured to route their traffic over Tor. 

![image](https://user-images.githubusercontent.com/6468571/169418925-5481b345-451a-471f-af4c-ff556f2be88e.png)

Tor Browser is the only viable browser that utilizes Tor as a proxy; all other browsers should be avoided. The file-sharing platform OnionShare may be relied upon. Using Tor with BitTorrent is unsafe. You have total control over the information you provide via online forms. If you use Tor Browser to surf the internet, the websites you visit will be unable to detect your identity or location. Numerous websites' online forms request significantly more personal information than is necessary. Even if you join that website, your location cannot be discovered, but your identity may be determined. In addition, your anonymity on that website will be compromised if you provide your name, email address, physical address, phone number, or any other personal information. Filling out online forms with considerable care is the most effective strategy to protect yourself against Internet scammers.

The use of Tor to torrent is not advised. Even when advised to use Tor, torrent file-sharing software has been demonstrated to disobey proxy settings and establish direct connections. This behavior has been seen previously. Due to the nature of torrents, the tracker GET request will often request your IP address. Even if you just use Tor to communicate with your torrent client, this is the case. As a consequence, not only does your torrent activity and any other concurrent Tor web traffic become much less anonymous, but so does the whole Tor network. Browser plugins should not be installed or active. Tor Browser blocks Flash, RealPlayer, and QuickTime plugins because they may be abused to reveal your IP address. Likewise, any additional add-ons or plugins for Tor Browser may undermine your anonymity and privacy. Utilize only encrypted websites (HTTPS). All of your communication to and from the Tor network is encrypted when you use Tor, but the traffic you send to the website that acts as your final destination is not. HTTPS Everywhere is a Tor Browser feature aimed to force users to encrypt their traffic to large websites wherever feasible via HTTPS. Keep a watch on your browser's address bar to ensure that websites to which you transfer sensitive information have a lock icon or onion symbol, utilize https:// in their URLs, and display your expected website name. 

![image](https://user-images.githubusercontent.com/6468571/169418938-24c588e4-142c-4751-bfe2-f411e62973b8.png)

The EFF's interactive diagram illustrates the relationship between Tor and HTTPS. While connected to the internet, you should not view files downloaded through the Tor network. If Tor Browser tries to open a document that is handled by an external software, a warning will show. If you are not using the Tor Browser's PDF viewer, you should exercise extreme caution while downloading documents over Tor, particularly DOCs and PDFs. The program that opens these documents may download Internet resources outside of the Tor network. This is feasible even while using the Tor Browser's built-in PDF reader. 

When Tor is not in use, your IP address will be shown. If you must work with Tor-obtained material, utilize a workstation that is not connected to the internet or the dangerzone program to generate secure, openable PDF files. Using BitTorrent and Tor together is fundamentally risky. Utilize current relationships or aggressively seek out new ones. Tor attempts to conceal your internet actions so that your opponents cannot see them. Since this information is not disguised by default, anybody eavesdropping on your Internet traffic may immediately determine whether or not you are using Tor. By using a bridge as opposed to a direct connection to the Tor network, this danger may be mitigated. If you like to discover more, please continue reading. 

![image](https://user-images.githubusercontent.com/6468571/169419046-77b276d6-1fa7-4cd0-8ee6-ea679383855e.png)

The greater the number of Tor users around you, the less probable it is that you are one of them. Persuade others to use Tor with you! Develop critical thinking abilities and a larger information base. Before use Tor, be sure you understand what it can and cannot do. Therefore, we need your assistance in detecting and classifying any possible dangers.

## Is it possible for Tor  to circumvent website censorship and access restrictions?

Tor Browser may undoubtedly assist individuals in gaining access to your website in locations in which it is prohibited. The majority of the time, gaining access to a website that is prohibited may be accomplished by simply installing the Tor Browser and then utilizing it to browse to the website in question. We have a variety of methods available to overcome the strong censorship that exists in some areas, including pluggable transports, and these options are open to us. Please refer to the part of the Tor Browser User Manual under "Censorship Circumvention" for any more information.

## Is it possible to utilize a virtual private network with Tor?

We do not advocate utilizing a virtual private network (VPN) in conjunction with Tor unless you are an experienced user who is aware of how to setup both services in a manner that does not jeopardize your privacy.

On our wiki, you'll discover further information that goes into greater depth about Tor and VPN.

## Which assaults against onion routing are still possible?

As was just mentioned, it is possible for an observer who can view both you and either the destination website or your Tor exit node to correlate the timings of your traffic as it enters the Tor network and also as it exits the network. This can be done by viewing both the destination website and your Tor exit node. Tor does not provide protection against a threat model of this kind.

In a more constrained sense, it is important to keep in mind that if a censor or law enforcement agency has the ability to obtain specific observation of parts of the network, it is possible for them to verify a suspicion that you talk regularly to your friend by observing traffic at both ends and correlating the timing of only that traffic. In other words, if they have the ability to obtain specific observation of parts of the network, it is possible for them to verify a suspicion that you talk regularly to your friend. Again, this is only relevant for confirming that parties who are previously suspected of communication with one another are in fact speaking with one another. In the majority of nations, the level of suspicion needed to get a warrant already bears more weight than the evidence that would be provided by temporal correlation.

![image](https://user-images.githubusercontent.com/6468571/169419078-21ca395e-0faf-4ccf-a237-d9350c82004d.png)


Additionally, since Tor reuses circuits for numerous TCP connections, it is feasible to link non-anonymous traffic with anonymous traffic at any given exit node. Because of this, you should exercise caution with regard to the applications that you run simultaneously through Tor. It is even possible to use distinct Tor clients for each of these apps.

## What kinds of safeguards are offered by Tor?

The store-and-forward concept, which may be understood by analogy to the way mail is sent, is the foundation of internet communication: Blocks of data are sent across an IP network in what are known as IP datagrams or packets. Every single packet has both a source IP address (which belongs to the sender) and a destination IP address (which belongs to the receiver), similar to how regular letters have the sender's and the recipient's postal addresses. The path that a packet takes from the sender to the receiver includes numerous hops of routers. At each router, the destination IP address is inspected, and then the packet is sent to the next router in the chain. As a result, any router that stands in the between of the sender and the receiver finds out that the sender is interacting with the recipient. In particular, the Internet service provider in your area is in a position to compile an exhaustive profile of your Internet activity. In addition, any server on the internet that has visibility into any of the packets may create a behavioral profile of you.

![image](https://user-images.githubusercontent.com/6468571/169419096-7e8832b2-73c9-4a97-9c7e-8c3e57b6c9d6.png)

The purpose of the Tor network is to enhance users' anonymity by routing their Internet traffic via a network of proxies. Your communication is encrypted using a number of different levels, and it travels to the end recipient through the Tor network via a number of different hops. This representation provides more information on the procedure that is being followed. Take note that the only thing your local Internet service provider can see right now is the fact that you are connecting with Tor nodes. In a similar manner, servers on the Internet simply recognize the fact that they are being addressed by Tor nodes.

Tor was designed with the following three concerns of privacy in mind:

To begin, Tor prevents websites and other services from discovering your location, which they might then use to develop databases about your routines and hobbies if they had this information. With Tor, your Internet connections will not, by default, give away your location; instead, you will have the opportunity to choose, for each connection, how much information to expose about yourself.

![image](https://user-images.githubusercontent.com/6468571/169419188-7f487721-765a-4492-aee2-2aacb79d902c.png)

Second, Tor makes it impossible for those who are monitoring your traffic locally (such your Internet service provider or someone who has access to your home wifi or router) to figure out what information you are retrieving and where you are retrieving it from. If you are able to connect to any portion of the Tor network, you will be able to access any website that is available on the internet. This prevents them from selecting what you are permitted to study and post.

Third, Tor conceals your online activity by routing your connection via many Tor relays simultaneously. This prevents any one relay from discovering what you are doing online. The traditional method of using a single hop proxy offers a lower level of security when compared to the distributed trust model, which uses many relays that are each managed by a separate person or organization.


![image](https://user-images.githubusercontent.com/6468571/169419242-65f65b42-1cd3-4ba8-9cf9-2d2bf2423389.png)


It is important to keep in mind, however, that there are certain instances in which Tor is unable to address these privacy difficulties altogether; for more information about remaining assaults, see the entry below.

## What exactly is Tor?

There are many distinct things that may be referred to by the term "Tor."

Tor is a tool that may be installed on your computer and used to assist in maintaining your privacy and security while using the Internet. Your communications will be bounced around a distributed network of relays that are operated by volunteers all over the world. This will protect you in two ways: first, it will prevent anyone who is monitoring your Internet connection from discovering the websites that you visit, and second, it will prevent the websites that you visit from discovering your physical location. The term "Tor network" refers to this collection of volunteer relays.

![image](https://user-images.githubusercontent.com/6468571/169419264-05e4e247-362e-4eeb-bc18-242a7324f136.png)

The majority of users access Tor using the Tor Browser, which is a modified version of Firefox that addresses a variety of concerns pertaining to users' privacy. You may learn more about Tor by visiting our page under "about."

The Tor Project is an organization that is run entirely on donations and is responsible for the upkeep and development of the Tor software.

## What does the name Tor stand for?

The onion routing network is known as Tor. In the years 2001 and 2002, while we were in the process of initiating the new next-generation design and execution of onion routing, we would tell people that we were working on onion routing, and they would remark that they had heard of onion routing "Neat. In which case?" Even though the phrase "onion routing" has entered common parlance, the onion routing effort that led to the development of Tor was actually carried out by the Naval Research Laboratory.

![image](https://user-images.githubusercontent.com/6468571/169419372-0f990b18-a442-49e1-87ca-bc7fd249bd00.png)

Note that while Tor was initially derived from an acronym, the name does not really consist of the letters "TOR." The initial letter of each word is capitalized just once. People who haven't read any of our website and have instead gained all of their knowledge of Tor from news items are easy to discover since they spell it incorrectly. In fact, we can typically identify them by the fact that they haven't read any of our website.

## When my application delivers data, does Tor delete any personal information that may be present? 

No, it doesn't. You will need to make use of a different software that is familiar with both your application and the protocol that it uses, as well as how to "scrub" the data that it transmits. Tor Browser makes an effort to maintain consistency among all users with regard to application-level data such as the user-agent string. However, Tor Browser will not modify any of the content that you enter into any forms that it displays.

![image](https://user-images.githubusercontent.com/6468571/169419450-23e97fde-b619-4841-9d0e-e47475d915de.png)

![image](https://user-images.githubusercontent.com/6468571/169420299-b05fe9a3-4b36-4ea2-b601-0362a781a76f.png)

![image](https://user-images.githubusercontent.com/6468571/169418292-e9af8850-21dc-4c4f-abc8-a724fc6c15a0.png)


 * [Tor Manual](https://www.torproject.org/docs/tor-manual.html.en)
 * [Tor Control](https://www.thesprawl.org/research/tor-control-protocol/)
 * [HAProxy Manual](http://cbonte.github.io/haproxy-dconv/configuration-1.5.html)
 * [Polipo](http://www.pps.univ-paris-diderot.fr/~jch/software/polipo/)

![image](https://user-images.githubusercontent.com/6468571/169418370-07aa4c19-0e5a-40aa-a132-0f69db14f249.png)
