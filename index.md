## Hal Milenkovic - Painting Ghosts Magic Leap Project

### 11/18/19 - Super Galaxy Knights: Archer Archives

The first iteration of the project is a Magic Leap One game titled Super Galaxy Knights: Archer Archives.

Super Galaxy Knights: Archer Archives is a mixed reality game set in the Super Galaxy Knights universe. The goal of the experience is to mix immersive 3D comic panels in with action gameplay, utilizing all the tools that the Magic Leap One has to offer.

The game is based off of [Super Galaxy Knights Deluxe R](http://sgkdr.thecomicseries.com/comics/), a comic that I have been drawing since 2016. Super Galaxy Knights was chosen as the property to base this game around because-

- I’m knowledgeable about the universe.
- It’s a property I own.
- Gameplay makes sense in the universe - it’s easy to tailor new characters’ magic powers to the capabilities of Magic Leap rather than the other way around.
- The Super Galaxy Knights universe focuses a lot on inclusivity/diversity.

Here is the planned game flow:

- Player uses magic wand tool to start game & navigate to chapter.
- Player reads through comic panels.
- Player can walk up to panels & look inside. If a panel is in a wall, player can grab & move it.
- After the scene concludes, the game prompts the player to perform some task. e.g. , shoot virtual targets with a magic bow.
- Once the player has completed the chapter, they are shown their score, and unlock the next chapter. Score is framed as “money earned” in the story context.
- Player can play the chapter again for a better score, or move on to the next chapter.

The planned story:

_Diamis Artene is a reformed assassin who is looking for honest work to support her family. She is called in by Ty Kuna, a wealthy tech CEO, to work for his team of bodyguards. However, she soon finds out that Ty may not be the sort of person worth protecting..._

Some design precedents:

- Dr. Grordbort’s Invaders, a Magic Leap One shooter game. It has fun arcade gameplay, but doesn’t really have a story. The game shows that it's important to work around ML1’s field of view - use audio cues & visible indicators to show where the enemy is (although players still complained about the FOV issues regardless).
- Madefire Comic App, a Magic Leap One app. The app has MR comics, with sounds & some animation. The comics are nice, but they're not 3D.

The Capstone Advisor for the project is [Lindsay Grace](https://professorgrace.com/).

The current prototype has the first half of the first chapter of the game. It demonstrates menu, comic panels, archery gameplay, & scoring. There is currently no audio, but there is controller feedback. 

Here is the feedback from the prototype:

- Controls aren’t obvious to a first-time user of Magic Leap.
- Magic Leap sometimes messes up hand tracking or controller tracking.
- Bow is inside FOV when shorter players hold out hand.
- Targets are often outside the FOV, and the player doesnr't know where to look.

### 1/20/20 - Painting Ghosts

The project "Archer Archives" was abandoned. The bow & arrow and 3D comic gameplay was interesting, but it felt clunky due to the limitations of the Magic Leap One.

PAINTING GHOSTS (working title) is a game designed around the limitations of the Magic Leap One first, with the level design and story aspects coming later. The goal of the project is to first come up with simple mechanics that are built around the restrictions of the hardware, then build a simple game to be released to Magic Leap World by May.

The following is the current iteration of the design:
- A ring always floats in front of the user, through which all other virtual objects can be seen.
- This is meant to make the field of view restriction less jarring by adding context to it.
- The story explanation for this could be that the ring is a “magic lens” to let the player see ghosts.
- Enemies fly towards the player, and the player has to use the controller to shoot at the enemy to beat them.
- Current idea is to have the player shoot paint at ghosts - a color matching mechanic could add challenge, and seeing your environment get virtually painted could be fun.

The plan is to have the entire game finished and published on Magic Leap World by May.
- The main gameplay loop should be finalized by the end of January.
- Basic art design & gameplay structure should be finished by the end of February (5 types of basic enemy, 3 bosses?).
- By the end of March, implement story aspects (if any), and add any sound effects, music, & voice acting.
- The month of April should be spent working out bugs, polishing the game, and figuring out publishing.

This is the initial prototype:

[![PROTOTYPE 1](https://img.youtube.com/vi/7zDJAjNYW5s/0.jpg)](https://www.youtube.com/watch?v=7zDJAjNYW5s)

### Ghost Ring – Capstone Prototype 1/28/20

With Magic Leap projects that I’ve done in the past, I’ve tried to ignore or work around the restrictions of the platform – and in my opinion, the projects have suffered because of it. This new project is meant to work WITH the restrictions of the platform rather than against them.

The game presents the ring to the player as a “lens” that lets them see ghosts through it. This provides a physical model for why the user would be able to see the real world through the goggles with a much larger field of view than the game objects. The game entities are all “ghosts”, so you can only see them in a small “lens”.

[![PROTOTYPE 2](https://img.youtube.com/vi/V0RUdqVCdx0/0.jpg)](https://www.youtube.com/watch?v=V0RUdqVCdx0)

### Ghost Ring – Capstone Prototype 2/1/20

Today a few people tested the current prototype, and I got some useful feedback out of it all! Here’s some of the highlights, and how I plan on addressing them moving forward:

- Whenever any liquid is on screen, the game slows to a crawl. I plan on simplifying the liquid physics I programmed – fewer, larger droplets, essentially.
- Without spraying paint, there’s no way of knowing what color paint is currently selected (so you don’t know if you selected a color properly). To fix this, I plan on tinting the ring to fit the color selected.
- A related issue is that it isn’t clear that you have to press down on the touchpad to change colors – testers assumed they would be able to change color with a light touch. I plan on increasing the sensitivity of the controls so that the touchpad works just off of touch.
- Some players also didn’t realize there was a color wheel attached to the touchpad at first – the controller was held outside of the Magic Leap 1’s field of view, so they didn’t see the color wheel. I could change the color selection to be on the ring so players see it (for instance, making it so the players have to point to a floating color wheel), but I felt like that would be even less intuitive. Instead, I plan on having the first level of the game give the player access to only one paint color to start. In the middle of the level, the color wheel will appear in the middle of the ring, and fly over to the controller – that way, the player knows where to look.
- Some players thought the numbers representing the paint fuel and health were “high scores”. To fix this, I plan on making the representations of the fuel meters more visual in nature.
- In general, players wished the aesthetics of the game were more clear instead of just spheres, squares, and so forth.
Moving forward, I plan on introducing more structured gameplay (i.e. levels with specific enemy patterns). To that end, I also plan on introducing a variety of enemy types to the game to make gameplay more engaging. Here are some rough sketches I drew of different ghosts that could appear in the game:

![GHOST DESIGNS](http://snuffysam.com/wordpress/wp-content/uploads/2020/02/ghostSketches_A.png)

The general concept with these ghosts is to create designs that are both “cute” and “scary” – something that will fit with a simple, cel-shaded art style, but creepy nonetheless.

The “shaggy ghost” is intended to be the “default” ghost type – it would float directly towards the player, like the spheres in the current version. The “speaker ghost” would have similar behavior, but would take more paint to defeat. The “foot ghost” would always try to go behind the player, making them more annoying to deal with. The “cat-snake ghost” would make a bouncing motion as it approaches – its up and down movement making it harder to hit. The “mushroom ghost” would grow in and out of the ground in an attempt to get closer to the player. The “centipede ghost” would weave back and forth as it approaches the player, and you would have to destroy its tail (or destroy every segment) to beat it.

The “knight ghost”, “cowgirl ghost”, and “serpent queen ghost” are intended as boss characters. The “knight ghost” would have armor of different colors – you have to destroy each of the armor segments before you could destroy the ghost. The “cowgirl ghost” has a magic revolver that can change the colors of other ghosts in the world – the player has to be able to swap colors quickly to defeat her. The “serpent queen ghost” would be massive – so big that you won’t be able to see her entire body at once. The player will have to spray paint in her mouth when she opens it to attack them.

One other concept I have with these ghosts is that certain shapes would change depending on the colors – for instance, red ghosts would have circular shapes on them, but green ghosts would use triangles. This would be done to accommodate for color-blind players – red, green, and yellow, may be difficult to distinguish for many players, so for them the shapes should provide a clue as to which color the ghost is supposed to be.

### Ghost Ring – Capstone Prototype 2/16/20

[![PROTOTYPE 3](https://img.youtube.com/vi/svSA9k5Rb7E/0.jpg)](https://www.youtube.com/watch?v=svSA9k5Rb7E)

A new prototype was finished today. Here, there were a lot of aesthetics updated, which should make the game’s functions make more sense.

This new prototype will of course need to be user tested to figure out any issues. One potential problem is the color wheel appearing in the middle of the ring. The player is meant to grab the color wheel out of the ring to get it attached to their controller – however, this may not be clear, and some users may not be able to reach the color wheel.

### Ghost Ring – Capstone Prototype 2/23/20

[![PROTOTYPE 4](https://img.youtube.com/vi/28VviC8S7rA/0.jpg)](https://www.youtube.com/watch?v=28VviC8S7rA)

Not too many changes in today’s prototype.

A bigger ghost variant was added, that moves slower and takes more hits to destroy. However, I still don’t have new models created for the different variants yet.

The color wheel now flies towards players instead of hanging in the middle of the ring. Additionally – the UI on the ring for the different paint colors doesn’t appear until the player gains the ability to change colors.

Finally – ghosts are now only damaged by their matching color, rather than the reverse.

### Ghost Ring – Capstone Prototype 3/2/20

[![PROTOTYPE 5](https://img.youtube.com/vi/RuFWyopMobI/0.jpg)](https://www.youtube.com/watch?v=RuFWyopMobI)

In this update, symbols were assigned to the colors so that colorblind players can enjoy the game – red colors get hearts, yellow gets a treble clef, green gets stars, and blue gets crowns.

Additionally, a new ghost type was added that moves very quickly and tries to get behind the player.

### Ghost Ring – Capstone Prototype 3/23/20

[![PROTOTYPE 6](https://img.youtube.com/vi/8up2IkFVI78/0.jpg)](https://www.youtube.com/watch?v=8up2IkFVI78)

There’s been quite a few changes in the latest prototype!

- The color symbols were changed to random squiggles, to avoid confusing users with shapes that had an inherent meaning.
- All ghost types have different models, with unique animations.
- Music and sound effects were added.
- There is now a boss battle!

### Ghost Ring – Capstone Prototype 4/27/20

[![PROTOTYPE 6](https://img.youtube.com/vi/cet_oEbxDdw/0.jpg)](https://www.youtube.com/watch?v=cet_oEbxDdw)

The major things changed in this update are the main menu and the addition of Level 2.

On the main menu, the player can select which level they want using the touchpad, and press the trigger to confirm. Eventually, each menu option will have its own icon. I’m planning on displaying high scores on the menu, but I’m still trying to figure out how to best take advantage of the real estate.

In level 2 – two enemies come at the player instead of one! This is also the level where the centipede ghost will be introduced to the player. At the end of the level, the player will face Hazza, a ghost of a cowgirl. Her bullets change the color of ghosts in the area. I probably have to tweak some things for difficulty, but… for now, this is how it is!
