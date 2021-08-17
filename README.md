# [easy-recipe](https://said-alrove.github.io/easy-recipe/)
This is the first project from Juan Pablo's course of [CSS Grid and Flexbox](https://www.udemy.com/course/css-grid-y-flexbox-la-guia-definitiva-crea-10-proyectos/).

> **Disclaimer:** I'm starting to learn how to use **Git/Github** correctly, therefore there'll be plenty of pull requests, commits and other stuff as tests in this repository, however, *this won't represent my way of working forever*, I'll learn more things along the way as always :D!.

## Table of contents
* [Preview](#preview)
* [What I learned](#what-i-learned)
* [Reports](#reports)
    - [Lighthouse](#lighthouse)
* [Open Graph](#open-graph)
    - [Facebook](#facebook)
    - [Twitter](#twitter)

## Preview

## What I learned
> **Note:** this was an easy project to practice my knowledge in Grid and Flexbox (Grid overall).

* I started using more the **figure** and **figcaption** elements due to I know they are basically mandatory when having a kind of description or legend for the images, and of course, the code looks more organized that way (personal opinion :D).

* I learned that I shouldn't add lazy-loading to those images that are already in the user's view (like the logotype or the hero image) because it's useless (there's no point).

* A few days ago I watched a video where the YouTuber (*Lucas Dalto*) said that's more powerful to put our full URL in the meta properties (like **prefetch**) or other elements that require an URL instead of just putting the local direction ("https://said-alrove.github.io/easy-recipe/index.html" is better than "/index.html"). In like manner we should put the most descriptive information in the alt attributes to have a better SEO.

* I figured out that we shouldn't use **SVG** images for the **Open Graph** properties due to for any reason they're not rendered (there'll be issues warns in the debuggers).

> **Note:** something important to add is that we should use images with high definition (at least over 600px) to achieve a higher lighthouse performance.

* I've also implemented the logical properties (block/inline) due to they already have considerable support from the main browsers (+80% on average) and I considered so useful to use them because there are times when I want to use just a pair of values and I have to either write the full shorthand that includes the four properties or write each property individually, therefore, having another shorthand for those pair of values is great (furthermore you'll have fewer issues if you're working in a site with some language that's written in a different direction as the usual, for instance, Arabic). If you want more information about what I've mentioned, [check this out](https://www.youtube.com/watch?v=kzvmaVik4mA).

* As the last thing, I used the **::selection** pseudo-element to change the colors of the highlighter to make it more similar to the page colors (obviously, I tried to contrast the background of the highlighter with the text color).

> That'd be everything for this project :D.

> **P.D.** I forgot to mention that saw a different way for writing variables' names in CSS, e.g. with the prefix "clr" for colors, and "ff" for fonts, that way I can be more specific when calling a variable (--clr-primary-100), adding a number after the variable's name to indicate how bright or dark is the color if it's that there's more than one variant of that color is also a good idea that I started implementing since a while.

> In like manner, I figured out that we shouldn't use classes, or images properties in the sources elements (picture) due to the browser first parses the img element and then use the source of the fallback if it's possible. If you want more information check out these videos: 

   - [Srcset and sizes attributes](https://www.youtube.com/watch?v=2QYpkrX2N48&t=1s). 
  
   - [When to use .jpg or .png? the answer is WebP ... sort of](https://www.youtube.com/watch?v=Z_28syzkv-0).
  
   - [The HTML picture element explained](https://www.youtube.com/watch?v=Rik3gHT24AM&t=1025s). 
  
> They're part of a serie of videos from [Kevin Powell](https://www.youtube.com/user/KepowOb) **(great channel for CSS lovers)**.

> Also, something important to note is the fact that I discovered that I can use the **lang** attribute in practically any element of the HTML, it was very useful because in the footer I created a couple of sections with different dishes from different countries and regions of the world, but some dishes had some words in other languages (regardless of the name of the dish in essence) such as Spanish with the Spain food, therefore, to use the lang attribute to specify in which language that part of the page was and that way avoid auto-translation by **Google**, was very useful.

## Reports

### Lighthouse
![](readme/lighthouse.png)

## Open Graph

### Facebook
![](readme/facebook.png)

### Twitter
![](readme/twitter.png)
