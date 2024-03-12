---
layout: post
author: brady
---

### Using torch, built from scratch a small character based decoder only language model. Trained on text from Harry Potter.

As part of diving deeper into DL, I built and trained a small language model from scratch (trained on 1 nvidia A30 for just under 1 hour). The purpose of the model is to generate infinite "Harry Potter-like" text and is only trained on the text from the 7 harry potter novels (not very much text all things considering). The character level model struggles and the byte pair encoded model does slightly better. Still a long ways to go to actually generate a cohesive story but I think it gets close to "sounding" like Harry Potter. Off to build some actually relevant models now...
In case you are curious of what the model and outputs look like:

<img src="{{site.baseurl}}/assets/images/HP/DALLE_img.png" alt="HP DALLE Photo" style="width: 25%;">

