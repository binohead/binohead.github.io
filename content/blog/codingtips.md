---
title: Tips to copy and paste as needed
subtitle: Might save some effort
date: 2024-06-23T20:54:39.467Z
draft: false
featured: false
tags:
   - writing
#image:
#  filename: featured
#  focal_point: Smart
#  preview_only: false
--- 
Here's the central question

## Does it work?

Yes, but first, let's see how Versatil handles images. It works OK as long as you have the correct (absolute) path:

![](https://binohead.github.io/blog/warbled-songs/featured_hu17d2fd7c835acc25fa5b23506fa21df5_113233_8b3383641be7222c8b6729bfb23fa5fa.webp)


OK, now to the key question: how to handle asides, footnotes, etc.

##Footnote

Here's some text with a footnote.[^1]

[^1]: And that's the footnote. Great, though a bit distracting and perhaps disorienting if the function of the "return" icon isn't intuitively obvious.

## Onclick text

Sidenotes are hard, so I gave up on them. Onclick text works, but when you return to the main text it plops you back at the top of the page.

<a href="#" onclick="alert('Most sources will disagree with this characterization.')"> But with important caveats.</a>

## Mouseover text

Here it is with mouseover:

<a href="#" onmouseover="alert('Most sources will disagree with this characterization.')"> But with important caveats.</a>

That's better, but you still have to actively exit.

## Hover

Hover seems the best option for little snippets of text:

This is a [hover text](## "The actual causes of the decline are unknown. This is one of the many, many aspects of psychoornithological frequency saturation currently being explored in our laboratory.") example.

## Dropdowns

There's also the sort of curtain you can pull down, the best option for intermediate (c. one paragraph) text or images (though I might have to fix the path):


<details>
<summary>Example of an effective layout</summary>

{{< figure src="/images/mawa.jpg" caption="A magnolia warbler" >}}

A Magnolia Warbler. Note the rich detail.

</details>
