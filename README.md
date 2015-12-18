# KodiDragonboard410c

Few years back, while I was doing periodical PC reorganization, I've realized that I have a problem with multimedia organization. I've used one program for music playing and playlist keeping, few others for video, default software for my TV card. Anyone except myself would get highly confused...
“And then came XBMC...”
Although, still in development, it offered a lot of options and worked stable for the things that I needed. Soon, one of my old PC's became XBMC dedicated.
Being a tech addict with the “built in” need to tweak gadgets, I was delighted when my management gave me a space to play with DragonBoard 410c and my favorite media center. 
When started, we focused on Ubintu image by Linaro. Kodi was not installable via apt-get, so the how-to for Ubuntu covers installing Kodi (Jarvis alpha and beta) from source.
Since Linaro choose Debian as an official linux distribution, how-to was expanded to Debian as well. Main difference between Ubuntu and Debian, from the Kodi point of view, is that Kodi was backported on Debian Jessie and it is available through apt-get.
Building from source is done on the Dragonboard itself, because cross compiling is still WIP. Patches used on Ubutnu and Debian are currently different, since the Debian patches are based on existing patches for creating Kodi Isengard deb package.

Enjoy. :)
