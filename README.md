# Welcome!

I have created two web based CTF challenges for your entertainment. If you are unfamiliar with what a CTF is in a security context then here is a quick overview from [ctfd.io](https://ctfd.io/whats-a-ctf/):
> Jeopardy CTFs are the most common kind of CTF.
They revolve around a set of challenges which are provided by competition organizers to competitors.
Competitors form teams and then work on the challenges together.
Each challenge is designed so that when the competitor solves it, a small piece of text or "flag" is revealed. The flag is then submitted to a website or scoring engine in exchange for points. The amount of points rewarded is typically relative to the perceived difficulty of the challenge.
Competitors usually receive about 72 hours (typically the course of a weekend) to solve as many challenges as possible.

The general approach for CTF challenges is to first understand the system you are given, in this case it is a web application. Go through and discover its functionality, what technologies it uses and what other systems it interacts with. A simple way to start doing this is by opening up the network tab in your browser, take note of the the requests the application makes. What parameters does it send, what headers are in the responses? Once you have that understanding, then you must think like an attacker! How can you break away from the intended use cases set before you in the application? Look up the technologies used, what vulnerablities exist for them? Or what functionality exists that could be used maliciously? Think outside the box! 

The technologies used in the challenges are not anything fancy, it's all likely things that you've used or seen in your careers, so don't overthink it too much!

Here are a few resources to get you started around tools and tricks you can use when solving CTF challenges:
- https://book.hacktricks.xyz/welcome/readme - A lot of great tricks for all types of CTF challenges
- https://portswigger.net/web-security - Covers just about every major web vulnerability, and has free labs to go with it.
- https://portswigger.net/burp/communitydownload - HTTP Intercepting Proxy. Extremely useful in web challenges allowing you to edit and replay HTTP requests as well as view all the requests being made by your browser.
- https://gchq.github.io/CyberChef/ - A swiss army knife of tools for various things like encoding, hashing and data analysis. Very useful in day to day life outside of CTFs.


Each challenge has two flags for you to find. The flags will be in the format `flag{flag_text_here}` so you'll know when you find it.

Please reach out to me if you want any hints, help or just want to know how the challenge works and see the code. I want this to be an enjoyable experience, and leave you feeling like you learned something along the way! Also if anything breaks just let me know. 

So without further ado, here are the challenges:

## Tetris Temple
Love tetris? So do I! I found this website that allows you to play in your browser, and customize the block colors! I wonder how they are doing that? Well anyways, here it is: http://tetris.doshmajhan.com. Have fun playing!

## Security Theatre
My favorite kind of theatre. I hear they have some fantastic screenings at the moment. Make sure to go the ticket booth to get your ticket first: http://ticketbooth.doshmajhan.com but mind the auth... Enjoy the shows!
