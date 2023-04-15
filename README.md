# reference-website

1. Naming convention for all filenames, paths and folders
Naming conventions have a few rules, but they are mostly straightforward. Keep everything lowercase. No spaces. Only use letters, numbers and dashes (-).

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
a:
img:
q: This tag is used to mark up quotes in other elements, for example a paragraph.
blockquote: Use this tag for large, standalone quotes.
cite: This tag is used to mark the source of the quote.
em: This tag places emphasis on the element content. It is typically displayed in `<em>italics</em>`.
strong: This tag represents urgency and a high level of importance. It is typically displayed in `<strong>bold</strong>`.
b: This tag is used to highlight a keyword. It draws attention to a word without putting too much importance in it. It is typically presented in `<b>bold</b>`.
i: This tag is used when using another language, on a technical term or on a title. It is usually represented in `<i>italics</i>`.
small: This tag represents side comments and small print. The text in this element will be `<small>smaller</small>` than the normal size of text.

6. Explain block Elements and also explain the list of block elements and why they are used from below:
html
head
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

17. Write a code example on how you will use a flexbox property on a parent element with sub properties.

18. What is CSS grid property?

19. Write the parent and two sub-properties used for CSS Grid Property.

20. What is the difference between display: flex and display: grid?

21. What sub-property we use to divide elements in CSS Grid properties?

22. What unit we use to fractionally divide the element width in CSS Grid property and what are others unit we can use alternatively? (Write a code example)

23. What is the area property in CSS grid we use for the child elements?

24. Which sub-property of display grid you can use to prevent displaying empty columns. Write a code example of that property.

25. Explain the steps to add google fonts to your CSS file and how will you link it to the html file.



