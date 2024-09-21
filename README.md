# Module 5 - Trouble With Bears Website

## Overview

This project includes a template website in which the styling, and html required some adjustment to make it more accessible. The following code is the changes needed in order to be in line
with the project description and requirements. The content of the project includes a website that talks about bears with some audio files, images, and tables describing them.

## Sources and Credits

- Infomation on scalable website design: https://developer.mozilla.org/en-US/docs/Learn/Accessibility/Mobile
- ARIA Screen reading informtion: https://developer.mozilla.org/en-US/docs/Learn/Accessibility/WAI-ARIA_basics
- Information on screen readers and audio: https://developer.mozilla.org/en-US/docs/Learn/Accessibility/Multimedia
- Had some help on the toggle comments javascript using ChatGPT

## How to Run

- To get view the website, simply clone the git repo into your perfered IDE(recommended VSCode).
- Once this is complete, open the project folder and then press F1 to open the top command line.
- Search for Live Preview: Start Server in order to being a local intance of the website/browser.
- Enjoy.


## Accesibility Lab Answers

- The content is still not very accessible — report on what happens when you try to navigate it using a keyboard:
    For me, initally I am not able to use tab, the return key, the arrow keys, or anything to be able to scroll on the website or navigate using only keyboard.

- Can you update the article text to make it easier for screen reader users to navigate?
    Yes, I added a transcript of what the audio would say for those who may not be able to hear it or that use screen readers.

- The navigation menu part of the site (wrapped in <div class="nav"></div>) could be made more accessible by putting it in a proper HTML semantic element. Which one should it be updated to? Make the update.
    It should be changed just to "nav" instead, with some naming adjustments to the CSS aswell.

- The images are currently inaccessible to screen reader users. Can you fix this?
    Yes, I added alt descriptions to each of the images to describe what the images are portraying.

- The <audio> player isn't accessible to hearing impaired (deaf) people — can you add some kind of accessible alternative for these users?
    As stated before, there is now some more transcripts and alternate descriptions in order for deaf people to still see what is being said. This also applies to those who use screenreaders.

- The <audio> player isn't accessible to those using older browsers that don't support HTML audio. How can you allow them to still access the audio?
    I added a sample download link so that users would be able to download the raw audio, instead of needing to access it only through the website.

- The <input> element in the search form at the top could do with a label, but we don't want to add a visible text label that would potentially spoil the design and isn't really needed by sighted users. How can you add a label that is only accessible to screen readers?
    I fixed it by adding an aria-label which makes it accessible to screen readers.

- The two <input> elements in the comment form have visible text labels, but they are not unambiguously associated with their labels — how do you achieve this? Note that you'll need to update some of the CSS rule as well.
    I fixed it by adding some labels to the HTML and then made a small addition to the CSS to allow for the labels to be hidden.

- Can you list two more ideas for improvements that would make the website more accessible?
    One possible addition to the website would be to add a skip to get to the main body content much easier than needing to try and tab through all the options until they reach it.
    Another possible addtion would be to add some more of the ARIA features like Aria-Live, which would give immediate updates to those who are using the site if someone posts a comment, or something is changed on the website.
