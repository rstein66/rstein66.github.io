---
layout: page
title: Neanderthals' Photo Album
description: Build scientific literacy by projecting realistic alternatives.
img: assets/img/msms-ne-album/scene-02-clothing-boxers.jpg
importance: 1
category: [nyu, msms, amnh]
toc:
  sidebar: left
---

<style>
    .audio-description {
        color: var(--global-text-color-light);
        font-family: "Roboto Condensed", Tahoma, sans-serif;
    }
    .block-danger, .block-tip {
        font-size: 1rem;
    }
    .block-warning {
        font-size: 1rem;
        li, em {
            color: var(--global-warning-block-text);
        }
    }
    .quote {
        font-family: "Roboto Condensed", Tahoma, sans-serif;
        text-align: center; 
    }
    .scene-direction {
        color: var(--global-text-color-light);
        font-family: "Roboto Condensed", Tahoma, sans-serif;
        font-style: italic;
    }
    .transcript {
        font-family: "Roboto Serif", Georgia, serif;
        font-size: 0.95rem;
    }
</style>


> By [Alyssa Cohen](https://www.linkedin.com/in/alyssa-cohen-9abb25230/) and Rachel Stein


<div class="subnote">The division of labor broke down roughly as follows: Alyssa focused on the anthropology. I (Rachel) focused on design. We paired on implementation.</div>  

<div class="subnote">This project was initially created for NYU Museum Studies' graduate course <a href="https://as.nyu.edu/departments/museumstudies/courses/spring-2024-course-schedule.html" target="_blank">Digital Frictions - Museum Accessibility and Digital Design</a> (Spring 2024).</div>


**Shorthand:**

- AMNH – _American Museum of Natural History_
- Hall – _Hall of Human Origins_



## Concept Overview

This project complements the Neanderthal diorama in the [Hall of Human Origins](https://www.amnh.org/exhibitions/permanent/human-origins) (Hall) at the [American Museum of Natural History](https://www.amnh.org/) (AMNH) in New York City. 

Our intervention aims to promote scientific literacy by helping visitors imagine scientifically realistic alternatives for what Neanderthals looked like and how they behaved. 

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/msms-ne-album/diorama-photo-by-alyssa.jpg" class="img-fluid rounded" zoomable=true %}
    </div>
</div>
<div class="caption">
    Unaltered close up of the diorama from the visitor's perspective.
</div>



## Statement of Need

The human evolution dioramas in the Hall are meant to help visitors visualize what our hominid ancestors looked like and how they behaved in their respective environments. Their goal is to bring [paleoanthropological](https://www.britannica.com/science/paleoanthropology#:~:text=Paleoanthropology%2C%20interdisciplinary%20branch%20of%20anthropology,and%20the%20theory%20of%20evolution.) evidence to life. However, visitors can easily misinterpret the dioramas’ realism as objective truth. In reality, the dioramas are scientifically informed artistic tableaux resulting from the work of scientists and sculptors. Currently, the AMNH does not help visitors understand this–at least in this exhibition.

<!-- An engaging intervention is especially necessary since the in-person educational lab closed.

A 2007 New York Times article about the Hall's opening describes an interactive educational lab:

<p class="quote">
    "Off in a side room, the Spitzer Hall has an educational laboratory with microscopes and laptops ready for visitors, guided by instructors, to try their hands at examining fossils and learning how to decode DNA. The lab is designed with young people and student groups in mind, but anyone is free to experience something of what it is like to delve into the human past."<br>
     - <a href="https://www.nytimes.com/2007/02/09/arts/design/09orig.html" target="_blank">NYTimes (Feb 2007)</a>
</p>

However, when we visited in the spring of 2024, the physical lab appeared permanently closed (unconfirmed). On the AMNH’s site, we found the [Virtual Human Origins Educational Lab](https://www.amnh.org/exhibitions/permanent/human-origins/educator-resources/human-origins-educational-lab), but no mention of an in-museum lab. -->



## Target Audience

This project is intended for the general public visiting the Hall in-person.

<p class="quote">
    "The Museum welcomes roughly five million visitors annually from New York City and from around the globe, including hundreds of thousands of K–12 students and teachers" - <a href="https://www.amnh.org/about/diversity-equity-inclusion" target="_blank">AMNH</a> 
</p>



## Concept Description

To achieve our learning goal of helping visitors build scientific literacy, we must capture and engage their attention. This is particularly challenging because the Hall's displays are densely packed. Even a reasonably small number of visitors makes the space feel crowded.  

Therefore, rather than adding additional displays, we will use high-quality digital projection to make the Neanderthal diorama appear to change. In addition to saving space, this approach has the advantage of encouraging visitors to engage with the project without requiring them to download a mobile app or click through a kiosk menu. The following section, § Physical Setup, explains this approach further.




## Setup

### What is Hologauze?

According to Holotronica, the makers of Hologauze: 

<p class="quote">
    "Hologauze<sup>®</sup> is the original and best solution for creating large-scale holographic illusions with digital projection. Hologauze<sup>®</sup> is the only patented and fully silvered projection gauze available with unparalleled levels of transparency, brightness, contrast, and viewing angle range." 
    – <a href="https://www.holotronica.com/hologauze/" target="_blank">Holotronica</a>
</p>

In practice, we use the branded product as a generic stand-in for holographic gauze that supports high-quality digital projections (think “Kleenex” for “facial tissues”). Because cost and similar factors were not part of our class project, we could choose a highly regarded product without in-depth product research or comparisons, including costs (e.g., material and setup costs, energy consumption). 

<div class="row justify-content-sm-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/msms-ne-album/hologauze-bluecadet.jpg" alt="BLUECADET in all caps displayed on a nearly invisible screen, which is hung on a step ladder's spreader bar" class="img-fluid rounded" zoomable=true %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/msms-ne-album/hologauze-like-screen.jpg" alt="A semi-transparent floor-to-ceiling mesh screen hangs in the middle of a warehouse. The ladder behind the screen is clearly visible." class="img-fluid rounded" zoomable=true width="69%" %}
    </div>
</div>
<div class="caption">
    The Bluecadet design company <a href="https://www.facebook.com/Bluecadet/videos/experimenting-with-holo-gauze-at-bluecadet/1676063799103729/?locale=en_US" target="_blank">experiments with Hologauze</a> (left). A Hologauze-like screen <a href="https://windon1999.en.made-in-china.com/product/KSXmBhavMeco/China-Holographic-Transparent-Reflective-Stage-Foil-Large-Stage-Foil.html" target="_blank">advertised for purchase</a> (right).
</div>


### Why digital projection?

- Our delivery method reduces but does not eliminate friction for all visitors by asking far less of them. For example, they will not need to download a mobile app or click through menus on a kiosk.  
- Our intervention aims to be self-explanatory to sighted visitors. Still, we hope they will read the captions above (surtitles), listen to the audio (on the webpage), or read the transcript (on the webpage) to enhance their experience. 
- Regrettably, visitors with low vision or blindness still need their smartphones. The exhibition is too compact and crowded to play the audio “out loud.” Doing so might also increase friction for some visitors with sonic frictions (e.g., some Autistic people). Relatedly, we worry that adding captions for visitors with reduced hearing or deafness might make the display more overwhelming. Both are accessed through a large color-contrasting QR code with sonic and haptic cues.


### Physical Setup

- Hologauze will be placed directly behind the diorama's glass. Our video will be projected onto the Hologauze every five minutes, visually altering the Neanderthal mannequins and their environment. 
- Visitors can scan a QR code, bringing them to a web page (see § Web Page) with two versions of the accompanying audio narration. One version will include an audio description (primarily intended for blind and low-vision visitors), and the other will not. The page will also include a verbal description of the diorama for blind and low-vision visitors and a transcript of both narration versions. 
- Captions will appear at the top of the Hologauze screen (surtitles). The audio narration (without verbal description) will sync with the projection, starting when the video begins. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/msms-ne-album/diorama-gmaps-modified.jpg" 
        alt="The annotated image shows the diorama and the display windows (and their informational panels) on either side of the diorama. A large QR code is superimposed onto the information panel directly to the left of the Neanderthal diorama."
        class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    This project assumes that additional small-scale updates will make the existing area more physically accessible. For example, the raised plaque on the floor (to the left of the freestanding informational panel, which is directly in front of the diorama window) would be relocated. 
</div>


### Web page

<a href="/assets/pdf/msms-ne-album/ne-album-mobile-page-mockup.pdf" target="blank"><i class="fas fa-file-pdf"></i> Mobile mockup</a>




## Why Neanderthals?

This project focuses on the Neanderthal diorama (rather than another early human species) because they have long gripped popular imagination. Neanderthals (formally: Homo neanderthalensis) are modern humans (formally: Homo sapiens) closest human relatives. They are the closest species genetically as well as behaviorally. While they are extinct, this closeness makes them most easily relatable. 

> ##### 🔍 WHO?
>
> [§ Storyboard](#storyboard) introduces Neanderthals. 
> For an in-depth introduction, see 
> "[Who were the Neanderthals?](https://www.nhm.ac.uk/discover/who-were-the-neanderthals.html)" by the Natural History Museum \(in London\).    
{: .block-tip }
  
> ##### ⚠️ ACCURACY
>
> The study of early modern humans is a highly active and rapidly evolving 
> field. Therefore:  
> 
> - Reputable resources may have conflicting information, 
> depending on when they were last updated. 
> - While this project makes a concerted effort to reflect the current 
> state of research as of May 2024 (see [§ Works Consulted](#works-consulted)\),
> its focus is on museum accessibility and digital design, _not_ anthropology.
{: .block-warning }

> ##### ♬ RACIAL FEATURES
>
> Our project does <u>not</u> change racial features.
> However, we list them below to highlight that some conventions 
> of depicting Neanderthals may be (unintentionally) heavily influenced 
> by the racism & biases of their discoverers in the 19th century. 
{: .block-danger }

**_Some_ known unknowns about Neanderthals:**

- Racial features:
    + Amount of <u>body hair</u>
    + <u>Eyelid</u> shape
    + <u>Nose</u> cartilage shape
    + <u>Skin color</u>
- Lifestyle features:
    + <u>Clothing</u> is dependent on regional factors, such as weather & available resources
    + <u>Diet</u> is dependent on the regional availability of flora and fauna
    + <u>Facial hair</u> grooming (e.g., may have used obsidian as razors)
    + <u>Shelters</u> (e.g., caves, rocky outcrops)
<hr>



## Storyboard

> ##### 🎞️ RECORDING
>
> Click [here](https://youtu.be/iwFNIBSvdSk) for a recording of the storyboard scenes with voice-over.     
{: .block-tip }

Storyboard-specific:
  
|            Term           |                     Meaning                     |
|---------------------------|-------------------------------------------------|
| Default state&nbsp;&nbsp; | Unmodified diorama (see [_Intro scene_](#intro-scene)\) |
| Movie                     | All scenes                                      |
|                           |                                                 |
|                            **Style**                            |         **Description**                     |
| Normal text                                                      | –                                           |
| <span class="transcript">Script</span>                           | Always spoken and written               |
| <span class="caption">Image caption</span>                       | Adds context, _not_ displayed; smaller font |
| <span class="scene-direction">[scene direction]</span>           | Narrow font, gray, bracketed, italicized    |
| <span class="audio-description">{audio description}</span>&nbsp; | Narrow font, gray, enclosed in curly braces |

<br>


### Opening scene

<p class="scene-direction">[As the narration begins, inspirational/curiosity-provoking music plays softly in the background. 
    <u>Examples</u>: <a href="https://artlist.io/royalty-free-music/song/rising-star/130137" target="_blank">"Rising Star" by TURPAK</a> or <a href="https://artlist.io/royalty-free-music/song/cat-walk/85915" target="_blank">"Cat Walk" by Roie Shpigler</a>
]</p>

<p class="transcript">Neanderthals lived in Europe, the Middle East, and parts of Asia. They appeared about 400,000 years ago and became extinct 40,000 years ago.</p>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/msms-ne-album/range-of-Neanderthals.jpg" alt="Known Neanderthal range in Europe (blue), Southwest Asia (orange), Uzbekistan (green), and the Altai mountains (violet)" class="img-fluid rounded" zoomable=true %}
    </div>
</div>
<div class="caption">
    Neanderthals' known range, inferred from skeletal remains 
    <br>
    (<a href="https://commons.wikimedia.org/wiki/File:Range_of_NeanderthalsAColoured.png" target="_blank">Nilenbert, Nicolas Perrault III, 2017</a>, 
    <a href="http://creativecommons.org/licenses/by-sa/3.0/" target="_blank" title="Creative Commons Attribution-Share Alike 3.0">CC BY-SA 3.0</a> license).
    <br><br>
    An up-to-date and simplified map should replace this one.
</div>

<p class="scene-direction">[Display "50,000 years ago" caption.]<br>[Zoom in on western France. Display "Western France" caption at maximum zoom.]</p>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/msms-ne-album/world-map-modern.jpg" alt="Physical map of the modern world without text or political boundaries" class="img-fluid rounded" zoomable=true %}
    </div>
</div>
<div class="caption">
    Replace with world map c. 50,000 years ago. 
</div>

<p class="scene-direction">[Display fades to black.]</p>


### Intro scene

<p class="transcript">Here, we have a 50,000-year-old Neanderthal campsite that archaeologists found in western France. But how do you know that what you're looking at is real? It might not be. Scientists used a lot of real evidence to create this scene, but how they interpret it might be wrong. Let's explore some other realistic possibilities... following scientific evidence, of course!</p>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/msms-ne-album/scene-00-default.jpg" class="img-fluid rounded" zoomable=true %}
    </div>
</div>
<div class="caption">
    Default state. 
</div>


### Hair scene

<p class="scene-direction">[Hair changes appear on the mannequins one by one when mentioned.]</p>

<p class="transcript">Let's start with their hair. Scientists can't know what color every Neanderthal's hair was or how they styled it. DNA gives us clues but not exact answers. Like us, some Neanderthals had brown hair that they braided. Some were bald with red beards. Others had short, gray hair.</p>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/msms-ne-album/scene-01-hair.jpg" class="img-fluid rounded" zoomable=true %}
    </div>
</div>

<p class="scene-direction">[Display returns to default state.]</p>


### Clothing scenes

<p class="scene-direction">[New items appear when named.]</p>

<p class="transcript">Did Neanderthals wear clothes? Probably. We know they sewed with needles made of animal bones. In this scene, the female in the middle is preparing an animal hide, probably to make clothes. During the hot French summer, a female might have worn a light dress or a straw hat to protect her from the sun. Neanderthals at least wore underwear. <span class="audio-description">{Boxers with pink hearts appear on the male Neanderthal.}</span> Oops! It's 50,000 years too early for those.</p>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/msms-ne-album/scene-02-clothing-boxers.jpg" class="img-fluid rounded" zoomable=true %}
    </div>
</div>

<span class="audio-description">{The boxers are replaced with a beige loin cloth.}</span> <span class="transcript">Much better!</span>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/msms-ne-album/scene-03-clothing-loincloth.jpg" class="img-fluid rounded" zoomable=true %}
    </div>
</div>

<p class="scene-direction">[Display returns to default state.]</p>


### Food scene

<p class="scene-direction">[Mannequins repositioned. The animal hide (that the younger woman is preparing) disappears.]<br>[New items appear when named.]</p>

<p class="transcript">During the summer in France, scientists think Neanderthals gathered fruits, nuts, and seeds. They knew how to use fire and maybe cook some fish for dinner.</p>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/msms-ne-album/scene-04-food.jpg" class="img-fluid rounded" zoomable=true %}
    </div>
</div>

<p class="scene-direction">[Display returns to default state.]</p>


### Recreation scene

<p class="scene-direction">[Animal hide and spear disappear.]<br>[New items appear when named.]</p>

<p class="transcript">There's evidence that Neanderthals had rituals. Maybe they collected flowers or played music for a special ceremony. The first modern human-made instruments were flutes, so maybe Neanderthals played them too.</p>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/msms-ne-album/scene-05-rec.jpg" class="img-fluid rounded" zoomable=true %}
    </div>
</div>

<p class="scene-direction">[Display returns to default state.]</p>


### Family scene

<p class="scene-direction">[Mannequins repositioned. Animal hide and spear disappear.]<br>[New items appear when named.]</p>

<p class="transcript">Like us, Neanderthals had fun with their families and took care of each other. Can you imagine a mom watching her toddler play while grandma holds his baby sister and dad tells dad jokes?</p>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/msms-ne-album/scene-06-family.jpg" class="img-fluid rounded" zoomable=true %}
    </div>
</div>

<p class="scene-direction">[Display returns to default state.]</p>


### Outro scene

<p class="scene-direction">[Display fades to black.]<br>[Images <u>similar</u>   to those below appear as the narrator speaks.]</p>

<p class="transcript">Just like humans, Neanderthals had different skin tones, diets, and cultures based on where they lived. With the archaeological and DNA evidence we have <em>today</em>, we don't know everything about our evolutionary cousins. Scientists use evidence to help us imagine realistic possibilities, but unless we have a time machine, we can't know for sure! Who knows, with new scientific technology and discoveries, maybe we'll get more answers soon!</p>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/msms-ne-album/outro-analyzing-skull.jpg" alt="Scientist in a lab taking samples from a human-like skull" class="img-fluid rounded z-depth-0" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/msms-ne-album/outro-family-campfire.jpg" alt="Multiracial families roasting marshmallows while gathering around campfire in the woods" class="img-fluid rounded z-depth-0" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/msms-ne-album/outro-kids-playing-at-home.jpg" alt="Two girls and one boy, all with traditional Muslim head coverings, playing a hand game at home in Lebanon" class="img-fluid rounded z-depth-0" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/msms-ne-album/outro-eagle-with-hunter.jpg" alt="A gold eagle standing beside a traditionally dressed, sitting Kazakh Eagle Hunter in Mongolia" class="img-fluid rounded z-depth-0" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/msms-ne-album/outro-hair-braiding.jpg" alt="Standing Black woman braiding the hair of a sitting biracial woman" class="img-fluid rounded z-depth-0" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/msms-ne-album/outro-dna-sequencing.jpg" alt="Scientist in a lab pipetting sample into a vial for DNA testing" class="img-fluid rounded z-depth-0" %}
    </div>
</div>


<p class="scene-direction">[The display fades to black and then returns to the default state (i.e., fully transparent).]</p>

<hr>



## Future Work

If we were to continue this project, the tasks we would like to focus on are listed below.

**Content**
<div class="subnote">(In order of importance.)</div>

1.  <u>Shorten script</u>- the narration (without audio description) should be 1:30 minutes. at most to reduce the chances of losing the audience's attention. Visitor feedback would be especially important for this task – _e.g., Ask them what their least favorite scene was._
2.  Add additional <u>audio description</u>.
3.  Add a verbal <u>description of the diorama</u>.
4.  Add an <u>article</u> with educational content about Neanderthals, paleoanthropology, and paleogenetics.

**Work with**
    
- <u>Anthropologists</u> to verify accuracy.
    + _E.g., In the [Recreation scene](#recreation-scene), use flowers that likely grew in western France approximately 50,000 years ago._
- <u>Designers</u> - I am not a designer. Professional expertise would greatly benefit the [§ Storyboard](#storyboard) scenes and _[Web page](#web-page)_ designs.  
- Improve accessibility by soliciting feedback from \[paid\] <u>disability consultants</u>, who should include people with blindness, low vision, deafness, and other disabilities. 
    + _E.g., Is important information missing from the verbal descriptions? Are the verbal descriptions too long? Is it important to include an American Sign Language translation?_


**Physical layout**

- Can a <u>bench or stools</u> be added to allow people to sit while watching the video? This would improve accessibility, and likely visitor engagement, but the Hall is very compact.
- Can the panels on either side of the diorama be relocated to give viewers <u>more space</u>? (see _[Physical setup](#physical-setup)_\). 
- Consider <u>applying Hologauze</u> to the other dioramas in exhibition. Will visitors expect and be disappointed that only one diorama is "animated"?


## Acknowledgments

**People**

Thank you <u><em>very</em></u> much to following for their time and guidance: 

- Course instructor [Rosanna N. Flouty](https://as.nyu.edu/faculty/rosanna-n-flouty.html), NYU Clinical Associate Professor and Museum Studies Program Director
- [Josh Goldblum](https://www.linkedin.com/in/joshgoldblum/), Founder and CEO of Bluecadet
- [Alice Walker](https://www.linkedin.com/in/alicedowwalker/), New Business Strategist at Local Projects

<!-- - 📍 NYU Anthropology prof -->
**Voice-over** (in the [recording](https://youtu.be/iwFNIBSvdSk)\) was generated by [Natural Readers](https://www.naturalreaders.com).

<details>
    <summary><b>Image Sources</b></summary>
    <ul>
        <li>
            <a href="/assets/img/msms-ne-album/diorama-photo-by-alyssa-1400.webp" target="_blank">Diorama</a> (the basis for all scenes) - Alyssa Cohen (Aug 2021)
        </li>
        <li>
            <a href="/assets/img/msms-ne-album/diorama-gmaps-modified-1400.webp" target="_blank">Diorama in situ</a> 
            (in gallery) - modified 
            <a href="https://www.google.com/maps/@40.7808345,-73.9750143,2a,75y,174.51h,88.24t/data=!3m6!1e1!3m4!1sgHiPAbLEp9XN9loUM6Kq7A!2e0!7i13312!8i6656?coh=205409&entry=ttu" target="_blank">Google Maps</a> (Mar 2016)
        </li>
        <li>
            Bluecadet on Hologauze - 
            <a href="https://www.facebook.com/Bluecadet/videos/experimenting-with-holo-gauze-at-bluecadet/1676063799103729/?locale=en_US" target="_blank"> Bluecadet on Facebook</a>
        </li>
        <li>
            <a href="/assets/img/msms-ne-album/hologauze-like-screen-1400.webp" target="_blank">Hologauze-like screen</a> - 
            <a href="https://windon1999.en.made-in-china.com/product/KSXmBhavMeco/China-Holographic-Transparent-Reflective-Stage-Foil-Large-Stage-Foil.html" target="_blank">Miss June Tang on Made-in-China</a>
        </li>
        <li>Mobile mockup assets (modified)<ul>
            <li>Screenshots from the mobile version of the <a href="https://www.amnh.org/exhibitions/permanent/human-origins">AMNH's "Anne and Bernard Spitzer Hall of Human Origins" page</a></li>
            <li>Screenshots from the iOS 17 Voice Memo app</li>
        </ul></li>
        <li>Opening scene assets <ul>
            <li>Neanderthals' range – image & alt text: 
                <a href="https://commons.wikimedia.org/wiki/File:Range_of_NeanderthalsAColoured.png" target="_blank">Nilenbert, Nicolas Perrault III</a> (Nov 2017)</li> 
            <li>Modern world map - <a href="https://www.surfertoday.com/environment/maps-of-the-world" target="_blank">SurferToday.com</a></li>
        </ul></li>
        <li>Clothing scene assets (modified)<ul>
            <li>Boxers  - <a href="https://www.istockphoto.com/photo/valentines-underwear-gm506800876-84385985">wabang70 on iStock</a></li>
            <li>Hat - <a href="https://x.com/profdanhicks/status/1256150642193809408">@profdanhicks on Twitter</a></li>
            <li>Loincloth  - <a href="https://www.renderhub.com/artshock/brown-leather-loincloth/brown-leather-loincloth-01.jpg">artshock on RenderHub</a></li>
        </ul></li>
        <li>Family scene assets (modified)<ul>
            <li>Baby in sling - <a href="https://www.lillebaby.com/cdn/shop/products/sling_nimbuscloud_0328_720x_9d01cfee-9123-4e8a-940c-16b2423a445d_1800x1800.jpg?v=1663630432">LÍLLÉbaby</a></li>
            <li>Child - <a href="https://www.haaretz.com/archaeology/2018-11-04/ty-article-magazine/neanderthal-children-got-badly-sick-in-winter-study-shows/0000017f-da73-d432-a77f-df7ba97b0000">Haaretz</a></li>
        </ul></li>
        <li>Food scene assets (modified)<ul>
            <li>Basket - <a href="https://www.istockphoto.com/photo/braiding-basket-gm166521429-23702373">VladyslavDanilin on iStock</a></li>
            <li>Fire - <a href="https://www.istockphoto.com/photo/campfire-on-the-beach-gm1802190577-548575726">Dontstop on iStock</a></li>
            <li>Fish - <a href="https://www.istockphoto.com/photo/european-bass-spigola-branzino-dicentrarchus-labrax-mediterranean-fish-gm1276836506-376225842">ItalianFoodProduction on iStock</a></li>
            <li>Grapes - <a href="https://www.istockphoto.com/photo/bunch-of-grapes-and-raisins-gm119680411-14843196">popovaphoto on iStock</a></li>
            <li>Nuts - <a href="https://www.istockphoto.com/photo/mix-nuts-with-wooden-bowl-gm617882672-107382411">Altayb on iStock</a></li>
            <li>Tree stump - <a href="https://www.istockphoto.com/photo/beautiful-texture-of-old-tree-stump-table-top-on-white-background-gm1166542705-321380871">HAKINMHAN on iStock</a> </li>
        </ul></li>
        <li>Recreation scene assets (modified)<ul>
            <li>Flute - <a href="https://www.britishmuseum.org/collection/object/Y_EA6385">British Museum</a></li>
            <li>Flowers - <a href="https://www.istockphoto.com/photo/bunch-of-lavender-flowers-tied-with-a-rope-isolated-on-a-white-gm1332140077-415073233">igoriss on iStock</a> </li>
        </ul></li>
        <li>Outro scene assets<ul>
            <li>Analyzing skull - <a href="https://www.istockphoto.com/photo/science-professional-and-person-with-skull-in-hand-for-analysis-or-research-for-gm1713042839-539924609">Jacob Wackerhausen on iStock</a> (image & modified alt text)</li>
            <li>DNA sequencing - <a href="https://www.istockphoto.com/photo/scientist-pipetting-sample-into-a-vial-for-dna-testing-gm1334095553-416349684">Cavan Images on iStock</a> (image & modified alt text)</li>
            <li>Eagle with its hunter - <a href="https://www.istockphoto.com/photo/gold-eagle-resting-with-eye-patch-covered-beside-kazakh-eagle-hunter-at-bayan-olgii-gm2154717627-575571523">Edwin Tan on iStock</a> (image & modified alt text)</li>
            <li>Family campfire - <a href="https://www.istockphoto.com/photo/multiracial-families-roasting-marshmallows-while-gathering-around-campfire-in-the-gm1773349119-546062631">Drazen Zigic on iStock</a> (image & modified alt text)</li>
            <li>Hair braiding - <a href="https://www.istockphoto.com/photo/black-female-hairstylist-working-on-mixed-race-female-client-at-home-gm1952511355-557281193">AzmanL on iStock</a> (image & modified alt text)</li>
            <li>Kids playing at home - <a href="https://www.istockphoto.com/photo/kids-playing-at-home-gm1440494365-480461075">FG Trade on iStock</a> (image & modified alt text)</li>
        </ul></li>
    </ul>

    <hr>
</details>
<br>



## Works Consulted

<a href="/assets/pdf/msms-ne-album/msms-neanderthal-bib.pdf" target="blank"><i class="fas fa-file-pdf"></i> 
    Works that informed our background research
</a>
