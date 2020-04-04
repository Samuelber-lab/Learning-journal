# Chapter 10
## Introducing CSS
While getting introduced with CSS, it is important to imagine that there is an invisible box around every HTML element. Therein, CSS will allow the wed author to create rules that govern the way that each individual box and its enclosed content is presented. CSS works by associating rules with HTML elements, which controls how the contents of specified elements should be displayed. A CSS rule contains two parts: a <span style="color: blue;"> ***selector*** </span> and <span style="color: red;"> ***declaration*** </span>.
<span style="color: blue;"> ***Selectors*** </span> tells or directs which part of the page window or in other words, which element, (i.e., heading: `<h><h>`, paragraph: `<p>,<p>`, etc) the change should be applied to. The same rule can be applied to multiple elements. 
<span style="color: red;"> ***Declaration*** </span> on the other hand how the element referrred to in the selector should be styled. It is divided into two parts, namely <ins> property </ins> and <ins> value </ins>. These are separated by colon. A CSS declaration sit inside a curly brackets and each is made up of two parts: a **propery** and **value**. Several **properties** can be specified in declaration, where each separated by semi-colon. An illustration for how this looks like: 

h1, h2, h3 {<span style="color: red;"> font family: </span> <span style="color: green;"> Arial; </span> <span style="color: red;"> Color: </span> <span style="color: green;"> Purple; </span>} 

Hence, in the above example, all the red colored are "properties" and green colored ones are "values". 

# Chapter 11
## Color
The color property allows the web author to specify the color of the text inside an element. In the CSS, the color can be specified in on of the three ways: 
- **RGB value**: this is expressed in terms of the proportion of the constuent parental colors, i.e., red, green and blue, forming the resulting color. For example: rgb(100.100.90)
- **HEX codes**: these are six-digit codes that represent the amount of red, gree and blue in a color preceded by a hash or pound `#` sign. For example: #ee3e80
- **Color names**: There are 147 predefined color names that are recognized by browsers. For example: Blue
