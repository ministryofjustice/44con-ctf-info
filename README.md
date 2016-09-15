
##This doc
This doc will be updated during the conf as needed so keep an eye for it. Twitter for MOJ Digital: https://twitter.com/Justice_Digital



##Background
Prison break!

##Registration

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

##Hints
Some hints might be provided in IRC depending how people get on with it. For troubleshooting or problems please talk to us directly or in pm.

##Rules
* Don't attack the hosts themselves or the infra, just the web apps.
* Be respectful to each other
* Have fun!


