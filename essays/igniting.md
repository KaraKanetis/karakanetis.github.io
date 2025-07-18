---
layout: essay
type: essay
title: "Balance with Bootstrap and CSS and the Convenience"
# All dates must be YYYY-MM-DD format!
date: 2025-07-06
published: true
labels:
  - Bootstrap
  - CSS
  - Python
---
# Balance with Bootstrap and CSS and the Convenience

When I first started learning web development, I started it the same way I approach my work in astrophysics and Python: I wanted to understand everything from the ground up. Just like I’d never use a black box function in Python without knowing how it works, I didn’t want to touch UI framework until I fully understood HTML and CSS.

But after spending so much time writing CSS just to make a simple webpage responsive, I realized something: there’s a difference between learning the fundamentals and refusing to use tools that make your life easier. In astrophysics, I don’t hand code every single data analysis function, I use libraries like NumPy, SciPy, and Astropy to speed things up. Which I should have realised is the same with web development. 

## Why Bootstrap Makes Sense

Bootstrap 5 felt like the NumPy of web design. Instead of spending forever fine tuning everything, I could use Bootstrap’s grid system to build a clean, responsive layout much faster. But what I appreciated most was how Bootstrap didn’t lock me into anything I still used custom CSS to style things the way I wanted, but Bootstrap handled the repetitive layout work that would have taken me hours.

This balanced approach where I could let Bootstrap handle the base structure while I worked on the details, reminded me of how I use Python in my research. I might use a library function to solve an equation, but I still write my own code to process the results and generate the plots. In both cases, I’m not giving up control; I’m just choosing where to focus my effort.

## Bootstrap Example

To see what I mean, here’s a simple example from one of my practice projects. Let’s say I wanted to display some basic asteroid data alongside my observation notes. With plain HTML and CSS, I would need to write a flexbox layout, media queries for responsiveness, and a bunch of CSS rules. But with Bootstrap, I can create a clean, responsive two column layout with just a few classes:
```html
<div class="container">
  <div class="row">
    <div class="col-md-6">
      <h2>Asteroid Data</h2>
      <p>Name: 433 Eros</p>
      <p>Orbit: 1.458 AU</p>
    </div>
    <div class="col-md-6">
      <h2>Observation Notes</h2>
      <p>Visible in infrared wavelengths. Potential mission target.</p>
    </div>
  </div>
</div>
```

That’s it. No flexbox issues, no media queries. Bootstrap automatically makes the layout responsive and on a small screen, these two columns will stack vertically.

If I wanted to do the same thing using raw CSS, the code would be much longer and harder to maintain:
```html
<div class="container">
  <div class="left-column">
    <h2>Asteroid Data</h2>
    <p>Name: 433 Eros</p>
    <p>Orbit: 1.458 AU</p>
  </div>
  <div class="right-column">
    <h2>Observation Notes</h2>
    <p>Visible in infrared wavelengths. Potential mission target.</p>
  </div>
</div>
```
```html
.container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
.left-column, .right-column {
  width: 48%;
}
@media (max-width: 768px) {
  .left-column, .right-column {
    width: 100%;
  }
}
```
Both work, but one takes a few lines of Bootstrap, and the other takes several lines of custom CSS. It’s the same reason I use libraries like NumPy in Python instead of coding every calculation from scratch.

## Learning Curve

Bootstrap wasn’t effortless to learn. I had to memorize class names like col-md-6 and mt-3, and at first, I constantly checked the documentation. But it got easier over the week, especially once I started recognizing patterns. After a few tries, I could build a basic page layout without Googling every step.

Looking at other students' projects, I saw how Bootstrap could help create polished, professional looking sites quickly. That made me to try applying Bootstrap to my own practice projects, and I could immediately tell that my websites looked cleaner and worked better on mobile.

## My Takeaway

In the end, Bootstrap didn’t replace my HTML and CSS knowledge, it built on it. Just like I wouldn’t use Python without understanding the underlying math, I wouldn’t rely on Bootstrap without knowing how to style a webpage manually. But for larger projects, or when I’m short on time, Bootstrap helps me work smarter, not harder.

If you’re thinking of learning a UI framework but are worried about losing creative freedom, don’t be. Bootstrap isn’t about limiting your options; it’s about giving you a solid foundation to build on. Whether I’m simulating asteroid impacts or building a website, I’ve learned that the right tools help you spend less time reinventing the wheel—and more time creating something meaningful.

