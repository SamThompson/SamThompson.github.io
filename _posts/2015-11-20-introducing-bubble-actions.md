---
layout:     post
title:      Introducing BubbleActions
date:       2015-11-22 14:00:00
author:     Sam Thompson
summary:    An open source Android UI library implementing the long press actions in the Pinterest app.
categories: Android
thumbnail:  android
tags:
 - Android
 - Pinterest
 - Android libraries
 - Open source
---
One of my favorite parts of the Pinterest Android app is what happens when you long press an image:
<img src="/assets/bubble-actions-1.png" alt="BubbleActions screenshot 1" style="width: 300px;"/>

All of the contextual actions that we can perform on the image are hidden until we long press and leave our finger pressed to the
screen. A "bubble" appears for each action with a circular indicator appearing over the item we're acting on. In order to 
perform a particular action, we move your finger over to a "bubble" and lift
our finger. It's a delightfully clean UI touch that makes the staggered grid of images less cluttered
than if the actions were directly on the card of the pin.

I was really inspired by this design, so I decided to create my own open-source implementation: 
BubbleActions. It differs in a few tiny ways from the
Pinterest version, but it's fairly close:
<img src="/assets/bubble-actions-2.png" alt="BubbleActions screenshot 1" style="width: 300px;"/>

BubbleActions supports adding up to 5 fully customizable actions. You can find the code and documentation 
for BubbleActions on [Github](https://github.com/SamThompson/BubbleActions). Contributions
and feedback are always welcome.

