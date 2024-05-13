# Solution for challenge Thinking about the past

![challenge question](<Thinking about the Past - OSINT.jpg>)

Description : 
- Category : OSINT
- Points : 200

The challenge included a image of a github profile.

![github profile](MyProfile.png)

From the given username ```0p7imis7ic``` we can go search for the user in github.

This is the profile that we search for : 
![profile](image.png)
but we can see that there is not repository available or anything but there is a suspicious string ```aSBtaXNzIG15IG9sZCBzZWxmLCBjcmllcyBpbiBKYXZhIDoo``` there. By throwing it into cyberchef, we get this ```i miss my old self, cries in Java :(```

![cyberchef](image-1.png)

If you compare the latest version of the profile with the image in the challenge, we can realise that in the image of challenge there are 2 repo available in the repository tab. By using a wayback machine, we can find the [old version](https://web.archive.org/web/20240505113349/https://github.com/0p7imis7ic) of profile.

![wayback machine](image-2.png)

We can see that there is a [linkedin](https://www.linkedin.com/in/kamal-bartolo-b00196308/) account. After browsing through his about, we can saw a random string ```SUNURjI0e1IzZmwzdDFuZ183b18wbGRfNzFtZVNzU3N9``` at the end and try decoding it will show the flag.

![cyberchef](image-3.png)

```ICTF24{R3fl3t1ng_7o_0ld_71meSsSs}```