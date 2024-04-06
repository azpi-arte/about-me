## Jesus' User Page

Hello! Welcome to my user page where you will be introduced to me as a person
and a programmer.

**Table of Contents**
- [Jesus' User Page](#jesus-user-page)
  - [Skills](#skills)
  - [Artistic Programming Project Flippy Bit](#artistic-programming-project-flippy-bit)
  - [Goals](#goals)

### Skills
I program in these **languages**:
* Python
* Java
* HTML
* CSS
* JavaScript
* C
* C+
* ARM
  
I excel at many creative/artistic practices like:
* Digital Illustrations
* Graphic Design
* UI/UX
* Guitar 
* Video Editing
* Videography
* Creative Writing 
  
I often excel using creative software like:
* Adobe Photoshop, Illustrator, Indesign, Premiere Pro
* Krita
* Blender
  
---
Above all, I am a *highly artistic* and creative programmer/individual.
My spirit is ingited upon seeing the possibility of expressing myself 
artistically through code. I am a front-end focused programmer and excel at 
higher level programming langauges like python.

### Artistic Programming Project Flippy Bit
This is easily seen in my reinterpretation of the game 
> 'Flippy Bit And The Attack Of The Hexadecimals From Base 16'.

[flippy bit screenshot](src\flippy-bit.png)

The game can be found online on [their website](https://flippybitandtheattackofthehexadecimalsfrombase16.com/)

I call my version of the game 
> 'Flippin Bit'

![flippin bit/my version screenshot](src\flippin-bit.png)

Flippin Bit is a reinterpertation of Flippy Bit. I programmed it in Python using
the Pygame library to utilize the library's sprite, audio looping, and text 
display functionality. I drew the sprites and background art myself and composed
my own musical track.

Although my version of the game still isn't where I want it to be I have made 
progress with my vision for it.

Here are the things I would like to implement where the checked items are parts
I have already implemented:
- [x] Custom Sprites
- [X] Custom Soundtrack
- [ ] Gradual Difficulty Increase
- [ ] Difficulty Modes

The hardest part about this project was learning about game loops because some 
of the concepts like delta time were unintuitive.

Although these are only a few lines of code, it is responsible for keeping the 
entire game running:

    #GAME LOOP
    while True:
        for event in pygame.event.get():
            if event.type == pygame.QUIT:
                pygame.quit()
                sys.exit()
            for cluster in cluster_list:
                cluster.bit_flip_main_looper()


---

### Goals
My goals as a software engineer are to
1. Use my technical skills and experience for altruistic purposes. 
2. Improve the daily lives of others with developed software.
3. Contribute to a personally meaningful project with a great team.