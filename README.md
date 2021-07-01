# 01 HTML, CSS, and Git: Code Refactor

# Section 01: General Information

First code Boot Camp assignment.
 by Cristobal Hernandez

## Description
The task is cleaning the code for the Horiseon webpage. On the next section the document shows what changes have been made and their description on why they were changed.

## Deployed Application URL
https://cristobalhdz.github.io/HoriseonWebpage_FirstHomework/

# Section 2: Changes to the code
## Changes made to HTML

<b>Line 11 & 26:</b> Changed `<div>` to `<header>`.
</br>
Change description: It is a header.

<b>Line 28:</b> Changed `<div class="hero"></div>` to `<figure class="hero" alt="hero banner image"></figure>`
<br/>
Change description: Changed from `<div>` to a `<figure>` to better show that the object is an image. Also all images should have an `alt` to show the image´s description so it was added

<b>Line 31:</b> Changed added `id="search-engine-optimization"`
<br/>
Change description: On the original code there is no id so when the user clicks on the header, it does nothing

<b>Lines 34, 40, 48, 60, 67 & 74:</b> Added `alt="Image description" to the <img /> tag`.
<br/>
Change description: All `<img />` tags should have a description in case the image doesn´t load.

<b>Line 30, 54, 57 & 79:</b> Changed from `<div>` to `<section>`.
<br/>
Change description: `<section>` better represents grouping of content,  while `<div>` is better represented in small chunks of content.

<b>Line 81 & 86:</b> Changed from `<div>` to `<footer>`. Removed `class="footer"` because it is now a Tag and not a class.
<br/>
Change description: It is a footer.

<br/>
<br/>

## Changes made to CSS

<b>Line 5:</b> Added a `scroll-behaviour: smooth`
<br/>
Change description: It makes a better user experience

<b>Line 66:</b> Added the line with the code `max-height:200px` for the float-left class.
</br>
Change description: It was moved from the image formats. We can add just that one line of text and remove 3 classes that did the exact same thing

<b>Line 92-95:</b> Merged all classes into just one called `.benefit-card`
<br/>
Change description: The benefit-lead,brand and card do the same thing. It is easier to merge them into just one class

<b>Line 83:</b> Make the padding larger. It was `padding:20px` changed to `padding: 20px 20px 80px 20px`
<br/>
Change description: The benefits collumn was not looking good besides the main cards. This change made it so the bottom page looks better

<b>Line 97-100:</b> Merged all classes into just one called `.benefit-card h3`
<br/>
Change description: The benefit-lead,brand and card (h3) do the same thing. It is easier to merge them into just one class

<b>Line 102-106:</b> Merged all classes into just one called `.benefit-card img`
<br/>
Change description: The benefit-lead,brand and card (img) do the same thing. It is easier to merge them into just one class

<b>Line 117-120:</b> Changed the name to `.main-card-format h2`
<br/>
Change description: There are another 2 classes with the same name that could be turned into just 1 class.

<b>Line 122 & 129:</b> Changed the footer from a class to a tag
<br/>
Change description: We can make use of the tag and clean the code