Basics of HTML and CSS

- Introduction

HTML (HyperText Markup Language) is the most basic building block of the Web. It defines the meaning and structure of web content. Other technologies besides HTML are generally used to describe a web page's appearance/presentation (CSS) or functionality/behavior (JavaScript).

"Hypertext" refers to links that connect web pages to one another, either within a single website or between websites. Links are a fundamental aspect of the Web. By uploading content to the Internet and linking it to pages created by other people, you become an active participant in the World Wide Web.

- Key Components of HTML Elements

The main parts of our element are as follows:

1. The opening tag: This consists of the name of the element (in this case, p), wrapped in opening and closing angle brackets. This states where the element begins or starts to take effect — in this case where the paragraph begins.
2. The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends — in this case where the paragraph ends. Failing to add a closing tag is one of the standard beginner errors and can lead to strange results.
3. The content: This is the content of the element, which in this case, is just text.
4. The element: The opening tag, the closing tag, and the content together comprise the element.

## example of html closing and opening tags (<p>, <h1>, <h2>, etc.)

- Intro to CSS

CSS (Cascading Style Sheets) is the code that styles web content. CSS basics walks through what you need to get started. We'll answer questions like: How do I make text red? How do I make content display at a certain location in the (webpage) layout? How do I decorate my webpage with background images and colors?

Like HTML, CSS is not a programming language. It's not a markup language either. CSS is a style sheet language. CSS is what you use to selectively style HTML elements. For example, this CSS selects paragraph text, setting the color to red:

## code example of setting paragraph text to color red

- How to apply CSS to an HTML Doc

To make the code work, we still need to apply this CSS (above) to your HTML document. Otherwise, the styling won't change the appearance of the HTML. (If you haven't been following our project, pause here to read Dealing with files and HTML basics.)

1.  Open your index.html file. Paste the following line in the head (between the <head> and </head> tags):

## <link href="styles/style.css" rel="stylesheet" />

2. Save index.html and load it in your browser. You should see something like this:

## attach image link: https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics/website-screenshot-styled.png

- Survey Form Certification

FreeCodeCamp's first Certification Project for their Responsive Web Design certification was a survey form. This project focsued on the use of the <form> element. Below are key features of the <form> element.

The <input> element is the most used form element. Depending on the type (as listed below), these <input> elements can have different displays and functions.

## table shown here: https://www.w3schools.com/html/html_forms.asp

The <label> tag defines a label for many form elements and is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.

The <input type="radio"> defines a radio button. Radio buttons let a user select ONE of a limited number of choices.

## code example of radio

The <input type="checkbox"> defines a checkbox. Checkboxes let a user select ZERO or MORE options of a limited number of choices.

## code example of checkbox

The <input type="submit"> defines a button for submitting the form data to a form-handler. The form-handler is typically a file on the server with a script for processing input data. The form-handler is specified in the form's action attribute.

## code example of submit

- Tribute Page

FreeCodeCamp's second Certification Project for their Responsive Web Design certification was a tribute. This project focsued on the use of the <div> element. Below are key features of the <div> element.

The <div> tag defines a division or a section in an HTML document. The <div> tag is used as a container for HTML elements - which is then styled with CSS or manipulated with JavaScript. The <div> tag is easily styled by using the class or id attribute. Any sort of content can be put inside the <div> tag! 

- Sources

mdn web docs: html https://developer.mozilla.org/en-US/docs/Web/HTML 

mdn web docs: html basics https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics

mdn web docs: css basics https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics

w3schools: html forms https://www.w3schools.com/html/html_forms.asp

w3schools: div tag https://www.w3schools.com/tags/tag_div.ASP