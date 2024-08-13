---
layout: page
title: Twin Cities Blood Lead Levels Analysis
description: a project with a background image
img: assets/img/12.jpg
importance: 1
category: work
related_publications: false
---
Introduction
When raising a child, parents go through lots of stress to keep their children safe and healthy. From using car seats to getting children vaccinated to working on speech and mobility development and beyond, there is a lot to think about. But one aspect that may be overlooked in providing safe and healthy environment for a child is lead. Lead in paint, soil, air, or water is invisible to the naked eye and has no smell (“Prevent Children’s Exposure to Lead” 2021). However, children can be exposed to lead in a variety of manners, including swallowing house dust or soil contaminated by lead paint or drinking water delivered through lead-based pipes, faucets, and plumbing fixtures. Exposure to this hidden element can seriously harm a child’s health, including damage to the child’s brain and nervous system, slowed growth and development, as well as learning, hearing, speech, and behavior problems (“Prevent Children’s Exposure to Lead” 2021). If exposed to especially high levels of lead, children can face a brain condition known as encephalopathy, severe neurological damage, comas, and even death (“Annual Elevated Blood Lead Levels” 2020). Thus, without a question it is crucial to keep lead exposure to a minimum when raising a child.

In this project, we analyzed elevated blood lead levels in the 7 county Twin Cities metropolitan area using public data provided by the Minnesota Department of Health over the period of 2015-2019 (Health, n.d.). To protect the privacy of individuals, the smallest granularity we were able to obtain this data was on the census tract level, meaning for each of the 691 census tracts in the Twin Cities metropolitan area we obtained information on how many children were tested and how many of those tests resulted in elevated blood lead levels. To have elevated blood lead levels (EBLLs) means that a child has a confirmed result at or above 5 micrograms of lead per deciliter of blood (mcg/dL) (“Annual Elevated Blood Lead Levels” 2020). Children under 6 years of age are tested. The Minnesota Department of Health identifies children living in the Minneapolis and Saint Paul city limits as children at a higher risk for lead exposure and recommends these children to receive blood lead testing at 1 and 2 years of age. This recommendation is warranted given that in 2019, between 1-2% of children in Minneapolis or St. Paul had EBLLs, which is double the statewide average and higher than any other region of Minnesota (“Annual Elevated Blood Lead Levels” 2020). Interestingly, the MDH has found children living in the Metro area but not living in the cities of Minneapolis or St. Paul are at a lower risk of lead exposure than the Greater Minnesota (non-Metro) are. Only about 0.3% of these children have elevated blood lead levels whereas about 0.8% of children living in MN outside the metro area have elevated blood lead levels. As a result, to best explore this contrast between Minneapolis-Saint Paul and the suburban region, this project will solely focus on EBLL data from the 7 county Twin Cities metro area. This region is shown in navy on the road map of Minnesota below.
Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: Spatial Analysis of Elevated Blood Lead Levels in Twin Cities Area
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
