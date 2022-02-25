# Class 12 Prompts

## What's the difference between and HTML Element and and HTML Tag?

Let's say we have the example of:  `<h1>Hello World</h1>`.    
The HTML Tags are just the starting and end tags of `<h1></h1>`, while the HTML element is the tags plus its content `<h1>Hello World</h1>` 



## Explain, to someone you know, the 3 ways to link/use CSS in an HTML file to style a web page.

Let's say I want to style a paragraph to have a font color of green, this can be done in the following ways:

  a. It can be linked inline within the html code using the `<style>` attribute.  An example would be:
      `<p style="color:green">A red paragraph.</p>`
  
  b. It can be linked internally using a `<style>` element in the `<head>` section:
`       <head>      
           <style>
              p {color: green;}
           </style>
        </head>`
  
  C. It can be linked externally via an .css stylesheet:
      `<link rel="stylesheet" href="styles.css">`
  
  -----
# Class 16 Prompts

## Why is it generally a good idea to position CSS `<link>`s between `<head></head>` and JS `<script>`s, just before `</body>`? Do you know of any exceptions?

When the page loads, it load top to bottom and line by line.  When placing the css links between the head, it allows to the html to be rendered and styled at the same time.  If the css links are placed just before the `</body>` tag, only the bare html would be loaded and rendered.  Then the a second render would occur, applying all the style changes from the css.  This would cause a lot of noise and layout changes as the page renders a second time.  Optimally it is best to place css between the  `<head></head>` to avoid this second render.
