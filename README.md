# Colorstack Fall 25 Intro to HTML & CSS

Hello everyone, and welcome to Colorstack's first workshop of the Fall '25 semester!

Today we will be going over HTML and CSS.

Please feel free to fork this Github Repository, 
  to follow along with the lesson, you'll need:
  - VS Code
  - Live Server VS Code extension

Let's begin!

## Intro to Front end Web Dev
  main responsibility is to create and polish things that the user sees.
  
  basic languages include: html, css, and javascript

## HTML - Hyper Text Markup Language
  standard markup language for creating web pages

  describes the structure of a web page

  consists of series of elements that tell the browser (Chrome, Edge, Firefox, Safari, etc.) how to display the content
  - "this is a heading", "this is a paragraph", "this is a link", etc.

  ### What is an HTML Element?
    defined by a start tag, some content, and an end tag.

    <tagname>Content goes here...</tagname>

    empty elements: some HTML elements have no content, like <br>. these elements do not have an end tag!

    ![screenshot](assets\images\html_structure.png)

    #### HTML Links
      links are defined with the <a> tag:

      ex. <a href="link" target="_blank">Click here!</a>

      the links destination is specified by the href attribute 
      
        attributes provide additional information about elements

        always specified in the start tag

        usually come in name/value pairs like name="value"

        * always quote attribute values
        * always use lowercase attributes

    #### HTML Images
      images are defined with the <img> tag:

      the source file (src), alternative text (alt), width, and height, are provided as attributes

      ex. <img src="url" alt="an image" width="100" height"100">

        there are 2 ways to specify the url in the src attribute

          absolute url: links to external image hosted on another website

          relative url: links to an image on local machine

  ### Viewing HTML Source
    CTRL/CMD + U

  ### Inspect an HTML Element  
    CTRL/CMD + I

  ### style attribute
  used to add styles to an element, such as color, font, size, etc.

  ex. <tagname style="property:value;">
  where property in this case is a CSS property, and value is a CSS value

  ex. properties: background-color, color, font-family, font-size, text-align

  in line styling is not fun sometimes! esp with larger code bases. more on that soon!

  ### other useful tags!

  <div></div>: used to divide up sections
  <ol></ol>: ordered list
  <ul></ul>: unordered list
  <li></li>: list item


## CSS - Cascading Style Sheets
  * cascading means that a style applied to a parent element will also apply to all children elements within the parent.

  used to format the layout of a webpage.

  can control color, font, size of text, spacing between elements, how elements are positioned / laid out, what background images or background colors are to be used, different displays for different devices and screen sizes, and much more!

  ### 3 ways to add css to html
    - inline - using the style attribute inside html elements
    - internal - by using a <style> element in the <head> section
    - external - by using a <link> element to link to an external css file

    we'll be focusing on external css!

    #### commonly used CSS properties
      color: // property for text colors
      font-family: // property for text fonts (can also import fonts!)
      font-size: // property for text sizes
      border: 2px solid powderblue; // defined border around html element
      padding: 20px; // defines a padding (space) between the text and the border
      margin: 25px; // defines a margin (space) outside the border

      extra you might use

      list-style: none;
      display:
      justify-content: (can only be used along w display)
      align-items: (can only be used along w display)
      border-radius: (rounding or sharpening borders)

## Resources / Examples
[W3 Schools](https://www.w3schools.com/Html/html_intro.asp)
[Pop Culture Recipes](https://jason-b-jiang.github.io/Recipes-Website/)
[Globetrotter Example](https://globetrotter-final.onrender.com/gallery.html)
