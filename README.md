# A Responsive Fintech Website: "FinBase"

## Content :link:
1. [Project Overview](#1-project-overview-😄)
2. [Screenshots](#2-screenshots-📷)
3. [Why I built this](#3-why-i-built-this-❓)
4. [what I learned building this project.](#4-what-i-learned-while-building-this-project)
5. [Challenges](#5-challenges-😓)
6. [Tools and resources utilized](#6-tools-and-resources-utilized-🔧)
7. [Author](#7-author-🖊️)


## 1. Project Overview: :smile:
Hey guys, this project is a website designed for a fictional Fintech company "FinBase". This website is primarily an informative platform where the company's range products and services  are showcased in vibrant colour. It consists of a Visually appealing homepage and an FAQ page, which includes a convenient email input box for user inquiries.

***

Check it out [here](https://finbase.netlify.app)

***

## 2. Screenshots :camera:

#### Screenshot 1
![reference image](/img/FinBase%20Website-homepage-full.png)
*A screenshot of the Homepage*


#### Screenshot 1
![reference image](/img/FinBase%20Website-FAQ%20Page.png)
*A screenshot of the FAQ page*



## 3. Why I built this :question:
The aim of this project was to Push the limits of my understanding of **Responsive Design** and the **Mobile-first** methodology by leveraging on the capabilities of Flexbox  layout and its associated properties, the `position` and `Transform` properties, CSS **Media Queries** and other responsive design techniques.  
 
My ultimate aim here was to design a website that maintains its visual appeal on both large screens and smaller screens (Mobile devices).

## 4. What I learned while building this Project

- Not every element on a webpage needs a specific height since elements will naturally expand to accommodate their content.

- I became proficient in employing the `order` property. To ensure its functionality, it's essential that parent elements have their `display` property set to `flex`. Within the `.flex-items` class, those with lower `order` values will be positioned ahead of others. It's worth noting that even negative values can be used as valid inputs for the `order` property.

- I discovered a way to maintain consistent width for the main content across all sections of my webpage. I achieved this by creating a reusable `.container` class and applying it to all sections, setting specific `width` and `max-width` properties to ensure uniformity throughout.

- I gained an understanding of the significance of incorporating `comments` into code and how they contribute to its readability and long-term maintainability.

- The mobile-first approach streamlines code by initially focusing on smaller screens and subsequently making layout adjustments through relatively fewer lines of code in **Media Queries**. This method reduces the overall codebase because you build the core structure with compact screens in mind, adding complexity only as needed for larger screens.

-  I learned how to make cool buttons with pictures inside them using something called `inline-flex`.



## 5. Challenges: :sweat:
During this project, I faced a few tough challenges that left me scratching my head. However, I managed to overcome them by doing some research and turning to Google for solutions. Here are a few of the tricky ones.

- I struggled to align my image icons with the button text on the same line. I experimented with flexbox, padding, and margins, but none of it worked. After some thorough searching on Google, I discovered the `inline-flex` property, which finally solved the issue for me.

```css
.hero-btn {
    padding: 12px;
    border-radius: 10px; 
    width: 80%;
    background-color: #f8f8f8;
    border: 1px solid #c0bbbb;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
    
}
```
- Another challenge I faced in development was related to the `display: flex;` property I had set on the modifier class `.container`, which was meant to maintain consistent width for the main section of my webpage. However, this caused style issues in other sections within the main section. To fix this, I made adjustments by applying only the essential layout style rules to the `.container` element.

```css
.container {
    width: 95%;
    max-width: 1200px;
    margin: 0 auto; 
}
```
## 6. Tools and resources utilized :wrench:

In the course of building this project, I made use of the following tools and resources;
- HTML5 
- CSS
- Colour palette from[ coolors.com](https://www.coolors.co/) :link:
- Images from[ icon8.com](https://www.icons8.com/) :link:
- Resources from [freeCodeCamp.org](https://www.freecodecamp.org/) :link:
- Resources from [scrimba.com](https://www.scrimba.com)

## 7. Author :pen:
 
Hi everyone! I'm Benedict, learning web development to become a frontend developer. Check out my blog for learning experiences, projects, and tips. Follow me on Twitter too! 
kindly click on the links below. Thanks!

- Follow me on [Twitter](https://twitter.com/CodewithNtaji) :link:
- Checkout my blog on [Hashnode](https://benneythedev.hashnode.dev/) :book:
