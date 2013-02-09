---
layout: post
title: "Solar Sails"
---


##Preface

Hello! Being my first article, I have greatly underestimated the detail and work that would go into the writing of this article. It has taken a great deal longer to write and research and is much longer than intended. I will thus be publishing them in parts, likely three or so, over the next few weeks. Hopefully I'll get better at planing these things as I go! So with out further ado:

##Abstract

Solar sails are an exciting, old technology that have been researched and developed since [the 70's.](http://science.nasa.gov/science-news/science-at-nasa/2008/31jul_solarsails/) The effects of solar radiation on spacecraft are well known and are taken into account in spaceship and satellite design. Many craft have used solar radiation to [conserve propellant and correct trajectories.](http://messenger.jhuapl.edu/news_room/details.php?id=102)
Even though utilizing solar radiation has been around for a while, it's use as the primary propellant has only just begun to see the light of day with experimental missions [IKAROS](http://en.wikipedia.org/wiki/IKAROS)
and [NanoSail-D.](http://en.wikipedia.org/wiki/NanoSail-D2) Because solar and light sails use the sun as to provide a force on the sail, they are very cost effective to propel and because there will be always be an acceleration (within reasonable distances of the sun), they can achieve high and even near relativistic velocities over periods of time. This makes them plausible solutions to interstellar travel and, perhaps, interplanetary.In this article we'll look at the physical principles at play behind this technology and look at some test cases of our own creations.


#Part 1:Theory and Propulsion

##The Momentum of Light

Classical theory tells that the momentum of an object is the product of its mass and its velocity, $\vec{p} = m\vec{v}$ . When then we consider the momentum of light which has no mass, we find light can never have momentum and any solar sale we set out to launch will be fated to fall straight into the sun. Thankfully Einstein (et al.) tells us that objects at relativistic speeds behave differently. From relativity, the energy of an object at rest is proportional to its mass by the square of the speed of light. But for an object in motion, the energy is found also to rely on the momentum as well thus leading to the complete equation of special relativity:

$$ E^{2} = (mc^{2})^{2} + (pc)^{2} $$


Where E is the total energy, m is the mass, p in the momentum, and c is the speed of light.
When we consider a photon (light) which has no mass, we arrive at:

$$ E = pc $$


Rearranging and keeping in mind that momentum is a vector gives an expression describing the momentum of a photon:

$$ \vec{p} = \frac{E}{c}\vec{r} $$

Which gives rise to the great possibility of propelling a spacecraft with light!


##Organizing

Now that the fundamental ideas have been established, we'll rearrange some things to get some more applicable equations. First up, we realize that when we discuss interplanetary travel, we almost exclusively focus on kinematics. Well all we have right now is an equation of momentum. So perhaps we ought to start there. If we recall that:

$$ \vec{F} = \frac{d\vec{p}}{dt}$$
and
$$ P = \frac{dE}{dt}$$

Thereby:

$$ \vec{F} = \frac{d}{dt} \left[ \frac{E}{c}\vec{r} \right] = \frac{P}{c} d \vec{r}$$

We see here that the force relies on the change in direction of the light beam. We can simplify the possible values of the direction to just two solutions using some quick conservation analysis, after all, this is just a momentum problem.

###Absorption
We find that when the photon is absorbed by the sail, the momentum gained by the sail is the same as the momentum of the photon.
![Absorption](/images/absorption.png)

###Reflection
When the photon is reflected, the momentum gained by the sail, by conservation principles, must be twice that of the photon's initial momentum.
![Reflection](/images/absorption.png)

Of-course, we'll have only the best material at hand when we create our sail, so to create the most efficient sail (in terms of propulsion), we'll use a completely reflective surface and assume dr = 2. Under real conditions, though, we could not achieve a perfectly reflective surface, or perhaps we wouldn't want to. We might even consider using material that can change its reflective properties so that we could control tho amount of momentum being transferred. Now we have a nice equation that can be used to describe the motion of our sail, but it can't really be used to relate anything about sail to it's performance. In other words, this equation isn't very 'engineer-friendly'. You've probably already figured out that the area of the sail is going to be the most concerning factor of the design, so we'll have to incorporate two spatial dimensions in some way. Well, if we recognize that force per area is just pressure, we can transform the equation from one of force to one of pressure. To keep the units inline, we'll also need to divide the left by an area. We'll find then that power per area is just intensity. This leaves us with:

$$ p(I) = 2\frac{I}{c} $$


That's as far as we'll go for now, but stay tuned. Later we'll take a look at the distacne dependency of intensity by the inverse square law and derive some models for the motion of our sail.

If you have any questions or comments or would like to point out a typo, mistake, or poor explanation, please email me at dan@dankolbman.com.

