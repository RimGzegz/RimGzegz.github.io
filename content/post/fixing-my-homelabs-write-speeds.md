+++
date = '2026-08-15T21:35:12+02:00'
draft = false
title = "Fixing my smb share's write speeds being stuck at 100Mbps."
+++

So for few months I had issue that my write and read speeds on smb were capped at 100Mbps, I didn't bother with it as I was in my lazy phase for a while but today I fixed it.

I spent a while debugging, testing on both the truenas vm and on proxmox, doing drive tests, network tests and much more.

It turned out my router's 4th port is malfunctioning or is somehow capped at 100Mbps, now that I switched the cable to the 5th port I have a gigabit connection with my smb share.

Moral of the story, check ports, it might be that easy...
