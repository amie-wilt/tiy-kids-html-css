# The Iron Yard - Kids' HTML & CSS

## Introduction
  - My name is Amie Wilt
    - I am a web developer
    - I am also a graduate of The Iron Yard
  - Kurtis is our Teaching Assistant
    - He is a Ruby developer
    - He is also a graduate of The Iron Yard

## Topics we will cover in this course
  - What is HTML?
  - What are HTML tags and elements?
  - What is CSS?
  - How to style a website using CSS
  - How to create HTML and CSS files and view them in a web browser
  - Different tools to help you learn
  
## Week 1
  - What is HTML?
    - **H**yper**T**ext **M**arkup **L**anguage
    - Made up of tags and elements
    - Serves as the structure of a webpage
  - W3C, World Wide Web Consortium (https://www.w3.org/Consortium/)
    - an international community of member organizations, staff and the public that works together to define and develop web standards
    - One Web vision
  - HTML Tags
    - Tags separate normal text from HTML code.
    - Tags are not visible in the browser, they tell the browser what kind of content is being displayed.
    - Tags describe different document content
    - **Tags are chosen based on WHAT the content is, not HOW it looks**
    - Tag Syntax
      - Tags start with a '<' and end with a '>'
        - `<p>` (paragraph tag)
        - `<h1>` (heading tag)
      - Tags come in pairs or are self-closing:
        - `<p>`This is a paragraph and has a start and end tag.`</p>`
        - `<img src="image.jpg" />` This is an image tag, it does not have a start and end tag. It self closes before the closing bracket with a forward slash.
    - HTML Elements
      - The words 'tag' and 'element' are often used interchangeably. However, they are not the same thing.
      - Elements are made up of tags and the content they are describing.
        - `<p>`This is a paragraph with start and end tags. The tags and the content between them make up an HTML element.`</p>`
    - Let's play around in Codepen! (http://codepen.io)

## Week 2
  - What is CSS?
    - CSS stands for **C**ascading **S**tyle **S**heets
    - Where HTML is the **structure** of a webpage, CSS is the **layout** of a webpage.
    - HTML was never intended to be responsible for the formatting of a webpage.
    - The W3C created CSS to remove the styling from the HTML markup.
    - Styles can be managed in one CSS file rather than in numerous HTML files.
  - CSS Syntax
    - CSS consists of a selector and a declaration block.
    - A selector points to the HTML element that receives the styling.
    - The declaration block opens and closes with curly brackets and contain declarations.
    - A declaration is made up of a property and a value.
  - CSS Selectors
    - Element Selector
      - Selects elements based on the elements name
      - The element selector of an HTML paragraph (`<p>`) is **p**
    - ID Selector
      - Selects elements based on the ID attribute of an element
      - IDs are unique to one element and elements may only have one ID
      - They are written with a hash symbol (#)
      - HTML: `<p id="paragraph1">`
      - CSS: #paragraph1
    - Class Selector
      - Selects elements based on their class attribute
      - Classes can be used on multiple elements
      - They are written with a period (.)
      - HTML: `<p class="paragraph">`
      - CSS: .paragraph
      
## Week 3
  - The CSS **Display** Property
    - Most important CSS property for displaying layout.
    - Every HTML element has a default display property, most of which are block or inline.
      - Block-level elements
        - Always start on a new line
        - Take up the full available width
        - `<div>`, `<p>`, `<h1>`, `<header>`
      - Inline elements
        - Sit inline with the natural flow and therefore do not start on a new line
        - Only take up the necessary width
        - Do not respect height and width properties
        - Accept margin and padding properties but only respond to them horizontally, not vertically
        - `<span>`, `<a>`, `<img>`
      - Inline-block elements
        - Are similar to inline elements in that they sit inline with the natural flow
        - Take on block-level characteristics in that they respect the width, height, margin and padding properties
      - display: none;
        - Can you guess what that does?
        
## Week 4
  - The CSS **Position** Property
    - Manipulates the location of an HTML element
      - Static: the default position for all HTML elements
      - Relative
      - Absolute
      - Fixed
    - Static
      - The default position for all HTML elements
      - A static element sticks to the normal page flow
      - The left, right, top and bottom properties have **no effect** on static elements
    - Relative
      - Relative elements also stick to the normal page flow
      - However, they **are affected** by the left, right, top and bottom properties
      - These properties move the element relative to its **original position**
    - Absolute
      - When an element has a position of absolute, it is **removed from the natural flow of the page**
      - Other elements will behave as though it is not there
      - Absolute elements are positioned **relative to their closest positioned parent**
      - If there is no positioned parent, they are positioned **relative to the document body**
    - Fixed
      - A fixed element is **removed from the natural flow of the page** as absolutely-positioned elements are
      - However, they are always **positioned relative to the document body**, regardless of any positioned parents
      - Fixed elements are unaffected by scrolling
      
## Tools You Can Use
  - Learn more about HTML and CSS
    - W3Schools (not affiliated with the W3C), http://www.w3schools.com/
    - Codeacademy, https://www.codecademy.com/
  - Coding tools without the use of an editor
    - CodePen, http://codepen.io/
    - JSbin, http://jsbin.com/
  - Colors
    - W3Schools Color Picker, http://www.w3schools.com/colors/colors_picker.asp
    - Colourlovers, http://www.colourlovers.com/
    - Adobe Kuler, https://color.adobe.com/create/color-wheel/
  - Dummy Text
    - Lorem Ipsum, http://www.lipsum.com/
    - Cat Ipsum, http://www.catipsum.com/
    - Bacon Ipsum, http://baconipsum.com/
    - Veggie Ipsum, http://veggieipsum.com/
    - Baseball Ipsum, http://baseballipsum.apphb.com/
    - Pirate Ipsum, http://pirateipsum.me/
    - Space Ipsum, http://spaceipsum.com/
