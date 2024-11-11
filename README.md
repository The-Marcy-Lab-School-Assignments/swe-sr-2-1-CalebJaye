# Technical Writing Assignment

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/fullstack-curriculum/how-tos/working-with-assignments#how-to-work-on-assignments).

## Prompt 1

Do some research on semantic and non-semantic elements and share your findings. Your response should include:
* Examples of semantic and non-semantic tags
* The differences between semantic and non-semantic tags
* The benefits of using semantic tags (when possible)

Semantic elements are elements with meaning. Semantic elements are useful because they tell how the content inside them is supposed to behave, as well as the fact that they have specific attributes for their structure. Some examples of semantic elements are 'header', 'main', and 'nav'. Non semantic elements are unlike semantic elements in the fact that they don't have meaning. Non semantic elements don't tell how the content inside them is supposed to behave. Some examples of non semantic elements are 'div' and 'span'.

## Prompt 2

Do some research on accessibility. What are some ways to make your website more accessible? Explain why it is important for developers to create websites that meet accessibility standards.

In order to make your website more accessible, you can make your fonts and text easier to read, as well as make navigation easy and seamless. It is important for developers to create websites that meet accessibility standards as it encourages people to use your website more, makes it easier to understand, and provides a better experience for all.

## Prompt 3

It is possible to add "inline" CSS styles to our html elements using the `style` attribute like so:

```html
<p style="color: red;" >hello world</p>
```

While this is possible, it is a best practice to instead write styles in a separate CSS file. Provide at least one argument for why it _might_ be considered useful to write inline styles, and then provide a more compelling argument for writing styles in a separate CSS file.

It might be useful to write inline styles as it is convenient and easy to implement. However, it is better to write styles in a separate CSS file as it makes everything more organized and easier to read.

## Prompt 4

Imagine you are teaching a brand new programmer a brief lesson about the `class` and `id` attributes in HTML as well as how to use them to style elements using CSS. Your lesson should have the following components:

* An explanation of the concept of "classes" and "ids" with an analogy.
* An example of the usage using an HTML code block and a CSS code block.
* An explanation of the syntax using the terms: **attribute**, **selector** 

Classes in html are like groups that let any element the class is applied to know how to change the style of the text.
Id's are used to tell specific lines of text how to style them.

```html
.banana {
    color: red
    margin: 30px
}
<head>
<body="banana">
Hello Guys! Check out this cat!
<img 
  src="https://http.cat/images/415.jpg" 
  alt="cat eating a record" 
/>
</body>
    </head>
```
Using the .banana selector, I would have turned "Hello Guys! Check out this chat!" red and made the text 30px. The img and alt attribute adds on an image and text as well.
## Prompt 5

The Document Object Model (DOM) API provides functions for manipulating HTML documents. It is possible to build an entire website using only JavaScript and the DOM API, however is that the best practice?

When building a website, how can I decide which content I should write using HTML/CSS and which content I should create using the JavaScript and the DOM API?

You can decide whether to use HTML/CSS or JavaScript and the DOM API by whether or not you are going to change the style of your element. If so, use JavaScript and the DOM API.

