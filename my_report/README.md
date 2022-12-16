<<<<<<< HEAD
# Lesson: Digital & Serious Games

### First and Last Name: Paraskevi Evelina Kallergi
### University Registration Number: dpsd18139
### GitHub Personal Profile: https://github.com/dpsd18139
### Digital & Serious Games Personal Repository: https://dpsd18139.github.io/Role-Playing-Game/

# Introduction

TBA

# Summary

It's a test summary

TBA

# 1st Deliverable

I wrote a story draft about this game's plot. 
Then I made some concept art of my two characters. The main character, who is controlled by the player was designed in a way to appear androgynous/gender ambiguous. This way both genders will be able to put themselves in the characters shoes, without men having their fragile masculinity threatened. The other character is a mysterious young girl, at first glace appearing devoid of human emotion and common video game logic. As the game progresses we will learn more and more about this game through this character.

Then I used this character generator to create our character sprite models in a way that would correspond to the concept art I made earlier.
My initial plan was to make my own 2D pixel art sprites and animation, but I couldn't do it in time for this deliverable. I intend to do so for the next one.
https://picrew.me/image_maker/36838

After that I used a tile map I found on itch.io to create this map. My original goal was to find one that looks like a small night city but couldn't find find one that matched my vision so I used this one as a placeholder for the deliverable.

The graveyard is a crucial part of the story, so I intend to keep it.

I added a simple coloured semi transparent rectangle sprite as a filter to simulate a soft evening feel.

Lastly, I used a nostalgia inducing piano song I found on YouTube as backround music. Again, I originally intended to create my own music for this project, but again, I indend to do it for the next one!

I also intend to fix  the colliders.

P.S. I hope you're able to find the small easter egg i added :)

# 2nd Deliverable
I spent 2 days in front of my laptop and added so many things I don't remember the exact order, but I will do my best to make my fried brain remember.

First I decided to edit my main character's sprite so that they can change direction when the player presses a key.

I designed and drew the new pixel art sides myself using the pixel art program editor aseprite.
Here is the before and after.

Then I imported them into the game to test the animator. It worked but simply changing the direction of my character while walking did not feel natural enough.

Sooooooooooooo

I decided to animate four directions of walking.
I  designed the walk using 8 frames for each direction.

Again this is the before and after.

I imported everything in unity and fixed the animation so that the player can switch between a state of moving (using the walking animation), not moving 
(while holding the previous direction of the character).

Then the deadline almsost came up and I had 2 days to complete everything else.

So I got serious.

First I added a scenemachine camera to my game, it made the feeling a bit smoother.

I had already added collisions on the previous assignments, and I didn't intend to fix it on this scene, because I still plan on changing the map.

But I adjusted the pivot point on my sprites and it made everything seem a bit more immersive.

I added health to my player. 

Then I Added Enemies. First I added an animated spike trap.
Then an animated Red slime. I programmed them to move in a square and do damage to my player. 

Then after testing I found out that 5 lives are far too many and I wanted the game to be a bit less forgiving. So I reduced the max health to 3 health points 
and set the invincibility timer from 2 to 0.5.

After all that I discovered that there will be no way to tell the changes made to the player's health in the current state of the deliverable. 

So I opened up aseprite editor and added a red transparent layer on top of the 4 sides of the character to use them as custom animations, indicating when they player
gets hit. I imported them to unity and the game could show when the player gets hit.

However there was no indication for when the health gets to zero. So I programmed a game manager added a custom script to reset the scene after the player gets hit.




# 3rd Deliverable 


# Conclusions


# Sources

Tilemap: https://cainos.itch.io/pixel-art-top-down-basic
Character Generator:https://picrew.me/image_maker/36838
Music:https://www.youtube.com/watch?v=YOxZh2OaydM
======
