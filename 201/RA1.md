# Reading

1.**Compose a short poem describing how HTTP sends data between computers.**
_HTTP is cool and if you know it you're no fool, for clients and servers it's a tool for sending and receiving things that rule. It lets your computer read CSS and Script, so that the info you need isn't skipped_ 

2.**Describe how HTML, CSS, and JS files are “parsed” in the browser.**
-The browser parses the HTML file first, and that leads to the browser recognizing any `<link>`-element references to external CSS stylesheets and any `<script>`-element references to scripts.
-As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from `<link>` elements, and any JavaScript files it has found from `<script>` elements, and from those, then parses the CSS and JavaScript.
-The browser generates an in-memory `DOM` tree from the parsed HTML, generates an in-memory `CSSOM` structure from the parsed CSS, and compiles and executes the parsed JavaScript.
-As the browser builds the `DOM` tree and applies the styles from the `CSSOM` tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.

3.**How can you find images to add to a Website?**
-To choose an image, go to Google Images and search for something suitable.
-When you find the image you want, click on the image to get an enlarged view of it.
-Right-click the image (Ctrl + click on a Mac), choose Save Image As…, and choose a safe place to save your image. Alternatively, copy the image's web address from your browser's address bar for later use.
_Note that most images on the web, including in Google Images, are copyrighted. To reduce your likelihood of violating copyright, you can use Google's license filter. Click on the Tools button, then on the resulting Usage rights option that appears below. You should choose the option Creative Commons licenses._

4.**How do you create a String vs a Number in JavaScript?**
Strings are enclosed in single or double quotes, Numbers are numerical digits with no quotes around them

5.**What is a Variable and why are they important in JavaScript?**
Variables are containers that store values. You start by declaring a variable with the let keyword, followed by the name you give to the variable. So why do we need variables? Variables are necessary to do anything interesting in programming. If values couldn't change, then you couldn't do anything dynamic, like personalize a greeting message or change an image displayed in an image gallery. 

## Introduction to HTML

**Read the beginning of Getting Started with HTML. Start from the beginning and read through section “Anatomy of an HTML document”.**

1.**What is an HTML attribute?**
Attributes contain extra information about the element that won't appear in the content. In this example, the class attribute is an identifying name used to target the element with style information.

An attribute should have:

-A space between it and the element name. (For an element with more than one attribute, the attributes should be separated by spaces too.)
-The attribute name, followed by an equal sign.
-An attribute value, wrapped with opening and closing quote marks.

2.**Describe the Anatomy of an HTMl element.**
The anatomy of our element is:

-The opening tag: This consists of the name of the element (in this example, p for paragraph), wrapped in opening and closing angle brackets. This opening tag marks where the element begins or starts to take effect. In this example, it precedes the start of the paragraph text.
-The content: This is the content of the element. In this example, it is the paragraph text.
-The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This marks where the element ends. Failing to include a closing tag is a common beginner error that can produce peculiar results.

3.**What is the Difference between `<article>` and `<section>` element tags?**
-`<article>` encloses a block of related content that makes sense on its own without the rest of the page (e.g., a single blog post).
-`<section>` is similar to `<article>`, but it is more for grouping together a single part of the page that constitutes one single piece of functionality (e.g., a mini map, or a set of article headlines and summaries), or a theme. It's considered best practice to begin each section with a heading; also note that you can break `<article>`s up into different `<section>`s, or `<section>`s up into different `<article>`s, depending on the context.

4.**What Elements does a “typical” website include?**
header: `<header>`.
navigation bar: `<nav>`.
main content: `<main>`, with various content subsections represented by `<article>`, `<section>`, and `<div>` elements.
sidebar: `<aside>`; often placed inside `<main>`.
footer: `<footer>`.

5.**How does metadata influence Search Engine Optimization?**
Specifying a description that includes keywords relating to the content of your page is useful as it has the potential to make your page appear higher in relevant searches performed in search engines (such activities are termed `Search Engine Optimization`, or `SEO`.)

6.**How is the `<meta>` HTML tag used when specifying metadata?**
Metadata is data that describes data, and HTML has an "official" way of adding metadata to a document — the `<meta>` element. Of course, the other stuff we are talking about in this article could also be thought of as metadata too. There are a lot of different types of `<meta>` elements that can be included in your page's `<head>`.

## Miscellaneous

**How to start to design a Website.**

1.**What is the first step to designing a Website?**
Project Ideation

2.**What is the most important question to answer when designing a Website?**
"What exactly do I want to accomplish?"

## Semantics.

1.**Why should you use an `<h1>` element over a `<span>` element to display a top level heading?**
Although you can style a `<span>` to look like an `<h1>` it wont have any of the extra benefits or any semantic value that comes with the `<h1>` tag.

2.**What are the benefits of using semantic tags in our HTML?**
Some of the benefits from writing semantic markup are as follows:

-Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO)
-Screen readers can use it as a signpost to help visually impaired users navigate a page
-Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes
-Suggests to the developer the type of data that will be populated
-Semantic naming mirrors proper custom element/component naming

## What is JavaScript?

1.**Describe 2 things that require JavaScript in the Browser?**
dynamically updating content and controlling multimedia on a web page

2.**How can you add JavaScript to an HTML document?`**
JavaScript is applied to your HTML page in a similar manner to CSS. Whereas CSS uses `<link>` elements to apply external stylesheets and `<style>` elements to apply internal stylesheets to HTML, JavaScript only needs one friend in the world of HTML — the `<script>` element. 



## Sources
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript
https://developer.mozilla.org/en-US/docs/Glossary/Semantics
https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Thinking_before_coding
https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML
https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure
https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started
https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/
https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics
https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like
https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works
https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/
