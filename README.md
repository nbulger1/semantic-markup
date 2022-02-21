# Semantic Markup - Week 1 Homework

## Description

The following assignment was created under the premise that web **accessibility** is of utmost importance not only for increasing search engine ranking but also for people with disabilities. It is extremely important that people with disabilities can use a website through a variety of assistive technologies including video captions and screen readers.

I was provided with an HTML code file that led to a fully functional webpage. While the code worked to populate a webpage, the file lacked semantic markup and the CSS file needed some reformatting and consolidating to promote accessibility. 

By working through the code, I was able to experience the difficulty of locating different portions of a webpage or elements of CSS when there are no HTML semantic tags or consolidated CSS classes and ids. 

Provide a short description explaining the what, why, and how of your project. Use the following questions as a guide:

- What was your motivation?
- Why did you build this project? (Note: the answer is not "Because it was a homework assignment.")
- What problem does it solve?
- What did you learn?

## Table of Contents (Optional)

If your README is long, add a table of contents to make it easy for users to find what they need.

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Adjustments to HTML

To approach the HTML semantics, I opened the webpage in the default browser and went into the code inspect to identify which portion of the code was associated with which visual portrayal. 

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](/Users/natalie/Desktop/school_work/homework/semantic-markup/assets/images/Webpage Breakdown.png)

(/Users/natalie/Desktop/school_work/homework/semantic-markup/assets/images/Webpage Breakdown Part 2.png) 

The initial <div> on line 11 became the <header> to the entire webpage. Within the header there is an unordered list that can be defined as <nav> in place of the <div> on line 13.

Once past the header and navigation bar, the first chunk of code, from lines 30-52, contained all three sections of dark blue blocking on the webpage, thus it could be termed an <article> along with three <section> tags. 

The next chunk of code, from lines 53-75 created the light blue block on the right side of the webpage that appeared more like an <aside> and thus I tagged it as such with three <section>s. 

Finally, the last bit of code, from lines 76-81, could be refactored to <footer> as it created the footer that sat at the bottom of the page. 

## Adjustments to CSS

The CSS file seperated out each section into it's own class even though a lot of them required the exact same formatting.  


## Installation

What are the steps required to install your project? Provide a step-by-step description of how to get the development environment running.

## Usage

Provide instructions and examples for use. Include screenshots as needed.

To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative filepath, add it to your README using the following syntax:

    ```md
    ![alt text](assets/images/screenshot.png)
    ```

## Credits

List your collaborators, if any, with links to their GitHub profiles.

If you used any third-party assets that require attribution, list the creators with links to their primary web presence in this section.

If you followed tutorials, include links to those here as well.

## License

The last section of a high-quality README file is the license. This lets other developers know what they can and cannot do with your project. If you need help choosing a license, refer to [https://choosealicense.com/](https://choosealicense.com/).

---

🏆 The previous sections are the bare minimum, and your project will ultimately determine the content of this document. You might also want to consider adding the following sections.

## Badges

![badmath](https://img.shields.io/github/languages/top/lernantino/badmath)

Badges aren't necessary, per se, but they demonstrate street cred. Badges let other developers know that you know what you're doing. Check out the badges hosted by [shields.io](https://shields.io/). You may not understand what they all represent now, but you will in time.

## Features

If your project has a lot of features, list them here.

## How to Contribute

If you created an application or package and would like other developers to contribute it, you can include guidelines for how to do so. The [Contributor Covenant](https://www.contributor-covenant.org/) is an industry standard, but you can always write your own if you'd prefer.

## Tests

Go the extra mile and write tests for your application. Then provide examples on how to run them here.