# ziVA
An iOS kernel exploit designated to work on all iOS devices &lt;= 10.3.1

# More general information
https://blog.zimperium.com/zimperium-zlabs-ios-security-advisories/

https://blog.zimperium.com/ziva-video-audio-ios-kernel-exploit/

# Offsets modifications for other iOS devices
Like a lot (if not most) of the iOS kernel exploits, this also requires offsets for each iOS device and version. 
Those will be posted in the close future (when I get more time) but should be acquired from AppleAVEDriver (you can get a hint on the offsets from the comments above them).

# Sandbox escape
Like mentioned, AppleAVEDriver direct access requires sandbox escape (either mediaserverd sandbox context or no sandbox at all).
Fortunately, Sandbox escape exploits have been released by P0, which means this can be used to completely compromise a kernel, and a step towards a full jailbreak.

# Is it a Jailbreak?
This is a crucial part in a Jailbreak chain, but this never aimed to become a Jailbreak.

# Is this going to be a jailbreak?
Maybe, if someone wants to work on that

# Credits
Credit for finding the vulnerabilities, chaining them together, writing the exploit go to Adam Donenfeld (@doadam).
Special thanks to Zuk Avraham (@ihackbanme), Yaniv Karta (@shokoluv) and the rest of the Zimperium team for the opportunity (and the paycheck).
