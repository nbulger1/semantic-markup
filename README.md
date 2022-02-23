# Semantic Markup - Week 1 Homework

## Description

The following user story was created under the premise that web **accessibility** is of utmost importance not only for increasing search engine ranking but also for people with disabilities. It is extremely important that people with disabilities can use a website through a variety of assistive technologies including video captions and screen readers.

I was provided with an HTML code file that led to a fully functional webpage. While the code worked to populate a webpage, the file lacked semantic markup and the CSS file needed some reformatting and consolidating to promote accessibility. Finally, both CSS and HTML files needed comments to explain each portion and property of code. 

By working through the code, I was able to experience the difficulty of locating different portions of a webpage or elements of CSS when there are no HTML semantic tags,  consolidated CSS classes, and/or comments.  

## Table of Contents

- [Webpage Inspection](#webpageinspection)
- [HTML Changes](#html)
- [CSS Changes](#css)
- [Test](#test)
- [Link](#link)

## Webpage Inspection

To initially determine necessary semantic tags, I opened the webpage in a browser and went into the code inspection to identify which portion of the code was associated with which visual portrayal. I determined that there was a header, navigation bar, a main with a background image, an article with three sections, an aside with three sections, and a footer (see images below). There was also an image that lay between the header and article that was part of the main content of the page. 

![The Horiseon webpage includes a navigation bar, a header image, and main portion of the page.](https://raw.githubusercontent.com/nbulger1/semantic-markup/main/assets/images/webpage-breakdown.jpg "First Half of Sectioned Horiseon Webpage")

![The Horiseon webpage includes an article with three sections and an aside with three sections as well as a footer.](https://raw.githubusercontent.com/nbulger1/semantic-markup/main/assets/images/webpage-breakdown-2.jpg "Second Half of Sectioned Horiseon Webpage") 

After boxing the portions of each page, I started by going into the HTML file to find the corresponding code to adjust the < div > tags. 

## HTML

Refer to above screenshots to see boxed portions of the webpage as I address them below. 

> **Navigation**

The initial < div > became the < header > to the entire webpage. Within the header there is an unordered list that can be defined as < nav > in place of the < div >.

> **Main**

The main content of the page started off with the background image defined by the class = "hero". I tagged that portion of the HTML < main >.

> **Article**

After the main background image, the webpage has three portions of dark blue displayed in a block fashion, each with an image and text. I tagged all three of the blocks as an < article > and each individual block as a < section >.

> **Aside**

After the < article >, the code directed the user to the light blue block on the right of the page which I tagged < aside >.This < aside > also had three distinct portions of text paired with image that I tagged it as < section >s. 

> **Footer**

Finally, the last bit of code could be refactored to < footer > as it created the footer that sat at the bottom of the page. 

## CSS

> **Issue Identification** 

The CSS file seperated out each section into it's own class with formatting even though a lot of them required the exact same CSS code. I renamed the sections that required the same formatting and consoldated the CSS file.

> **div to nav**

I adjusted the "div" formatting to reflect the switch to the < nav > tags. I also moved the formatting portions around so they were in the order in which they appear in the code to make it easier to follow in a side by side view. 

> **Article Consolidation**

For the code related to the < sections > within the < article > = "content", I consolidated the class formats into one general format chunk that applied to all three of the < sections >. I also applied the same < img > and < h2 > format to all applicable elements within the content < article >. 

> **Aside Consolidation**

Similarly, I consolidated the class formats for the benefits < aside > into one general format chunk that applied to all < sections >. I did the same for the benefits < img > and < h3 >. 

> **Comment Addition**

Finally, I went through the entire CSS file and added in comments to explain how each format section applied to the visuals on the webpage. I also added in comments to explain what each CSS property did the first time that the property appeared in the file. 

## Test

The overall goal of the refactor was to adjust the code without affecting the function of the webpage, so my go-to test was to open the page in a default browser and see if the format of the page reflected the same format in the screenshots above. 

## Link

Below is the link to the deployed application: 