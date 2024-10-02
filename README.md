project 3 prevent training

This project is a formative assessment for Code Institute in which I'm building a one page website on the theme of PREVENT.
PREVENT is the UK governments' strategy for preventing radicalisation and for enabling people to disengage from radicalism.

This project will avoid provocative imagery and will be strong on textual information. This presents a UX challenge: 
to balance readability and visual clarity against the high word count. Text content on the website will be summarised from
official sources. Links will be provided to the relevant web pages.

The expected USER is somebody who works in a sector covered by the Prevent duty. 

Table of contents 

*[USER STORIES](USER-STORIES)

### USER STORIES

As a site user I can access information on the Prevent strategy

(what it is and who it applies to laid out side by side)

As a user I can access information on risk factors

(the signs of radicalisation laid out in a list alongside a sensitivity warning)

As a site user I can access said information in discrete sections

(concise lists with headings)

As a site user I can follow links to other pertinent government resources

As a site user I can follow a link straight to PREVENT training

(links provided in menu and in footer)

As a site user I can follow a link straight to PREVENT reporting

(links provided in menu and in footer)

As a jr developer I would like feedback from my users

(feedback form linked in footer)

### WIREFRAME

![wireframe](assets/images/readme/wireframe.png)

### WIP header and main

![unstyled bootstrap and html](assets/images/readme/wip-header-and-main.png)

### WIP main and footer

![unstyled bootstrap and html](assets/images/readme/wip-main-and-footer.png)

### UX DESIGN

Colour palette: 

#fafafa
tomato
bisque
aqua

Typography: arial, helvetica

Images: credited in page

### VALIDATION

First Attempt:

CSS passed validation with no errors

HTML did not pass validation. Early in the project I encountered an issue where my background image was not covering the whole page.
Resolved by adding a class to the body (<body class="bg">). This image was too bright, and so I intended to darken with an overlay.

Having seen such a thing done before I tried to emulate it but ALAS it would not cover the image. Resolved with some tweaked CSS attributes
and some divs left unclosed:

<div class="bg">
<div class="overlay">

I will return to this problem

### FURTHER TESTING

I have accessed the deployed product on Firefox and Chrome on PC and iPhone. It responds as expected.