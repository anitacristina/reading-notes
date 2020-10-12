# Design Webpages with CSS

This page reflects my understanding of Chapter 10 and 11 from the book “HTML & CSS” by Duckett

CSS stands for **C**ascading **S**tyle **S**heets.It is the language that helps you to style an HTML document



## CHAPTER 10- INTRODUCING CSS

Below are the three ways of inserting the information in the style sheet

**External CSS** : External style sheets are defined within the <link> element inside the head section. It should use three attributes (href,type and rel).This method is preferred if all the HTML pages required same style sheet. _Example:_ ```<link rel = "stylesheet"  type = "text/css" href = "myStyle.css" />```

**Internal CSS** : The internal style sheet is  defined inside the ``<style>`` element, inside the head section of the HTML page. _Example:_ ```<style> body { background-color: linen;} </style>```
  
**Embedded/Inline CSS** : An inline style is used to apply a unique style for a single element. _Example:_ ```<h1 style="color:blue;text-align:center;">This is a heading</h1>```

### Types of CSS Selector

CSS selectors are case sensitive and they are used to stye the HTML elements. There are many different types of CSS selectors, but below are one that was described in Chapter 10

**UNIVERSAL SELECTOR** - `*{}` Targets all the elements of the HTML page.

**TYPE SELECTOR** - ``` h1, h2, h3 { }``` Targets all the elements of the given type within a HTML page.

**CLASS SELCTOR** - ```.anita {}``` Targets the elements based on the contents of their class attribute. `p.anita { }` - Targets only <p> elements whose class attribute has a value of note. Class selector is specified by .(period) symbol.
  
**ID SELECTOR** - ``#anita { } `` Targets  the elements whose id attribute has a value of anita. ID selector is specified by # symbol.

**CHILD SELECTOR**  `li>a {}` Targets any **a** elements that are children of an <li> element. It is specified by > symbol.
  
**DESCENDANT SELECTOR** ``p a {}`` Targets any <a> elements that sit inside a <p> element, even if there are other elements nesteed between them.
  
**ADJACENT SIBLING SELECTOR** ``h1+p {}`` Targets the  first <p> element after any <h1> element, but not any other <p> element. This is specified by + symbol
  
**GENERAL SIBLING SELECTOR** ``h1~p {}``Targets all the <p> elements that are sibling of an <h1> element. This is specified by ~ symbol.
  
   **Note**: If the two selectors are identical, the latter will take precedence or priority.

## CHAPTER 11- COLOR

The color gives life to the HTML pages. The color property allows you to specify the color of the text inside an element. There are three ways to set the color in CSS for both background and foreground. 1) RGB Values, 2) Hex Code & 3) Color Names

**RGB VALUES** - RBG stands for Red, Blue and Green. The values for red, blue and green are expressed as numbers between 0 and 255. ``rgb(102, 205, 170)``

**HEX CODE** - Hex values represent values for red, green and blue in hexadecimal code. The hexa decimal value for 102 -> 66, 205 -> cd and 170 -> aa. ``#66cdaa``

**COLOR NAMES** - Colors are represented by the predefined names.There are 147 predefined color names that are recogined by browsers. ``Red``

**HSL & HSLA** - The HSL and HSLA color property has been introduced in CSS3 as an **alternate way to specify colors.** The HSLA stands for HUE, SATURATION , LIGHTNESS and ALPHA. The value of the property starts with the letters hsl or hsla followed by individual values inside parentheses.  ``{background-color: hsla (0, 100%, 100%, 0.5);}``




## My Learnings from DeltaV Code 102
- [Home](README.md)
- [Growth Mindset](GROWTH_MINDSET.md)
- [Learning Markdown](LEARNING_MARKDOWN.md)
- [Coder's Computer](CODERS_COMPUTER.md)
- [Revision Cloud ACP](REVISION_CLOUD.md)
- [Structure Webpages](STRUCTURE_WEBPAGES.md)
- [Design Webpages with CSS](DESIGN_WEBPAGES_CSS.md)
- [Dynamic Webpages with JS](DYNAMIC_WEBPAGES_JS.md)
- [Computer Architecture and Logic](COMPUTER_ARCHI_LOGIC.md)
- [Programming with JS](PROGRAMMING_WITH_JAVASCRIPT.md)
- [MORE TO COME]...
