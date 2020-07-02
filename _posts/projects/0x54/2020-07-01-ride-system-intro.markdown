---
layout: post
title: The Project 0x54 Ride System
date: 2020-07-01 21:46:00 -0400
description: An Introduction to the 0x54 Ride System # Add post description (optional)
img: 0x54/generic-header.png # Add image post (optional)
tags: [Project 0x54, Introduction]
---

# What can it do?
<iframe width="560" height="315" src="https://www.youtube.com/embed/HWuHxVhyFRU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
What you just watched was a quick, afternoon length animation I put together using the ride vehicle's animation rig. I created it as an attempt to showcase what that ride vehicle could do, showcasing some of the features and sensations that it can convey in a somewhat realistic scene program.

# Alright, what can it *really* do
Here's some somewhat vague technical information:
* Bus-Bar/Pinch Rail transport base w/ variable speed
* Heave
* Pitch
* Strafe
* Yaw (Limited, unlike most other ride systems. This is sacrificed in favor of...)
* Infinite, Controlled, Off-Axis Roll

As you can see, my goal with this system was to provide a new, unique experience through the off-axis roll. Other ride systems, especially dark ride systems, roll around the base of the ride vehicle, at the guest's feet. This provides a satisfying enough sensation for the rides it's currently installed on, but it's a bit limited in its use.

As an example, take the motion of a bobsled/flying turns coaster. In such an attraction, guests bank sharply around turns at high speeds, rolling around an axis not centered around the guest's feet, but closer to or above the heartline.

That sensation, that of ducking quickly around corners at high speed, isn't particularly achievable with a foot-centric roll axis. 

I'm beginning to ramble here, but I'm going to assume I've made my point on the utility of infinite controlled off-axis roll.

I mentioned the limited yaw as a sacrifice. I'm sure given unlimited time and money, it's wholly likely that some over-engineered machine could provide the motion I want with the benefit of infinite yaw, as well as infinite roll. Maybe stick the main motion base on a heavy-duty turntable with a complicated slip ring.

Sacrifices like this help with the creative process, is my reasoning. Given some constraints, wonderful work can be done. After all, every major dark ride since The Haunted Mansion has had the ability to spin on the spot forever. What considerations would have to be made for a system that couldn't?

I'm not a mechanical engineer. I'm not going to spend a lot of effort determining what is and what isn't possible and for how much. 

Moving on from that, let's explain how my concept works mechanically.

# Wholly Unqualified Speculative Mechanics (WhUSpeM)
Here's the current model.
|Left | Top | Front |
| :-: | :-: | :-:|
| ![]({{site.baseurl}}/assets/img/0x54/ortho-side.png) | ![]({{site.baseurl}}/assets/img/0x54/ortho-top.png) | ![]({{site.baseurl}}/assets/img/0x54/ortho-front.png) |

Central to the ride system is the barrel o' monkeys (guests). Mounted to a floor spanning a chord of the barrel, 4x4 guests sit with to-be-determined restraints (Realistically, over the shoulder. Desired? Lap bars of some form). 

The barrel itself, structurally is only the chord-floor and a leading and trailing ring. Each of these rings are embedded into a leading and trailing "slip," which are affixed to each other through some structural supports. The slips contain slip-rings to transfer power and audio (hence the name) and some mechanical magic to make it spin properly. 

The slips are each mounted at one point at their bottom to two actuators, which can heave the slip up and down independent of each other, providing a pitch effect. The actuators are mounted upon "slides" at the bottom, which each slide back and forth laterally in a trough. 

...

So it's not particularly mechanically strict. Nor realistic.

But it's a somewhat fantastical ride system entirely for personal practice. 

I can't give up all my good ideas for free. 

(excuses)


# What's next for the ride system?

## Technical:
* Kinematic Analysis
* Multiple Ride Vehicle management
* Export Script
* Non-inverting variant

## Story / Art:
* Various concept art passes for the ride vehicle
* Create improved/production 3D model


Thanks for reading :)