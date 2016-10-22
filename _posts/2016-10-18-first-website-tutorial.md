---
layout: special
title: Basic guide to get a domain, set up web hosting and upload your first website via FTP
tags:
- Courses
- Tutorials
---

<style>#banner {
	background-image: url(assets/images/firstwebpage-sky.jpeg);} </style>

**By Miguel Paz**. Photo by [Greg Rakozy](https://unsplash.com/@grakozy)

💡 *This is a simple tutorial I wrote for my students at CUNY Graduate School of Journalism. It is entry level and includes a couple class specific details.**

## Choosing a domain

A domain is the name of your website and it’s made of 2 things: 

A name: *what-ever-you-want-to-name-your-website. *

A top level domain: .com, .org, .net, etc.

For example a domain that I own is miguelpaz.info. The New York Times is nytimes.com. CUNY’s is cuny.edu. There are also subdomains. CUNY’s Journalism School website is one: journalism.cuny.edu.  


There are many types of domains, starting with the [original top level domains](https://en.wikipedia.org/wiki/List_of_Internet_top-level_domains#Original_top-level_domains) (including .com, .org, .net, .edu), [country top level domains](http://country_code_top) (like .us, .fr, .ca, .cl, .ar, .co, .tv, .io, .in, etc.), second level domains (.co.uk, .com.ar, etc.) and other types of domains. There is a [new list of domain names](https://en.wikipedia.org/wiki/List_of_Internet_top-level_domains#ICANN-era_generic_top-level_domains) you can also check (examples: .nyc, .miami, .bike). In most cases, this ones are sold by [specific domain name registrars](https://en.wikipedia.org/wiki/List_of_Internet_top-level_domains#ICANN-era_generic_top-level_domains). A [full list of domains](https://www.iana.org/domains/root/db) is maintained by the Internet Assigned Numbers Authority.

[Domain names](https://en.wikipedia.org/wiki/Domain_name) can be bought (we talk about buying domains but you actually rent them) for one year and renewed annually from [Domain Name Registrars](https://en.wikipedia.org/wiki/Domain_name_registrar). You can also choose to buy your domain for more years. You can buy a domain and pay for web hosting from a single provider or get the web hosting elsewhere. Due to the specificity of each service, it’s more usual to get the domain and hosting separately.


Once you register a domain name, you will get one or more Domain Name Servers (DNS). DNS "[are the Internet's equivalent of a phone book](http://www.networksolutions.com/support/what-is-a-domain-name-server-dns-and-how-does-it-work/). They maintain a directory of domain names and translate them to Internet Protocol (IP) addresses". This may look like host1.domainnameregistrar.com which is the text on top of the underlying [IP address](https://en.wikipedia.org/wiki/IP_address).  

Depending on popularity and availability, prices of domains vary. A .com domain can cost $10 dollars per year, while a .io (very popular in *startupland* lately) will cost $50. Prices may vary also between domain name registrars, if they are on sale, etc. 

Things to look for when you buy a domain name from a domain registrar: 

-FTP access
-Includes cPanel (a dashboard to manage your domain and DNS)
-Full control of your DNS
-Includes a [SSL](https://en.wikipedia.org/wiki/Transport_Layer_Security) certificate free for one or more years (so your website uses [HTTPS](https://en.wikipedia.org/wiki/HTTPS) protocol by default). If it doesn’t and the price of the domain is very cheap, you can get it and then go get a free certificate with [Lets Encrypt](https://letsencrypt.org/getting-started/).
-Does not charge you extra if you want to transfer your domain name to another registrar. 
-Provides Domain forwarding

## Buy a domain and web hosting

You can purchase domains on many sites,  including [Midphase](https://www.midphase.com/website-hosting/), where we are buying domains and hosting for our class (please see disclosure below). 

Midphase right now has a ["Personal web hosting"](https://www.midphase.com/website-hosting/#) offer that includes: A free domain and web hosting for 1 website and 1 subdomain. The 1 year web hosting plan costs $ 42.84. A 3 month plan is $ 10.71. 

There are many other sites to buy domains like [Gandi](https://www.gandi.net), [Namecheap](https://www.namecheap.com), [I want my name](https://iwantmyname.com), etc.  I specially recommend [Gandi.net](https://www.gandi.net/) because of its proven track record of taking special care of security, and it’s supports of a variety of open source projects.

Most will offer discounts and cheap prices when you buy a domain for the first time but when you renew it, the price will be higher. If you can afford it buy it for more than one year right away.

Since you want to build your portfolio and online presence, first try to get your own name as a domain but if you can’t, be creative and come up with something you know you will use for quite some time and it is memorable. First site has [11 great tips for choosing a domain name.](http://firstsiteguide.com/choose-domain/)

## Step by step to getting a domain and hosting with Midphase*

1. Go to [Midphase](https://www.midphase.com/website-hosting/) and [purchase domain](https://www.midphase.com/knowledgebase/display/MID/How+To+Register+A+Domain) and hosting (I recommend the cheapest plan). Do this as soon as you can. Domain names and hosting can take up to 48 hours to start working properly. 

![image alt text](assets/images/image_0.png)

2. If you don’t have a domain yet, use this search box to add the name you want and look for options and prices. For example I searched for possible domains for my name.

![image alt text](assets/images/image_1.png)

3. I got this options. 

![image alt text](assets/images/image_2.png)

4. I bought the cheapest one for this tutorial: miguelpaz.site

![image alt text](assets/images/image_3.png) 

5. Then add your information and pay for it.

![image alt text](assets/images/image_4.png)

6. Confirm the order and set your password.

![image alt text](assets/images/image_5.png)

![image alt text](assets/images/image_6.png)

7. You will see a [Dashboard and a Icon Drive for Share Hosting](https://www.midphase.com/knowledgebase/display/MID/How+To+Access+cPanel+Through+The+Shared+Hosting+Tab). Click on that to see the basic information of whatever domain you bought. 

![image alt text](assets/images/image_7.png)

8. Only if you want to or feel the need to read again about FTP, go to the left icon for Shared Hosting and follow the tutorial that explains very well how to connect via FTP. This is your cPanel (dashboard to manage your website). You will also get an email from Midphase with information for you to remember. Save it.

![image alt text](assets/images/image_8.png)

9. Now, **important**, to access your domain and hosting and get your FTP credentials **you must** log into your Control Panel or CPanel at [https://chi.midphase.com/home](https://chi.midphase.com/home) with your username and password. Once you are in, click on the left drive icon of Shared Hosting, look for your domain name and click on it. You will see your credentials to use in your FTP:  
Host: miguelpaz.site
Username: miguelpa
Password: the one you created when you created your account in MidPhase. In here you can create a new specific password for your FTP (recommended).

![image alt text](assets/images/image_9.png)

You are done with that 👍🏼🍾. 

10. Now you will download an FTP client to use it to upload your website to your hosting server. 

FTP stands for [“File Transfer Protocol”](https://en.wikipedia.org/wiki/File_Transfer_Protocol) and it is used to connect between your computer 💻 (client) and the server 🖥 of your web hosting. 

In order to do that you need to install in your computer an FTP client. This is basically a software that allows you to upload your webpage folder and it’s contents from your computer to your web hosting so it can be displayed in your web page under your domain name. It can also be used to download stuff from your web hosting. 

Think of FTP clients as the grandparents of Dropbox or Google Drive, and of FTP as the protocol that helps your machine talk to another machine (since 1971 by the way) to get your stuff into the web. 

11. We're going to use FileZilla FTP client, since it's free, open source and offers a straight forward (ugly) but useful interface.  

12. Download [FileZilla](https://filezilla-project.org/). If you have issues, try [downloading it here](https://sourceforge.net/projects/filezilla/?source=typ_redirect). FYI: if you don’t like it there are other programs that will work just as well such as Cyberduck. 

13. Open FileZilla. On the top side you will see 4 boxes: Host, Username, Password, Port where you must write your web hosting credentials and the click on the Quickconnect button, to connect to your web hosting and upload files.

![image alt text](assets/images/image_11.png)  

-In the "Host" field, add your domain name.   
Ex. Host: miguelpaz.site
-In the "Username" field, enter your cPanel or FTP username.  
Ex. Username: miguelpa
-In the "Password" field, enter your MidPhase cPanel password.  
-Leave port set blank or at "21”.
-Click "Quick Connect".

>>Tip: If your hosting says login failed due to password issues, you should create a new password that is stronger.

![image alt text](assets/images/image_10.png)

14. Not sure about how FileZilla looks and organizes stuff? The **left** side of FileZilla shows the files stored on your Computer. The **right** side shows the file on your server, where you will see a set of folders and files. The **onlye important folder** for you in the server side now is the one called **"public_html"**. This folder is where you will upload your files from the **left** side (stored in your computer) to the **right** side (your web hosting server). All you need to do is find the files you want to upload on the left side of the screen, click once on them and then drag them to the right side of the screen. This will upload the files to your website. 

15. **Never** erase your "public_html" folder. If you don’t know what other folders or files are for at your server, **DO NOT** delete, rename or move them.

Still confused? Here is a [video tutorial](https://www.youtube.com/watch?v=O3DudpEMPiY), a list of [crazy awkward domain names](http://www.boredpanda.com/worst-domain-names/) and some of the [longest domains ever](http://archive.oreilly.com/pub/post/the_worlds_longest_domain_name.html)

That’s it! Now go celebrate you have your first website online.🎉


**_Disclaimer:_** None of the professors or coaches are connected in any way with any of the companies mentioned. We have chosen Midphase as a web hosting provider due to it’s low price, ok service, and because it is easier to pick one provider to explain the entire class how to setup your website. We'll all have a common dashboard which makes it easier for everyone. You can choose other providers. Feel free to ask me about other options.*