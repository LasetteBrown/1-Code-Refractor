# 1-Code-Refractor

## Making A Website Accessible

This weeks homework assignment asked me to look at the HTML and CSS files of an existing website to check for accessibility and efficiency without changing features or asthetics. 

I made the following changes to the code in order to make these improvements:

* Tracking changes to HTML file "index.html":

    * The title of the webpage was set as "Webpage" which is not specific or descriptive. I changed the title to read “Horiseon Homepage” so that both the tab as well as any accessibility adaptive technology could recognize the page for what it is.

    * The navigation links at the top of the page should allow the audience to jump to that area of the website when clicked. The navigation link titled "search engine optimization" was not functioning properly. I added ‘id="search-engine-optimization"’ to the div that corresponded with that section of the page so that link at top would work.

    * I fixed the img element within the benefit-cost div. The img element does not require a second </img> and all other img elements in the HTML do not have this so I took it out to make the text more consistent.

    * I added alt text for each img within the HTML that briefly described what was in the image. This allows for accessibility adaptive technology to identify what is in the image.
    
    * I added a title for the div containing the background image. This title is visible when a curser hovers over the image so I did not want the title to be confusing. I chose to make it generic as there was no important data contained within the background image. I therefore titled the background image "Horiseon Social Solution Services, Inc".

    * I changed the html elements so that they used semantic selectors.

* Tracking changes to the CSS file style.css

    * The css file is, in general, unnecessarily repetitive. Therefore, I looked for duplicate styling and consolidated it by creating a class that could be applied to all elements that shared the styling. 

    * I reorganized the styling elements so that they matched the html elements by section.

    * I added comments to the css file explaining each section and each individual change.

