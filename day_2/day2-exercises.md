# Chapters 3 and 4 Questions:

1. There are three main types of lists in HTML: ordered, unordered, and definition. What are their differences?

* Ordered lists are numbered
* Unordered lists are bullet pointed
* Definition lists contain terms and their definitions

2. What is the basic structure of an element used to link to another website?

<a href="websiteURL">LinkTitle</a>

3. What attribute should you include in a link to open a new tab when the link is clicked?

target="_blank"

4. How do you link to a specific part of the same page?

In the href, rather than using a URL you use a # and the id attribute of the element that you want to link to. Example:
<a href="#top"> Links to the top of the page whose is attribute has a value of top.

# Chapters 10, 11, and 12 Questions:

1. The purpose of CSS is to add visual design to your webpages

2. CSS stands for Cascading Style Sheets. "Cascading" refers to the way that rules are applied as you move down the sheet. Earlier rules are superceded by ones that come later, and more specific rules take precedence over more general ones. In this way you can write general style rules that have some exceptions.

3. What is the basic structure of a CSS rule?

Each css declaration is inside curly brackets and is made up of a property and a value, which are separated by a colon

4. How do you link a CSS stylesheet to your HTML document?

Inside the head element of the HTMl page, you have a <link> element that tells the browser where to find the CSS file. The <link> element needs three attributes: href, type (text/css), rel (stylesheet)

5. When is it useful to use external stylesheets as opposed to using interal CSS?

You should use an external stylesheet when you build a site that has more than one page. This allows each page to have the same style rules without having to repeat them, and makes it easier to make changes that apply across all pages.

6. Describe what a color hex code is.

A hex code is a # followed by 6 digits that denotes how much red, green, and blue is present in a specific color.

7. What are the three parts of an HSL color property?

Hue, saturation (the amount of grey in a color), lightness (the amount of white/black in a color)

8. In the world of typeface, what are the three main categories of fonts? What are the differences between them?

Serifs, which have extra details on the ends of the main strokes of letters. Sans-serifs don't have any extra details- they have clean ends to letters. Monospace fonts have an equal amount of space between all strokes and every character.

9. When specifiying font-size, what are the main three units used?

Pixels, percentages, and EMS
