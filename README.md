# Horiseon Refactoring

## Finished product summary

While working on the code for this site it was revealed that one of the links was broken and would not allow a user to get to the desired location as a result of clicking the link.  Upon looking at the code it was revealed that an ID tag was referenced in the hyperlink but was not in the document at all.  To fix this I added the ID for “Search Engine Optimization” so that the hyperlink would know where to redirect.  The HTML file also lacked a title for the site while only having a placeholder of “website”.  The code lacked semantic HTML elements in classifying the various sections and had labeled a majority of the sections as "div" element.  In addition, all the images did not have “alt” text to describe the image in case the image failed to load as well as provide context for the visually impaired using screen readers.  While looking at the sites CSS file it appeared excessively long and upon closer review was found to have repeated rule sets that could have been consolidated using the “DRY” method.

The following is a link to the website.  [Horiseon marketing website](https://arms-like-trees.github.io/Challenge-1/)

## Finished product appearance

The following image shows what the site should look like upon loading

![Horiseon website that has a navigation bar in the header, a main section with an image as a background, another main section underneath the fisrt section that has the sites main text content, an aside section to the right that has loosley related content, and a footer at the bootm ofthe page.](/assets/images/01-html-css-git-homework-demo.png)

The image has been scaled down so that it is easier to see the site in its’ entirety but should fill the entire screen when viewing the code in a web browser.

