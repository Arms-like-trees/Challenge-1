# Challenge 1 Code Refactoring

As a user I wanted to use the skills and knowledge that I have acquired to review code files and refactor the code files to follow accessibility standards.  While completing this I also wanted to keep the site’s original appearance while viewing the webpage, while also leaving the code in a better state than how it was given to me.

## Finished product appearance

The following image shows what the site should look like upon loading

![Horiseaon website that has a navigation bar in the header, a main section with an image as a background, another main section underneath the fisrt section that has the sites main text content, an aside section to the right that has loosley related content, and a footer at the bootm ofthe page.](/assets/images/01-html-css-git-homework-demo.png)

The image has been scaled down so that it is easier to see the site in its’ entirety but should fill the entire screen when viewing the code in a web browser.

## Finished product summary

While working on the code for this site it was revealed that one of the links was broken and would not allow a user to get to the desired location as a result of clicking the link.  Upon looking at the code it was revealed that  an ID tag was referenced in the hyperlink but was not in the document at all.  To fix this we added the ID for “Search Engine Optimization” so that the hyperlink would know where to redirect.  It was also revealed that in viewing the code it lacked semantic HTML elements in classifying the various sections and had labeled a majority of the sections as "div" element.  In addition all the images did not have “alt” text to describe the image in case the image failed to load as well as provide context for the visually impaired using screen readers.  In addition while looking at the sites CSS file they appeared excessively long and upon closer review was found to have repeated rule sets that could have been consolidated.

While working on this project I learned more about the different semantic HTML tags and how they are used to breakup a document into logical sections  following an order of importance.  For if everything is all under a "div" element then how are you to know that one section is more important than another and what might be only loosely related versus directly related to what is being presented.  I also was able to better understand the use of “alt” text to be able to make all things accessible and usable for everyone, rather than assuming that each individual has the same traits and technology to be able to access the site for its purpose.  Additionally I was able to experience first hand the reason for using DRY, which is a coding principle that stands for “don’t repeat yourself”, as well as being able to write comments in both the HTML and CSS documents to leave notes that is only visible in the code but not online as well as to help direct future coders in how each section is broken into each section.  

