# Midterm Exam Review

## I. Format
- multiple choice
- true/false
- short answer
- short "write some code" questions.
    - HTML/CSS
    - JavaScript

## II. Topics Covered
Everything we have covered in class or in HW assignments this semester is fair game. Be sure to focus on the following:
Below are some example questions - **these are not exhaustive of what can and will appear on the exam**:

## A. HTTP Protocol
1. Who (the client or the server) sends *request headers*?
1. Who (the client or the server) sends *response headers*?
1. Who (the client or the server) sends *status codes*?
1. What does the **403** status code mean?
1. What does the **404** status code mean?
1. Why is the **HOST** request header required?
1. Who (the client? the server? both?) can send text and/or images?
1. Give two ways to verify that we have successfully "turned off" banjo's PageSpeed module.
1. How many .htaccess files can you have in a single folder?
1. Suppose you upload a .htaccess file containing directives into your `www` folder. Which folder(s) would be affected by the file?
1. Also see HTTP protocol notes and questions here: [http-protocol-intro.md](https://github.com/tonethar/IGME-230-Master/blob/master/notes/http-protocol-intro.md)
1. Also see HTTP demo notes here: [http-protocol-demo.md](https://github.com/tonethar/IGME-230-Master/blob/master/notes/http-protocol-demo.md)

## B. FTP
1. Give the name (address) of the `http://people.rit.edu` web server (that you FTP files to).
1. What are the numeric permissions that are required for web viewable *directories*?
1. What are the numeric permissions that are required for web viewable *files*?

## C. Intro To Web
1. Describe the 4 *layers* (or *pillars*) of web design.
1. What language do we use to add *structure* to a web page?
1. Which layer of web design is responsible for how web pages look?
1. How can we add *behavior* to a web page?


## D. Basic HTML
1. See the [IIM review folder](https://github.com/tonethar/IGME-230-GDD-2017-Fall/tree/master/IIM-Web-Review)
1. Give examples of HTML *semantic* elements (tags)
1. Give examples of HTML5 *Structural* elements
1. Give examples of *standalone* (or empty) elements
1. Give examples of *container* (or non-empty) elements
1. Give an example of an *absolute* file path
1. Give an example of a *relative* file path
1. <s>What kind of content are HTML tables appropriate for?</s>


## E. Basic CSS
For the exam, be able to write complete CSS rules from memory.

1. What does CSS stand for?
1. Give an example of a CSS `type` selector.
1. Give an example of a CSS `class` selector.
1. Give an example of a CSS `id` selector.
1. Give an an example of a style rule that utilizes the CSS `universal` selector?
1. Give an example of a CSS `descendant` selector (aka descendant combinator)
1. What does `display:block` do?
1. What does `display:inline` do?
1. What does `display:inline-block` do?
1. What does `display:flex` do?
1. What does `display:grid` do?
1. What does `float:left` do?
1. What CSS rules causes the element it's applied upon to show below a floated elment?
1. Define `inline`, `internal`, and `external` style sheets.
1. If these 3 types of styles conflict, which one usually "wins"?
1. Imagine we write a CSS rule that effects the `color` of elements in the &lt;body> tag - which elements on the page will *inherit* the value of this property? 
1. Which CSS properties are commonly NOT inherited?
1. How large is a CSS *point* unit?
1. How large is a CSS *pixel* unit?
1. How large is an CSS *em* unit?
1. How large is an CSS *ex* unit?
1. Specify the CSS colors red, green, blue, black, and white in hexadecimal notation.
1. Why is it a good idea to specify more than 1 font name in your CSS `font` rules?
1. <s>Once you set `position:absolute`, what are the other two CSS properties you will usually need to set?</s>
1. <s>What is the CSS property used to set the stacking order of HTML elements?</s>
1. Describe the CSS box model.
1. Describe the difference between `margin` and `padding`.
1. Give at least 3 properties of the "box" that we can set (other than margin and padding).
1. What is the HTML tag used to connect to an external CSS file or an embedded font?
1. What is the CSS property we use to define whether/how quickly a property will animate when changed?
1. Be familiar with the [box model and advanced CSS selectors shown here](../weekly/week-02B-notes.md)

## F. More CSS Layout / Flexbox / Grid
1. How do block elements align themselves with each other in the normal flow of an HTML page?
1. In contrast, how do inline elements behave?
1. What CSS property can be changed to make inline elements behave like blocks and vice-versa?
1. What elements are affected when `display:flex` or `display:grid` is applied to a container element?  ie: which elements become "items" in that layout system?
1. Know the basic functionality of `flex-direction`, `align-items`, `justify-content`
1. What does `flex-wrap` allow to happen?
1. How do you use `grid-template-rows` and `grid-template-columns` to divide your page?
1. If you define element names with `grid-area`, what do you use to define what named sections go where in your layout?
1. How do you make a section of CSS apply only at certain screen widths?

## G. CSS Rollovers
1. Give the 4 CSS `pseudo selectors` that are used to create CSS rollover effects.
1. What CSS property defines when and how a numeric element property can change over time?  (ie: simple animation, but we aren't talking about the "animation" property)

## H. Markdown
1. Know the basic Markdown syntax (headings, lists, etc)

## I. Web Publishing
1. When to use *serif*, *sans-serif*, and *decorative* fonts
1. What image file format(s) should generally be used for photographs?
1. What image file format(s) should generally be used for web graphics such as logos and banners?
1. What are the 2 questions every navigation system should answer?
1. What does CRAP stand for?
1. Give a short summary of each CRAP principle
1. What does the "above the fold" design principle mean?
1. Define *Responsive Design*
1. What is the `name` of the &lt;meta> tag you will need to add to all of your responsive (and mobile friendly) web pages?
1. What properties of the browser does a media query commonly "test" for?

## J. Website Design Process
1. See [Week 5 Notes](https://github.com/dccircuit/IGME-230-Spring-2019/blob/master/weekly/week-05A-notes.md)

## K. PHP
- See review questions for all 4 PHP chapters: [About this PHP Tutorial Series](https://github.com/tonethar/IGME-230-Master/blob/master/notes/php-0.md)
1. Know the difference between push, pop, shift, and unshift as it relates to manipulating arrays
1. Know how a variable is represented in PHP
1. Be able to identify the `$_SERVER` super global.
1. Understand the purpose of the `strip_tags()` function as it relates to user-generated input.
1. Understand that PHP code should never appear in a browser and why.
1. Know about `phpinfo()`

## L. Frameworks and Libraries
1. Understand what Bootstrap is and what it's useful for.
1. Understand what jQuery is and what it's useful for.

## M. Introduction to Web Applications
For the midterm exam, you will be responsible for the first 5 parts of this web apps series:

1. [Introduction to Web Applications](https://github.com/tonethar/IGME-230-Master/blob/master/notes/web-apps-1.md)
2. [Introduction to JavaScript](https://github.com/tonethar/IGME-230-Master/blob/master/notes/web-apps-2.md)
3. [Introduction to the Web Browser DOM](https://github.com/tonethar/IGME-230-Master/blob/master/notes/web-apps-3.md)
4. [More Web Browser DOM Methods](https://github.com/tonethar/IGME-230-Master/blob/master/notes/web-apps-4.md)
5. <s>[JavaScript Functions](https://github.com/tonethar/IGME-230-Master/blob/master/notes/web-apps-5.md)</s>


- **Be sure to focus on the Discussion/Review sections and their questions for each of the <s>5</s>(4!) above pages!**
- **Be able to write some JavaScript from memory!**

You can access all of these web app tutorial pages from here: 
[https://github.com/tonethar/IGME-230-Master/blob/master/notes/web-apps-0.md](https://github.com/tonethar/IGME-230-Master/blob/master/notes/web-apps-0.md)


## N. Sample *short answer* questions

1. Write JavaScript that loops through the `foods` array and produces the HTML necessary for an unordered list containing the array’s contents.


- carrots
- broccoli
- tofu

```js
let foods = ["carrots","broccoli","tofu"];

// you write the rest


```

2. Write a CSS style rule that makes all hypertext links gray in color, with a left margin equal to 2 ems, and a font size of 15 pixels.


3. List the 4 "CRAP" design principles and a rule of thumb for each.


4. Write a complete PHP program that will print out the string "Hello World".
