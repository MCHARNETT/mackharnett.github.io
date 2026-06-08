---
layout: page
title: About
permalink: /about/
---

Hi! My name is MacKenzie Harnett, and I am an incoming postdoctoral fellow in MIT EECS at the [Perceptual Engineering Lab](https://mit-pel.com/) within CSAIL, where I will be working with **Dr. Jas Brooks**. Previously, I worked with **Dr. Rebecca Friesen** at the [Friesen Haptics Lab](https://www.friesenhaptics.com/team). This website is primarily a means for me to document past work, provide commentary on that work, and to report my current goings-ons. 

I received my **Bachelor of Science in Mechanical Engineering** from **Cornell University** in May 2021, and I received my **Ph.D. in Mechanical Engineering** from **Texas A&M University** in May 2026. Feel free to download my CV [here]({{ '/assets/pdf/cv.pdf' | relative_url }}).

My recent research interests are well embedded within the haptics space, specifically with regards to how we interpret and generate tactile graphics and artwork across a range of different platforms and different materials/textures.

Anyone interested in knowing more about my work or collaborating with me should reach out via my personal email:<span style="color:green"> harnettmackenzie \[at\] gmail \[dot\] com. </span>

<style>
#hej-toggle {
  display: none;
}

#hej-img {
  float: right;
  margin: 0 0 1em 1em;
  cursor: pointer;
}

#hej-toggle:checked + label #hej-img {
  animation: shake 0.4s;
}

@keyframes shake {
  0%, 100% { transform: translateX(0); }
  20%, 60% { transform: translateX(-5px); }
  40%, 80% { transform: translateX(5px); }
}
</style>

<input type="checkbox" id="hej-toggle">

<label for="hej-toggle">
  <img id="hej-img" src="/images/hej.png" alt="Hello!">
</label>