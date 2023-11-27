---
layout: page
title: Brooklyn Kids
description: Explore the Brooklyn Children's Museum by game.
img: assets/img/edct-2510/brooklyn-kids/bk-tunnel-with-otter.png
importance: 1
category: edct-2510
---

**Contents:**

<!-- MarkdownTOC -->

- [Concept Overview](#concept-overview)
- [Statement of Need](#statement-of-need)
- [Target Audience](#target-audience)
- [Learning Goals](#learning-goals)
- [Learning Theories](#learning-theories)
- [Concept Description](#concept-description)
- [Prototype](#prototype)
- [Acknowledgments](#acknowledgments)
- [Additional Resources](#additional-resources)

<!-- /MarkdownTOC -->

> <i class="fab fa-github"></i> **Click [here](https://github.com/rstein66/brooklyn-kids) to see code.**


### Concept Overview

_Brooklyn Kids_ gives children the freedom to "choose their own adventure" when exploring the [Brooklyn Children's Museum](https://www.brooklynkids.org/) (BCM) in Brooklyn, New York. The child avatar, Kit, partners with an imaginary museum resident named Ollie the Otter. 


### Statement of Need

**Subject**

<p style="text-align: center; font-style: italic;"> 
    "As the world’s first children’s museum, Brooklyn Children’s Museum has welcomed millions of children and families since 1899 to experience the love of learning" - <a href="https://www.brooklynkids.org/visit" target="_blank">BCM</a>
</p>
  
The game focuses on the BCM's ground floor, which houses its permanent exhibits.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        <a href="/assets/img/edct-2510/brooklyn-kids/bk-museum-map-1400.webp">
            {% include figure.html path="assets/img/edct-2510/brooklyn-kids/bk-museum-map.png" title="BCM floor map" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <a href="/assets/img/edct-2510/brooklyn-kids/bk-airmaze-1400.webp">
            {% include figure.html path="assets/img/edct-2510/brooklyn-kids/bk-airmaze.png" title="BCM AirMaze exhibit" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <a href="/assets/img/edct-2510/brooklyn-kids/bk-design-studio-1400.webp">{% include figure.html path="assets/img/edct-2510/brooklyn-kids/bk-design-studio.png" title="BCM pretend design studio" class="img-fluid rounded z-depth-1" %}</a>
    </div>
</div>
<div class="caption">
     Museum ground floor map (left), <a href="https://www.brooklynkids.org/exhibits/airmaze/" target="_blank"><i>AirMaze</i></a> exhibit (middle), & the <a href="https://www.brooklynkids.org/exhibits/world-brooklyn/" target="_blank"><i>Brooklyn World</i></a> exhibit's design studio (right)
</div>
  

**Purpose**
  
Social narratives<sup> [\[1\]](#social-narrative-resources)</sup> were one inspiration for this game. While it is not a social narrative, one of its primary purposes is similarly to help visitors prepare for their visit so that they do not feel overwhelmed. While the game is intended for children, it could also help parents and field trip leaders prepare.  

The game's second purpose is to give children the freedom to \[virtually\] visit/revisit the museum on their terms and schedule. There is far too much to see in a single visit.  

  
### Target Audience

Children (approximately 4-8 years old) will soon visit, or who have recently visited, the Brooklyn Children's Museum. 

Longer-term vision to better support this audience:

- The next development step is for the game's menu options to be read out loud to avoid assumptions about the children's reading skills. 
- The current word is highlighted to support children learning to read.
- While the proof of concept's narration and subtitles are in \[Standard American\] English, Ren'Py offers [multi-language support](https://www.renpy.org/doc/html/translation.html).


### Learning Goals

After engaging with the project, I want players to 
- Feel more familiar with the BCM and
- Begin/continue to develop positive associations with the BCM.

  
### Learning Theories

- **[Constructivist Theory](https://www.instructionaldesign.org/theories/constructivist/) –** The "choose your own adventure" format allows users to take ownership of their own discovery, including the pace of learning.
  
- **[Dual Coding Theory](https://www.instructionaldesign.org/theories/dual-coding) –** The inclusion of images, captions, and narration allows users to process the content both visually and verbally to enhance comprehension and recall. 


### Concept Description

I chose to use the game generation framework Ren'Py, which I learned about from classmates' demo. Its website [explains](https://www.renpy.org/why.html) that "Ren'Py is a free and cross platform engine for digital storytelling." Largely because I previously worked as a software developer, I found it an intuitive, flexible, and fast way to create a game. 

  
### Prototype

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        <a href="/assets/img/edct-2510/brooklyn-kids/bk-game-flow-1400.webp">{% include figure.html path="assets/img/edct-2510/brooklyn-kids/bk-game-flow.png" title="Game flow & corresponding videos" class="img-fluid rounded z-depth-1" %}</a>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="https://youtube.com/embed/lYl_9Myju_o" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="https://youtube.com/embed/BltOP3q2L_E" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    <a href="https://github.com/rstein66/brooklyn-kids/blob/main/game/script.rpy" target="_blank">Script</a> flowchart (left), followed by screen recordings with audio: video 1 (middle) & video 2 (right). Please watch in order.
</div>

  
### Acknowledgments

- This project was initially created for NYU's graduate course [Narrative, Digital Media and Learning](https://steinhardt.nyu.edu/courses/narrative-digital-media-and-learning).
- As currently configured, the project does not support users who are blind or have low vision.  
- Most references are either [here](https://github.com/rstein66/brooklyn-kids#attribution) or linked in the text above. Additional ones are listed below.  
- BCM's ground floor map is taken from the museum's [Activity Guide](https://www.brooklynkids.org/wp-content/uploads/2022/06/BCM-Activity-Book.pdf).  

### Additional Resources

<a name="social-narrative-resources"><sup>[1]</sup></a> <b>Social Narratives</b>  

- As described by the NYU Ability Project's "[Sensory Resources Guide For Museums](https://wp.nyu.edu/sensory_resources_guide_for_museums/)," "\[s\]ocial narrative is a story with photos and text that describes what visitors are expected to experience while visiting your museum or historic site... Thanks to social narratives, visitors can prepare for their museum visit... A social narrative is most commonly used by visitors with autism spectrum disorder... It \[can\] also serves a wide range of people such as school group visits, \[and\] independent family visits."

- _Example:_ the Met's for [families with children with autism](https://www.metmuseum.org/-/media/files/events/programs/progs-for-visitors-with-disabilities/social-narrative-children.pdf). Related Met resources are [here](https://www.metmuseum.org/events/programs/access/visitors-with-developmental-and-learning-disabilities/for-visitors-with-autism-spectrum-disorders).  
  
- "[Steps for Implementation: Social Narratives](https://autismpdc.fpg.unc.edu/sites/autismpdc.fpg.unc.edu/files/SocialNarratives_Steps_0.pdf)" by the National Professional Development Center on Autism Spectrum Disorders  