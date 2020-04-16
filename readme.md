# Rails by Odin:
  * In this Readme, I include notes or things that I would like to recall at a glance in the future. By all means, anyone reading this should absolutely do the [Odin Rails Project](https://www.theodinproject.com/) to get the full experience.
  * The Readme is broken down into sections based on how Odin proceeds with its tutorials.

### Basics (Skipped)

### Installations (Skipped)

### Git Basics (Skipped)

### The Front End [[Link to Odin Lesson](https://www.theodinproject.com/courses/web-development-101/lessons/introduction-to-the-front-end)]
  * The FrontEnd usually consists of at least 3 things:
    * How its structured (HTML)
    * How it looks (CSS)
    * How it functions (Javascript)
  * Read: [What is Front-End Web Development](https://generalassemb.ly/blog/what-is-front-end-web-development/)
  * Read: [The role of HTML](http://webapps-for-beginners.rubymonstas.org/html.html)

### Web Development 101 - HTML & CSS [[Odin Lesson](https://www.theodinproject.com/courses/web-development-101/lessons/html-and-css-basics)]
  * Odin Questions, My Answers:
    * Why do we separate HTML and CSS?
      * HTML dictates the structure of the webpage, whereas CSS dictates how it looks and minor alterations to the structure.
    * What are classes and IDs (and how are they different)?
      * An Id is regarded as a singluar identifier for an element in HTML. There should only be ONE of any Id.
      * A Class is applied to similiar objects to receive the same styling via CSS. If the styling is used on more than one object, then the object should use a class.
    * What are elements?
      * Every tag in HTMl is considered an element. Ids and classes help to make these elements more specific when styling them.
    * What are tags?
      * Tags are built in standards within HTML that provide basic functionality and styling to elements. (Such as `<a></a>` or `<div></div>`)
    * What are attributes?
      * Attributes provide additional information about HTML elements. 
      * For example, an `<a></a>` tag might also include  `href=""` to specify a page it will take the user to when selected.  
    * What are forms?
      * Forms collect user information in a standard and familiar way.
    * What is a div?
      * A div is usually used as a container by other elements, such as lists (`ul` or `li`).
    * What are selectors?
      * A Selector is anything that can be styled, such as a class, element or tag.
    * What are properties?
      * A property is additional information included when the DOM is generated that is not provided by the coder.
    * What are values?
      * Values are the default input for forms, buttons and such.
    * What is the “query string” in a URL and what does it do?
      * The Query String in a URL is represented by a `?`, and all parameters are included in the URL afterwards.
    * What is the difference between “pixels” and “ems”?
      * When styling, pixels offer EXACT measurements for emements, whereas ems offer semi-automatic scalability.
    * How do CSS styles for a particular element get inherited? i.e. how does an  element get its “default” styles?
      * Child elements inherit stylings from their Parent element, which creates their specific defualt styling.
    * What are two CSS attributes you can change to push an element around on the page?
      * Margin and Padding.
    * What are the three different ways to include CSS in your project or use CSS to style a particular element?
      * Inline Styling (styling added directly to the element)
      * External Styling (`.css` Stylesheets)
      * Internal Styling (CSS rules in the `<head></head> tag of your HTML)
    * What is the “default stylesheet” or “user agent stylesheet”?
      * "Default Stlying" includes the CSS standard spacing, margins, and so on which can cause issues when operating on different browsers and devices.
      * "User Agent Stylesheets" references a 'reset' CSS to give all devices a close-to-level playing field.
    * Why use a CSS reset file?
      * See above.
  * Complete: [Free Code Camps Responsive Web Design Certification](https://www.freecodecamp.org/learn/)

### Web Development 101 - Developer Tools [[Odin Lesson](https://www.theodinproject.com/courses/web-development-101/lessons/developer-tools)]
  * Watch: [Chome Developer Tools (DevTools)](https://www.youtube.com/watch?v=wcFnnxfA70g).
  * Watch: [Chome Devtools for CSS](https://www.youtube.com/watch?v=Z3HGJsNLQ1E) (Ignore anything about bootstrap for now).

### __________ [[Odin Lesson](__________)]
  * 
  * 
  * 
  * 
  * 

### __________ [[Odin Lesson](__________)]
  * 
  * 
  * 
  * 
  * 

### __________ [[Odin Lesson](__________)]
  * 
  * 
  * 
  * 
  * 

### __________ [[Odin Lesson](__________)]
  * 
  * 
  * 
  * 
  * 

### __________ [[Odin Lesson](__________)]
  * 
  * 
  * 
  * 
  * 













































### The DOM (Document Object Model)
  * The DOM is any and all HTML objects on a webpage I.E.
  ```
  <div id="container">
    <div class="display"></div>
    <div class="controls"></div>
  </div>
  ```
  * Nodes are represented as each individual object (such as a `div`, or a `p`) and are identified by an `id` or a `class`.
  * When a node contains other nodes, it becomes a _parent node_ (The `div` with the `id="container"`), while the contained nodes become _child nodes_ (The other `div`s with `class="display"` & `class="controls"`)
  * 
  * 
  * 
  * 