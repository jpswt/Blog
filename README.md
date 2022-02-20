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
      <link rel="stylesheet" href="styles.css">
  
  -----
  
  Blog 16
  
  


