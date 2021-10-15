# Burp_Suite_Notes
Notes taken on the following Burp Suite rooms on TryHackMe: https://tryhackme.com/room/burpsuitebasics https://tryhackme.com/room/burpsuiterepeater

## Burp Suite: The Basics

### What is Burp Suite?
- Burp is the industry standard tool for assesing the security of web apps, and is also used to assess mobile applications
- Burp can manipulate traffic between an attacker and a webserver
- Requests can be captured and sent to different parts of the Burp Suite framework
- Burp has three editions; Community (free), Professional, and Enterprise

### Features of Burp Community
- Proxy: Allows the user to intercept web requests/responses and manipulate them
- Repeater: Allows the user to modify and resend the same request multiple times (useful for SQLi)
- Decoder: Used for decoding captured information and encoding payloads before sending them to a target
- Comparer: Compares two pieces of data at word or byte level
- Sequencer: Used to asses randomness of tokens such as cookie values 

### The Dashboard
- Tasks menu is used to define background tasks for Burp to run while using the application
- Event log shows what Burp is doing, and also shows information about connections being made through Burp
- Issue Activity (Pro only) lists all vulnerabilities found by the automated scanner
- Advisory gives more information about vulnerabilities found, and gives suggested remediations
