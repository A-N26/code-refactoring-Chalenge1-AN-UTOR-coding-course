# Code refactoring challenge

## Description

The project is a challenge at the end of the week1 study period of coding course for us to "challenge" ourselves on what we studied and also were taught in virtual class duriung the said week. Per requirements one was to refactor the code for various acceptance criteria, namely, meaningful title, semantic elements, logical structure, and alt atributes to images.

As per the requirements, I scrubbed through the html and css codes along opening the webpage for an initial comparision to the provided image. Per my understanding of neat and condensed/consolidated, I eliminated the white spaces between each element and spaced out the sub/child-elements to make it easy to see the main elements and the sub-elements with-in each tree/hierarchy.

I checked the webpage again but found it not looking similar to the image provided in more than 1 ways. As such, I edited elements/properties in HTML code and also the CSS code to try and match-up to the image as close as possible. below is a point by point description of the changes:

    HTML code:
    - Consolidated the html code by reducing the whitespacing, inturn reducing the number of total lines used.
    - Added title to html code 'Horiseon - Increase your Website Search Engine generation LEAD' to give the site a name along with an emphasis on important words that describe the use of the site to any given user.
    - Inserted alt attribute below each image source tag to as per acceptance criteria.
    - Included id to search-engine-optimization, online-reputation-management & social-media-marketing div tags under content class div tag line to make them functional to navigate to corresponding tile.
    - Introduced class tags beside each paragraph tag for content, benifits and footer classes. Done to reflect css code adjustments to reflect on the webpage appropriately.

    CSS code:
    - Consolidated css content to reduce white spaces inbetween each property.
    - Added new syntax lines under header, footer, headings, various other elements, etc to try and match-up the final product the the provided img as close as possible.
    - Combined and/or added elements as follows:
        - Merged header and header h1, along with their existing and newly introduced syntax lines (mainly, slightly changed font size and replaced padding with padding bottom, left and top).
        - Separeted .seo from header h1. As it uses a different color which rest of the header does not.
        - Introduced padding bottom and padding left in 'header div' to make some adjustments.
        - Removed header tag from '.header ul' tag and merged 'ul', 'li' and 'a' elements and their corresponding child properties.
        - Merged all the 'h2' tags along with their child properties while removing their separate titles and adding 2 new child properties (margin-top and text-align). And did the very same for H3.
        - 'img' id tag created under each of the 3 content's image source links in html, so as to act upon all the 3 at once instead of separately. Initial child property and value were removed as it kept going wrong and three new properties and their values were introduced to satisfy the purpose.
        - float properties were left as is except minute value change.
        - added '.one' tag to all content headings and '.two' tag to all headings under benefits. Merged the 2 classes keeping only font-size property.
        - Introduced few new child properties to element classes .search-engine-optimization, .online-reputation-management and .social-media-marketing to match-up to the final product image.
        - Benefits section left mostly as is. Except for teh alphabetical rearrangement and inclusion of colour white.
        - Margin property removed from all three Benefits section's image properties.
        - Changed footer heading from h2 to h4. Introduced '.three' to paragraph tag. Merged '.footer', h4 and '.three' and their child properties.

After making the above mentioned changes, I feel that the final website preview looks nearly similar to the one in the image. Yet, I would strongly ask to open it in maximized window as the site's elements weird out when screen size is changed as the content has not been "flex-wrapped".

One challenge I faced while working on this project wasto keep a track of the changes constantly. As such I applied "unit testing" 'methodology' where in I kept of refrencing back to the website after editing each element/child-property to see for the changes (if they made the site look forked/worse or better).

## Image(s)

![alt text](screenshot/page_layout_preview.png)

## Badges

![badmath](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white)
![badmath](https://img.shields.io/badge/CSS-Style-blue)
