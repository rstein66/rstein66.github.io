---
layout: page
title: Spectrum of Extinction
description: Visualize and inspect human impact on Earth's biodiversity.
img: assets/img/edct-2510/extinction-spectrum/spectrum-of-life-wall.jpeg
importance: 1
category: [fall-2024, edct-2510]
---

**Contents:**

<!-- MarkdownTOC levels="2" -->

- [Concept Overview](#concept-overview)
- [Statement of Need](#statement-of-need)
- [Target Audience](#target-audience)
- [Learning Goals](#learning-goals)
- [Prototype](#prototype)
- [Concept Description](#concept-description)
- [Acknowledgments](#acknowledgments)
- [Additional Resources](#additional-resources)

<!-- /MarkdownTOC -->


**Abbreviations:**

- AMNH – _American Museum of Natural History_
- HoB – _Hall of Biodiversity_
- SoE – _Spectrum of Extinction_
- SoL – _Spectrum of Life \[Wall\]_ 


## Concept Overview

It is difficult to understate the catastrophic devastation of human activity on Earth's biodiversity, especially in the last several hundred years. This human-driven annihilation is often called the "sixth extinction"<sup> [\[1\]](#extinction-resources)</sup>. The Spectrum of Extinction (SoE) project forefronts this extinction to visitors to New York City's world-famous [American Museum of Natural History](https://www.amnh.org/) (AMNH), one of the renowned museum's most iconic permanent exhibitions, the [Spectrum of Life](https://www.amnh.org/exhibitions/permanent/biodiversity/spectrum-of-life") (SoL).



## Statement of Need

Walking into the AMNH's [Hall of Biodiversity](https://www.amnh.org/exhibitions/permanent/biodiversity) (HoB), SoL is one of the first things to catch visitors' eyes. Unsurprisingly so, given that,  

<p style="text-align: center; font-style: italic;"> 
    "The Spectrum of Life in the Hall of Biodiversity is an evolutionary trip through the amazing diversity of life on Earth. The 1,500 specimens represent a wide range [of life]... The only one of its kind in the world, this 100-foot-long installation is arranged into 28 living groups covering 3.5 billion years of evolution. " - <a href="https://www.amnh.org/exhibitions/permanent/biodiversity/spectrum-of-life" target="_blank">AMNH</a>.
</p>

<div class="row">
    <div class="col-sm-8 mt-3 mt-md-0">
        <a href="/assets/img/edct-2510/extinction-spectrum/spectrum-of-life-wall-1400.webp">
            {% include figure.html path="assets/img/edct-2510/extinction-spectrum/spectrum-of-life-wall.jpeg"  class="img-fluid rounded z-depth-1" alt="1,500 specimens representing a wide range of bacteria, fungi, plants, and animals are displayed on a long wall in the Hall of Biodiversity." %}
        </a>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <a href="/assets/img/edct-2510/extinction-spectrum/biodiversity-hall-map-1400.webp">
            {% include figure.html path="assets/img/edct-2510/extinction-spectrum/biodiversity-hall-map.png"  class="img-fluid rounded z-depth-1" alt="biodiversity hall map showing that it has seven parts, including: SoL, Solutions Wall, and Transformation of the Biosphere Wall" %}
        </a>
    </div>
</div>
<div class="caption">
    The Spectrum of Life wall in the AMNH's Hall of Biodiversity (left). The HoB's map (right).
</div>

In the shadow of the HoB's other icon sight, the Rain Forest Diorama, is a narrow and dimly lit corridor home to the Transformation of the Biosphere Wall. According to the official HoB educator's guide<sup> [\[2\]](#educator-guide)</sup>, this wall focuses on "human effects on the environment" and "examines the root causes of biodiversity loss—population growth and overconsumption." SoE's goal is to leverage the popularity of the SoL to increase awareness about human-driven extinction. Besides being an essential part of Earth's history, learning about this devastation is necessary as we confront the rapidly cascading impacts of climate change.


## Target Audience

This project is intended for visitors to use on their smartphones while exploring the AMNH's SoL wall in person.



## Learning Goals

<!-- _What do you want your learners to know or be able to do after engaging with your project._ -->

While celebrating the Earth's incredible biodiversity, increase awareness and understanding of human-driven extinction.



## Prototype

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        <a href="/assets/img/edct-2510/extinction-spectrum/spectrum-ar-view-finder-mock-1400.webp">
            {% include figure.html path="assets/img/edct-2510/extinction-spectrum/spectrum-ar-view-finder-mock.jpeg" alt="Display case photo with several species highlighted in red" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
     <div class="col-sm mt-3 mt-md-0">
        <a href="/assets/img/edct-2510/extinction-spectrum/spectrum-ar-mock-details-1400.webp">
            {% include figure.html path="assets/img/edct-2510/extinction-spectrum/spectrum-ar-mock-details.jpeg" alt="Dodo bird information, including population and location" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
</div>
<div class="caption">
    <b>Prototype mockups:</b> smartphone camera image preview with "extinct" species covered in red (left) and modal showing information about the extinct species the user tapped on (right).
</div>


## Concept Description

_Note:_ Ideally, SoE would be integrated into the AMNH's existing [Android and iOS apps](https://www.amnh.org/plan-your-visit/explorer) or mobile website to avoid inconveniencing visitors by making them download an additional native mobile app. Using existing products also significantly reduces costs by avoiding building and maintaining more products.

### Technological Feasibility

- Smartphones are now ubiquitous worldwide, and even most lower-end models have comparably good cameras and high-resolution screens.  
- The AMNH already offers free WiFi, so visitors' access to cellular data is not a concern.  
- The AMNH already uses [Bluetooth technology to aid navigation](https://www.amnh.org/explore/news-blogs/news-posts/bluetooth-beacons-help-navigate-museum-halls), so they have the technological infrastructure and institutional knowledge.  
- Since the SoL display case specimens are fixed, the project does not need to rely on computer vision. Instead, it can leverage GPS and/or Bluetooth labels to identify specimens quickly. This has the added advantage of relying less on the quality of phone cameras.  

### Rationale for Smartphones

- Creating and updating digital content is typically significantly cheaper and faster than physical signage. 
- A digital platform typically allows visitors to explore far more content without being overwhelmed.
- Visitors can take advantage of the accessible features they have already set up on their phone and are comfortable using–examples include increased font size, display contrast, and screen readers.

### Drawbacks

There are drawbacks, of course. It requires people to have smartphones. While this can be mitigated by allowing visitors to borrow phones, it still assumes familiarity and comfort with their use. Signage, in-app tutorials, and volunteer assistance could partially offset the latter. A more challenging drawback is that using phones means people look "down" at them. They are literally looking at the exhibit from a more limited viewpoint, rather than taking it in as a whole. Staring at the smaller screen also makes sharing the experience with their fellow visitors more challenging.


## Acknowledgments

- This project was initially created for NYU's graduate course [Narrative, Digital Media and Learning](https://steinhardt.nyu.edu/courses/narrative-digital-media-and-learning).
- I am very grateful to my classmates [Wei Wu Dolby](https://weiwudolby.cargo.site/) for sharing her technical expertise (generally and on my project specifically) and [Abigail Dean](https://www.linkedin.com/in/abigail-moon-dean/) for her tour of the AMNH hall.

Images:
  
- The Spectrum of Life wall [photo](/assets/img/edct-2510/extinction-spectrum/spectrum-of-life-wall-1400.webp) is from the AMNH's [webpage](https://www.amnh.org/exhibitions/permanent/biodiversity/spectrum-of-life), as is its `alt` text.
- The Hall of Biodiversity [map](/assets/img/edct-2510/extinction-spectrum/biodiversity-hall-map-1400.webp) is from the educator's guide (see [\[2\]](#educator-guide) below).
- The dodo bird fact card in the prototype mockup is from [A-Z Animals](https://a-z-animals.com/media/2023/03/7f9ef1d7adbd6893ab170b5e553e14dbe5e6e8c4-768x1152.jpg).


## Additional Resources

<a name="extinction-resources"><sup>[1]</sup></a> 
The Stanford University news article ["Study finds human-driven mass extinction is eliminating entire branches of the tree of life"](https://news.stanford.edu/2023/09/18/human-driven-mass-extinction-eliminating-entire-genera/) (Cummings, 2023) is one helpful introduction to the "sixth extinction."

<a name="educator-guide"><sup>[2]</sup></a> AMNH "[Hall of Biodiversity Educator's Guide](https://www.amnh.org/exhibitions/permanent/biodiversity/educator-resources)."