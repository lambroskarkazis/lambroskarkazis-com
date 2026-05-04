---
title: 'My Current Desktop Setup (Circa 2026)'
description: 'Speeding Up Gaming and Software Engineering Cost-Effectively With Used Hardware'
pubDate: 'May 4 2026'
---

Earlier this year, I picked up an old desktop computer from a buddy who was moving. I had only had a laptop, and the desktop was a nice upgrade for a few reasons. 

Initially, this desktop came with an AMD RX 550 graphics card, which I updated to a used NVIDIA RTX 3070Ti I brought off of Craigslist.

## Always On

I was in a machine learning class for graduate school this semester. It involved running many computationally-heavy experiments. Before the desktop, I had to tweak my laptop's sleep settings in order to not stop running whatever code I currently needed to run.

This is also potentially useful for self-hosting or other applications, though I have not made use of this too much yet.

## CUDA Support

I'd read alot about how (especially in the not-so-distant past) AMD had much better Linux driver support than Nvidia. Since I had expected to use Linux, I did not want to deal with a bunch of compatiblity headaches.

However, I read that Linux support for Nvidia had improved over the years (e.g. Wayland now working). I knew that CUDA was alot better supported than ROCM. I was not sure how much I would use the desktop as a normal desktop environment vs running ML class experiments vs as a gaming rig, so it was hard to decide between AMDs better support and NVIDIA's better performance.

Ultimately, I am really happy I ended up grabbing an NVIDIA card. CUDA support worked really well, and it made Machine Learning class way faster and less painless the day I got it setup.

For the problems we were doing in class, the 3070Ti would take a few seconds on pytorch models which normally took 10-100 times longer on the cpu. This allowed me to try out various hyperparameters and ranges in a more experimental way. It also allowed for changes to be more quickly reflected in my final charts. The first report would have a number of times where between the laptop cpu and worse results caching, I would possibly need to re-run experiments for a few minutes (up to about 20), during which time my laptop had all of it's fans spinning, was heating up, and I would worry that it could turn off if I was not paying attention / configuring the sleep settings properly.

I arguably could have or should have leaned on renting cloud GPUs sooner in the class. However, it just feels alot better when you are not paying money for your homework to run. And the 3070Ti performs really admirably for most of what I would throw at it. I now have a free platform I can test drive and scale up to larger rented GPUs if I have to and I know the code is already working.

## (Hypothetically) Better Gaming Performance

We have a 4k 144hz monitor in the office. With the 3070Ti, I could hypothetically get good resolution and refresh rate on older games (which I what I mostly play).

Ultimately, school ended up being really busy, and I did not have time for a ton of PC gaming. However, it is nice to have that option. I used to have a Lenovo Legion Y545 gaming laptop, and even that got great 1080p performance for Doom, Doom Eternal, Skyrim, Slay the Spire, and other games I would play at that time.

I think it would be fun to experience titles which did not perform well on that machine (like Metro Exodus Enhanced Edition which would not even run since it was not an RT laptop) on the desktop.

## Different Machine

Just having different machines is a huge plus. For one thing, I can have different settings than my laptop. I can run my laptop with an energy efficient profile for better battery life, but allow my desktop to draw as much power as it wants (I actually do limit the 3070Ti to 200W to try and meter that a little, but that has not caused serious throttling for my workloads so far from what I can tell). I can have normal sleep settings on the laptop so it doesn't start my backpack on fire walking home, but allow the desktop to be always on. While I work on writing my machine learning report or sketching out the next part of the code on my laptop, the desktop can run computationally intensive experiments.

I needed to install Windows on my laptop in order to comply with proctoring software, but I can experiment with different linux distributions on the desktop.

Finally, in terms of PC gaming, I can leave Steam off of my laptop (so I am better able to focus on school), while having it on the desktop if I am home and have some free time.