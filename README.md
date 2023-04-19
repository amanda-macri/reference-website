# reference-website

1. Naming convention for all filenames, paths and folders
Naming conventions have a few rules, but they are mostly straightforward. Keep everything lowercase. No spaces. Only use letters, numbers and dashes (-).
Ex: AmAnDa_m@cri_ass1gnment.html : This is a bad example of naming conventions.
Ex: amanda-macri-assignment.html : This is a good example of naming conventions.

2. Best practices for commit messages
Commit messages are a way to communicate the changes that have been made in a code document. If there is a bug, spelling error, or more code is added, it will get commited. Keep the summary to under 50 words. Capitalize the first word, unless using conventional commits. Use imperative verbs. For example, "Add Robotto Regular 400 to the class of information". Imperative verbs give off the impression that you are giving an order. It is important to use this, because consistancy is key in these commits. Specify the type of commit used. For example: bugfix, feat, chore, etc. Keep the content direct - You want to get straight to the point. Leave out the extra words, like though, maybe, I think, kinda, etc. You mostly want your commit to answer what and why you did what you did. What did I change? Why did I change it?

3. What is HTML?
HTML stands for HyperText Markup Language. It is a programming language used for building websites. You can structure different sections, paragraphs, links, and more. It can be used for web development, internet navigation and web documentation.

4. Proper syntax for HTML tags
Every element will have an open tag, content and close tag. For example, here we have an element: `<h1>This is a Header<h1>`. `<h1>`is the open tag. `</h1>`is the close tag. `<h1>This is a Header</h1>` is the element itself.

5. Explain or demonstrate commonly used html tags/elements:
headings, h1-h6: These are heading tags, marked h1-h6. h1 being the most important header and biggest, h6 being the least important heading and smallest. Ex: `<h1>This is the biggest header</h1>`
p: This represents a paragraph of text. It isa block element and always starts on a new line. `<p>This is a paragraph.</p>`
lists: There are two kinds of lists - ordered lists (ol) and unordered lists (ul). Ordered lists would have their list items numbered and unordered lists would have them as bulletin points. To add a list itel, you would use the li tag underneath the first ol or ul tag. 
a: This tag represents a hyperlink. The href atributte is added to the a tag, as it is what indicates where the link will take you.
img: This tag is used to embed images. It requires two attributes: src, which specifies the path to the image and alt text that will be displayed if there are issues displaying an image.
q: This tag is used to mark up quotes in other elements, for example a paragraph.
blockquote: Use this tag for large, standalone quotes.
cite: This tag is used to mark the source of the quote.
em: This tag places emphasis on the element content. It is typically displayed in `<em>italics</em>`.
strong: This tag represents urgency and a high level of importance. It is typically displayed in `<strong>bold</strong>`.
b: This tag is used to highlight a keyword. It draws attention to a word without putting too much importance in it. It is typically presented in `<b>bold</b>`.
i: This tag is used when using another language, on a technical term or on a title. It is usually represented in `<i>italics</i>`.
small: This tag represents side comments and small print. The text in this element will be `<small>smaller</small>` than the normal size of text.

6. Explain block Elements and also explain the list of block elements and why they are used from below:
Block elements are elements that start a new line of their webpage. It divides websites up into useful sections and parts like its start, middle and end or maybe something that will be displayed on a side bar.
html: Html block element encases the all of the html.
head: A container for metadata, placed between the html tag and body tag.
body: The body tag encases all the main part of the HTML, in other words: the body. It would contain things like headings, paragraphs, images, hyperlinks, tables, lists, etc.
header: The header is used to block together the introductory part of the text. It will normally include the introduction, company logo and main navigation parts of a website.
nav
main: This element wraps the main content of the page.
section: This element wraps any related comment. It will often have its own associated header.
article: The article element represents a self-contained part of a website. For example, it would be used for blog posts or a product card.
div: This is a block element used to group elements together.
aside: This element is often used on content that is indirectly related to the webpage. It is usually represented in a sidebar.
footer: The footer is used at the bottom of a webpage. Companies will often use it to list links, copyright information, extra information about the company, terms and services.
span: This is an inline container used to mark up text or part of a document.
small

7. Explain why accessibility is important and also explain the accessibility properties like:
Web is a crucial part of our day to day life. Web accessibility ensures that everyone, disibility or not, can use and interact with the website. 
landmark roles: These are roles that help people with screen readers jump from section to section on the website. For example: `header role=“banner”`, `nav role=“navigation”` and more. The extra bit (ex: `role="banner"`) is added to the corresponding element.
aria labels: It provides a label for objects that can be read by assistive technology. It provides a text label for an object, like a button. When a screen reader encounters this, it will read gthe alt text, so the user is clear on what it is.
image alternative texts: These are alternative texts that describe the corresponding image. They are only displayed when the image cannot be, for example if there is a glitch or slow connection. It is read outloud to those who use a screen reader software.

8. What is CSS and how can we implement CSS to our html file (write a proper explanation with the code required to attach a CSS file inside html file)
CSS stands for Cascading Style Sheets. It is a coding language used to style HTML documwents. CSS allows you to mnodify many of the visual elements of a webpage, such as: font, colour, image and font sizes, link attributes and much more.
This is how you create and attach your CSS document to your HTML: First, you want to create your CSS stylesheet. To do that, go to file in the top left and click new file. Name it "style.css". Put the put the "style.css" in a new folder called "css". To link the HTML and CSS, you have to paste `<link rel="stylesheet" href="/css/style.css">` into the "head" of your HTML. Once done, all changes you add to your CSS will modify your HTML.

9. What is the difference between CSS property and value (write explanation and an example code)
A property is an aspect of a selector, like margin, background-color, etc. A value is the descriptor of the change, like 1rem, purple, etc. Code example: 
    `html {font-family: 'Roboto', sans-serif;`
        `margin-right: 3rem;`
        `margin-left: 3rem;`
        `color: white;`
        `background-color: rgb(34, 31, 31);`
     `}`
In this example, we see the selector of HTML. I added all the properties of font-family, margin-right, margin-left, color and background colour. Then there is the value, which is always second. For example, we have 'Roboto', sans-serif;, 3rem and rbg.

10. Why do we use border-box property in CSS?
We use the border box property in CSS to organize the content, padding, border and margin of an element. It helps us layout elements in CSS and give space where needed. It simplifies adjusting sizes too. Setting the height and weight to the border edges reflects the actual space being occupied and displayed on the screen.

11. Explain different type of ways we can add spacing to an element
We can add spacing to an element by using margin or padding properties. The margin property will give the element space from other boxes, whereas padding will give the text space from the edge of the box.

12. What is the main difference between margin and padding?
The margin outside the box. It is a transparent layer, pushing other boxes away. It gives the box some breathing room from other boxes. Padding pushes the edge of the box away from the text. It gives the content itself some breathing room.

13. What are different types of display properties?
There are four different kinds of display properties: none, inline, inline-block, and block.
none: The element is completely removed.
inline: Allows the elements to be on the same line - height and width properties have no effect.
inline-block: Same as inline, but you can modify the height and width properties.
block: Forces elements on their own line, regardless of width.

14. Write a brief explanation of flexbox property
Flexbox is a two-dimmensional layout method for arranging items in rows or columns. It simplifies the process of changing and positioning each element.

15. What are different types of flexbox properties and what is the major difference between them?
flex-direction: Change the orientation of the displayed content.
    row: Displays in a row.
    row-reverse: Displays in a row on the other side and reversed.</li>
    column: Displays in a column.</li>
    column-reverse: Same thing as row-reverse, but regarding columns.</li>
flex-wrap: Decides whether elements will be on one line (flex-wrap: no-wrap;), or wrap onto a new one (flex-wrap: wrap;).
justify-content: Lets you control the alignment of the element on the main axis and space between flex-items. The default value is flex-start, but it can be substituted for flex-end, center, space-between, space-around and space-evenly.
align-items: This works on positions on the cross axis, whereas justify-content does the main axis. Some values that can be used are stretch, flex-start, flex-end and center.

16. Explain with code the use of flexbox property on a parent element and also explain the sub properties you might need for the flexbox property
`.class {`
    `display: flex;`
    `flex-direction: row;`
    `justify-content: flex-end;`
`}`
The display: flex is what tells the CSS that we will be using a flexbox. Flex direction tells us what direction the items in the box will be going in. The options are column, column-reverse, row and row-reverse. Justify-content property tells us where the content goes. Is is at the start, middle or end? Is it spaced evenly?

17. Write a code example on how you will use a flexbox property on a parent element with sub properties.
`.class {`
    `display: flex;`
    `flex-direction: row;`
    `justify-content: flex-end;`
`}`
I will use the same example as before. I want my items to be displayed in a row and at the end of the box.

18. What is CSS grid property?
The CSS grid property is a property that allows you to set values of multiple other CSS properties. It allows you to arrange your items into rows and/or columns, size those rows/columns evenly or unevenly. etc.

19. Write the parent and two sub-properties used for CSS Grid Property.
To use a grid, we would use this code: 
`.class {`
    `display: grid;`
`}`
That would be the parent property. Two sub properties would be the two added onto the one above:
`.class {`
    `display: grid;`
    `grid-column-start: 1;`
    `grid-column-end: 3;`
`}`
This places a grid item at column 1 and lets it end on column line 3.

20. What is the difference between display: flex and display: grid?
Flexbox was designed for a one-dimmensional layout - either column or row. Grid is designed for two-dimmnesional layouts - rows and columns at the same time.

21. What sub-property we use to divide elements in CSS Grid properties?
The sub-property would be `grid-template-columns`or `grid-template-rows`. From there, we can add how many boxes we would want by adding a value. For example: `grid-template-columns: 25% 10% 15% 50%`.

22. What unit we use to fractionally divide the element width in CSS Grid property and what are others unit we can use alternatively? (Write a code example)
The unit to divide an element fractionally with CSS grid would be fr. We can also use percentages,for example: 50% 50%.
`.class {`
    `display: grid;`
    `grid-template-columns: 1fr 1fr 1fr`
`}`

23. What is the area property in CSS grid we use for the child elements?
The area property we would use on the child elements is `grid-area`. It accepts the values of the name of grid row start pos (1), grid column start pos (2), grid row end pos (3), and grid column end pos (4). Ex: 
`.class {`
    `display: grid;`
   ` grid-area: 1 / 2 / 3 / 4;`
`}`


24. Which sub-property of display grid you can use to prevent displaying empty columns. Write a code example of that property.
The property of `grid-auto-columns` will prevent from displaying empty columns. You would have to set the value to `min-content`, which makes the width of empty columns the minimum required to display the content in the grid.
`.example {`
    `display: grid;`
    `grid-template-columns: 1fr 1fr 1fr 1fr 1fr;`
    `grid-auto-columns: min-content;`
`}`

25. Explain the steps to add google fonts to your CSS file and how will you link it to the html file.
First, you want to go to the Google Fonts website (https://fonts.google.com/). Next, you're going to find a font you like. For this example, I am going to use "Roboto Regular 400". Click on the "Select (your font properties here)" and you'll see it add to the boxes on the right. Copy what is in the first box on the right and paste it into the "head" section of your HTML. Finally, if you want to use this font, you need to add it in the css. You would have to select the element you want to have the font. Then go to Google Fonts and copy what is in the second box. Paste into your css after the selected element. It might look something like this:
`html {`
    `font-family: 'Roboto', sans-serif;`
`}` 
