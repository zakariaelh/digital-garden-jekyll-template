---
layout: page
title: Stuff I built.
permalink: /build
---

Below is a list of my side projects. Most of them are no longer accessible but the code is available on my github. 

I have a place in my heart for each project. If any sounds interesting to you, and want to contribute, please reach out. I'd gladly support. 

- Explain AI [website](https://xplnai.com)

The first AI Dictionary! Highlight any text to get contextual explanations. 

Want to give it a try? In the text below, highlight FLOP and click on the small tooltip. 

- Modern AI models require billions of FLOPs to process a single input, showcasing their computational intensity.

- After the new product launch, the marketing team was disappointed to see their campaign flops, resulting in lower-than-expected sales.

Magical, hein? 

If you own a website and want to add Explain AI for your visitors, get in touch with me. Otherwise, you can add it to your browser and use it across all websites.

This is by far my favorite project, and also the most useful AI tool I use, after ChatGPT and Cursor. Started as a fun project with Varun and Pedro, and fell in love with it and dedicated the next year building it. 

It's also the first project I made $1 on the internet with. 

- Golden DJ [code](https://github.com/zakariaelh/goldendj)

Golden DJ is an AI agent you can call over the phone to chat. It can also take song requests and play them over telephony. 

Project started at an AI hackathon (which we won). This was Omar and I's attempt at bringing Voice AI Agents to people without smart phones. 

While the MVP took a few hours to build, cleaning it up took a few days. 

- smplr [code](https://github.com/zakariaelh/smplr)

End-to-end platform for generating voice clone samples.

Another project I built during my Voice AI rabbit hole. As I was making a lot of voice clones for fun, I found myself spending a lot of time creating voice samples (a sample of the voice you want to clone). Creating a sample is essentially a 3-step process:
1. Find a recording of the voice you are trying to clone (often a Youtube video)
2. Remove the background noise (aka vocal extraction)
3. Extract only the parts where your characters speaks

Doing this was pretty tedious. So I built an algorithm that does all of this in the backend. All you need is the url of the video. 

Spent a lot of time trying to make this really fast, which was fun! My goal was to process a 30-min video in under 1 minute (including Downloading). Learnt a bunch about container parallelization along the way. Wanted to go low-level and optimize the models for inference, but novelty got in the way. 

I was suprised by how much it got used. I got a bill of $100 from Modal within the first 48 hours, but then usage slowed down but never went to 0. Every now and then, someone would reach out when when it stops working, and I'd happily fix it (one person offered me $20 once). A couple of people asked me to make it more reliable and put it behind a paywall. 

SMPLR is now down. Youtube started blocking all video downloads. Though I patched it upon request, the patch didn't stick for long.

- zakslist

Craigslist has the best apartment deals in SF (by far). It's also really hard to find good apartments there. 

I built zakslist for my own personal use. When looking for an apartment, I cared about four criteria: 
1. Overall price (own budget)
2. Price per sqft (Is it a good deal relative to the area?)
3. Distance from my favorite park (walking, biking, driving)
4. Distance from office (walking, biking, driving)

And most importantly, when one becomes available, I want to find out early. 

So I built an engine that finds the newly listed apartments every day, calculates their attractiveness score (based on the above criteria), and sends me the top 10 best apartments to my email. 

And that's how I found my place in the best neighborhood in SF.

I have tried many times to productionize it but never pushed it to the finish line.

- songbee

When C taught Yoga, she'd take song requests from her students over text. It used to get quite messy. 

So I built a simple form where the student put their name, and their song request (with autocomplete from Spotify API).

The song request would then go to her Spotify playlist directly. 

Didn't get much use. 

