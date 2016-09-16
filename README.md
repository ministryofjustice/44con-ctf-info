
##This doc
This doc will be updated during the conf as needed so keep an eye for it. Twitter for MOJ Digital: [@Justice_Digital](https://twitter.com/Justice_Digital)

##Background
Prison break! Type of challenges: Web

A series of web apps to break into prison and release yo' boy. (Not controversial at all).

blog post: https://44con.com/2016/08/31/ctf/

##Registration

###Update: We are closing official registration Friday 12:00
###Update: Winners have already been identified and will be announced at 16:00
###~~Infra will remain up until the evening (possibly 7-8pm) for people who just want to take a look or have a go~~
###Actually the conference closes at 16:00, so the infra will shut down at 16:00 as well

We have decided to use IRC so that we can copy paste some of the credentials because they are too long!

Registration via IRC (SSL) on irc.ctf.pwnz.org 6697 on channel `#CTF`

If you have no IRC client you could install irssi (OSX: brew install irssi) just note not all irc clients support SSL so get one that supports it.

To connect via irssi: `/server -ssl irc.ctf.pwnz.org`

If you need a human, come to the Ministry of Justice booth in the main hall of 44con.


##Format/Accessing the hosts
The hosts of the ctf will end in the domain `xip.io`. If you are having trouble resolving them just try again.
If you discover other domains that are Ministry of Justice branded, please not these are not in scope!

Without spoiling too much, the design is as such:
* Each team will get an entry point with **https** (the certificates are self signed and may produce errors, ignore that, it's not in scope but if you are wondering/suspecting someone might be messing with you let us know what the CN is of the cert)
* Entrypoint hostname will be like `<random string>.ip.ad.dr.ess.xip.io`
* HTTP basic auth password with username: dab  password: what you have been given as basic key. Sometimes this might pop up in the web apps, and break the flow, but it exists so other teams don't interfere with each other.
* These credentials / hosts should not be shared outside of your team

##Flag submission
Submit the flags by sending a PM to ohmygauss. We will be recording the timestamps and award points accordingly.

##Hints
Some hints might be provided in IRC depending how people get on with it. For troubleshooting or problems please talk to us directly or in pm.

##Rules
* Don't attack the hosts themselves or the infra, just the web apps.
* Be respectful to each other
* Have fun!

##Prizes
* A PiDrone (raspberry pi drone self assembly kit) 
* Clarification: To win a prize you need to be at the conference


##Acknowledgements
Thanks to everyone who participated this year! Also thanks to afraid.org for providing such a cool hostname (irc.ctf.pwnz.org) check them out at http://freedns.afraid.org/ it is a free service.
