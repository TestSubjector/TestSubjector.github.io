---
layout: post
title: "Whiskquilibrium The Game"
date: 2018-10-16
---
----------------
On 29th and 30th September, I had the chance to participate in the [Megathon Hackathon at IIIT Hyderabad](https://megathon.in/).
Hackathons I feel, are a bit of a strange thing. The novelty of cooking something up in a day or two versus the knowledge that most of what will be churned out in such events will be empty air in mere hours.

Still, it's a good thing to try out at least once, especially if you're in a coding slump.

With a team consisting of me, [Kushal Agarwal](https://github.com/legobridge), [Arnav Dhamija](https://github.com/shortstheory) and [Nischay Ram](https://github.com/Nischay-Pro) (appropriately called Team "CanWeGetBackToYouLater"), we devised and developed **Whiskquilibrium**. A 2D platformer game in the Godot game engine.

Here's the PR promoting synopsis - *It involves a cat named "Minto" trapped in a quantum world. She has the ability to shift her state between being alive and a ghostly dead form. Her presence itself changes the nature of the world around her. Can you solve the obstacles in her path that prevent her from escaping this mad world she is in?*

* Essentially, the game consisted of a cat character that has the power to switch colors between white and black and has to clear several levels.
* The blocks themselves in these levels are white, black or gray(level borders). The game mechanic is developed in the form of the cat being able to traverse through blocks of the same colour while being able to *paint* the blocks of the opposite colour, when *you stop touching that block*.
* The cat can jump in its default black colour
* The cat cannot jump when it switches to white(dead) state, but it gains the limited ability to fly which can be refilled by colouring up black blocks to white.
* The number of switches possible in a level is limited.
* The level can be reset at anytime (this is not a roguelike game *phew*)

Here are the sketches of the above mechanics, that we developed during the hackathon.

<img src="{{site.url}}/images/whiskquilibrium/tes1.gif" width="600" height="300" alt = "Colour/ Switch">
<img src="{{site.url}}/images/whiskquilibrium/tes2.gif" width="600" height="300" alt = "Fly">

The judging of the Game Dev section of the Hackathon was done by professionals from EA India (*insert jokes about DLCs here*).
Suffice to say, we did not win the 1st (given to a team that used RPG Maker to make more than 20 levels of content) or the 2nd prize (given to a team who make a game using their on OpenGL game engine, which they had been working on more than a few months, highlighting a major problem in my opinion, of hackathons).

Thankfully, we had a spot in the next 3 ranks (we were lazily not told the exact rank, since the **prizes** for these 3 spots were the same).
<img src="https://i.imgur.com/Jn5q0K1.jpg" width="400" height="300" alt = "The Prize">

I was actually very happy at the way the judges gave out their decisions to be honest. They had picked out people who had Ctrl C+V'ed almost all their code and assets from the net (essentially cheating). It was satisfying to watch them (those participants guilty of the aforementioned crime) being tongue-tied when the hard questions were asked.

This hackathon actually helped me fulfill one my college goals. Make a proper effort at a developing a game. Who knows? If we are able to actually find the willpower, maybe we'll polish this and release it on Steam.

Game development, in itself...is a pain. We had four people in our team and around 18 hours of time to understand Godot and make something. I can remember at least 5 instances, where at least one of us was on the verge of screaming, killing the other three and dancing on their corpses. The essence and the main difficulty with game development that I felt was that everything in games are linked. It's like how a real world problem behaves.
You want to change one move? Change everything that is dependent on that move!
You want to add visual indicators? Make sure that they -
* follow the camera
* are resized properly when the camera is zoomed in/out
* do not lag behind key presses
* look good
* and work as they are supposed too

Now when you are a novice (like we were), where and how to actually implement the above in a game engine is more than a bit of a pain.

To conclude, the most amazing was that at the end of it all we were more than happy at what we had been able to accomplish at the hackathon. We were sleep deprived of course, but seeing the game actually came to life brought that small-persistent-warm-giddy feeling to our hearts. We had implemented sound effects. Sound effects!

The reason I was felt a bit down though was because of a conclusion I had reached after the hackathon. That was while being an indie game developer will definitely be a fun and interesting career, you really need to be a bit of a masochist to be able to endure such a worklife.
