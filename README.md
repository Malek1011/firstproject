# What is HTML? 
- HTML stands for Hyper Text Markup Language
- HTML is the standard markup language for creating Web pages
- HTML describes the structure of a Web page
- HTML consists of a series of elements
- HTML elements tell the browser how to display the content
- HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc. <br/><br/>
## HTML Structure
1. The \<!DOCTYPE html> declaration defines that this document is an HTML5 document
2. The \<html> element is the root element of an HTML page
3. The \<head> element contains meta information about the HTML page
4. The \<title> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
5. The \<body> element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
6. The \<h1> element defines a large heading
7. The \<p> element defines a paragraph 
 ## What is an HTML Element
 - An HTML element is defined by a start tag, some content, and an end tag:

\<tagname> Content goes here... \</tagname>
- The HTML element is everything from the start tag to the end tag:

\<h1>My First Heading\</h1> <br/>
\<p>My first paragraph.\</p> <br/><br/>

***Note***: Some HTML elements have no content (like the \<br> element). These elements are called empty elements. Empty elements do not have an end tag!

## Web Browsers
The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.

A browser does not display the HTML tags, but uses them to determine how to display the document:

![image](https://www.w3schools.com/html/img_chrome.png)





## HTML Page Structure

![image](https://www.basictutorials.in/images/html-structure.png)

***Note:*** The content inside the <body> section (the white area above) will be displayed in a browser. The content inside the <title> element will be shown in the browser's title bar or in the page's tab.
	
	
	
	
	
	
##	HTML Headings
HTML headings are defined with the \<h1> to \<h6> tags.

\<h1> defines the most important heading. \<h6> defines the least important heading:
	
	
	
	
	
![image](https://iq.opengenus.org/content/images/2019/08/img8.png)
	
	
##	HTML Paragraphs
HTML paragraphs are defined with the \<p> tag
	
	
	
![img](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQMN0MWZTyy0UTtvOVq2mhO_vXKJOxw--i7TVxRtp7fUvp5qg1TrV-qbRgv1yX5SmBGLVA&usqp=CAU)
	
	
##	HTML Links
HTML links are defined with the <a> tag:
	
	
![img](https://linuxhint.com/wp-content/uploads/2021/08/image8-2.png)
	
	
The link's destination is specified in the href attribute. 

Attributes are used to provide additional information about HTML elements.

You will learn more about attributes in a later chapter.
	
	
##	HTML Images
- HTML images are defined with the \<img> tag.

The source file (src), alternative text (alt), width, and height are provided as attributes:
	
![image](https://cdo-curriculum.s3.amazonaws.com/media/uploads/img_tag.png)
	
	
##	HTML Attributes
- All HTML elements can have attributes
- Attributes provide additional information about elements
- Attributes are always specified in the start tag
- Attributes usually come in name/value pairs like: name="value"
	
	
	
##	The href Attribute
The \<a> tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to.
	
	
##	The src Attribute
The \<img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed
	
	
- here are two ways to specify the URL in the src attribute:

1. Absolute URL - Links to an external image that is hosted on another website. Example: src="https://www.w3schools.com/images/img_girl.jpg".

***Notes***: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

2. Relative URL - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

**Tip**: It is almost always best to use relative URLs. They will not break if you change domain.

	
	
##	The width and height Attributes
The \<img> tag should also contain the width and height attributes, which specify the width and height of the image (in pixels)
	
	
##	The alt Attribute
The required alt attribute for the \<img> tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to a slow connection, or an error in the src attribute, or if the user uses a screen reader.
	
	
##	The style Attribute
The style attribute is used to add styles to an element, such as color, font, size, and more.
	
	
##	The title Attribute
The title attribute defines some extra information about an element.

The value of the title attribute will be displayed as a tooltip when you mouse over the element.
	
	 
	
	
##	HTML Horizontal Rules
The \<hr> tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule.

The \<hr> element is used to separate content (or define a change) in an HTML page
	
	
	
	
##	HTML Line Breaks
The HTML \<br> element defines a line break.

Use \<br> if you want a line break (a new line) without starting a new paragraph.

	
**The \<br> tag is an empty tag, which means that it has no end tag.**
	
	
	
	
	
##	The HTML \<pre> Element
The HTML \<pre> element defines preformatted text.

The text inside a \<pre> element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks <br/>



##      The HTML Style Attribute
Setting the style of an HTML element, can be done with the style attribute.
<br/>





## Background Color
The CSS background-color property defines the background color for an HTML element <br/>



## Text Color
The CSS color property defines the text color for an HTML element.<br/>




## Fonts
The CSS font-family property defines the font to be used for an HTML element.<br/>



## Text Size
The CSS font-size property defines the text size for an HTML element<br/>



## Text Alignment
The CSS text-align property defines the horizontal text alignment for an HTML element. <br/><br/>



## HTML Formatting Elements
Formatting elements were designed to display special types of text

- \<b> - Bold text
- \<strong> - Important text
- \<i> - Italic text
- \<em> - Emphasized text
- \<mark> - Marked text
- \<small> - Smaller text
- \<del> - Deleted text
- \<ins> - Inserted text
- \<sub> - Subscript text
- \<sup> - Superscript text
<br/><br/>



## HTML \<blockquote> for Quotations
- The HTML \<blockquote> element defines a section that is quoted from another source.

- Browsers usually indent \<blockquote> elements. </br><br/>

<br/><br/>



## HTML \<q> for Short Quotations
The HTML \<q> tag defines a short quotation.

Browsers normally insert quotation marks around the quotation.

<br/><br/>



## HTML \<address> for Contact Information
The HTML \<address> tag defines the contact information for the author/owner of a document or an article.

The contact information can be an email address, URL, physical address, phone number, social media handle, etc.

The text in the <address> element usually renders in italic, and browsers will always add a line break before and after the \<address> element.


<br/><br/>


## HTML \<cite> for Work Title
The HTML \<cite> tag defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.).

Note: A person's name is not the title of a work.

The text in the \<cite> element usually renders in italic.

<br/><br/>


## HTML Comment Tag

You can add comments to your HTML source by using the following syntax:

\<!-- Write your comments here -->

***Note***: Comments are not displayed by the browser, but they can help document your HTML source code.

<br/><br/>



## Color Values
- In HTML, colors can also be specified using RGB values, HEX values, HSL values, RGBA values, and HSLA values.

<br/><br/>


## HTML Links \- Hyperlink

- HTML links are hyperlinks.

- You can click on a link and jump to another document.

- When you move the mouse over a link, the mouse arrow will turn into a little hand.

***Note***: A link does not have to be text. A link can be an image or any other HTML element!

<br/><br/>



## HTML Links \- Syntax
- The HTML \<a> tag defines a hyperlink. It has the following syntax:

\<a href="url">link text\</a> <br/><br/>

- he most important attribute of the \<a> element is the href attribute, which indicates the link's destination.

The link text is the part that will be visible to the reader.

Clicking on the link text, will send the reader to the specified URL address.



<br/><br/>





## HTML Links - The target Attribute
- By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link.

- The target attribute specifies where to open the linked document.

The target attribute can have one of the following values:

- _self - Default. Opens the document in the same window/tab as it was clicked
- _blank - Opens the document in a new window or tab
- _parent - Opens the document in the parent frame
- _top - Opens the document in the full body of the window



<br/><br/>




## HTML Links - Use an Image as a Link
To use an image as a link, just put the <img> tag inside the \<a> tag:

#### Example:
\<a href="default.asp">
\<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
\</a>



<br/><br/>




## Link to an Email Address
Use mailto: inside the href attribute to create a link that opens the user's email program (to let them send a new email):

#### Example
\<a href="mailto:someone@example.com">Send email\</a>



<br/><br/>



## Link Titles
The title attribute specifies extra information about an element. The information is most often shown as a tooltip text when the mouse moves over the element.



<br/><br/>



## HTML Favicon
- A favicon is a small image displayed next to the page title in the browser tab.

To add a favicon to your website, either save your favicon image to the root directory of your webserver, or create a folder in the root directory called images, and save your favicon image in this folder. A common name for a favicon image is "favicon.ico".

Next, add a \<link> element to your \"index.html" file, after the \<title> element, like this:

#### Example
\<!DOCTYPE html>

\<html>

\<head>

  \<title>My Page Title\</title>
  
  \<link rel="icon" type="image/x-icon" href="/images/favicon.ico">
  
\</head>

\<body>


\<h1>This is a Heading\</h1> <br/><br/>

\<p>This is a paragraph.\</p>


\</body>

\</html>



<br/><br/>



## Unordered HTML List
- An unordered list starts with the <ul> tag. Each list item starts with the <li> tag.

The list items will be marked with bullets (small black circles) by default:

#### Example
\<ul>

  \<li>Coffee\</li>
  
  \<li>Tea<\/li>
  
  \<li>Milk\</li>
  
\</ul>



<br/><br/>



## Ordered HTML List
- An ordered list starts with the <ol> tag. Each list item starts with the <li> tag.

The list items will be marked with numbers by default:

#### Example
\<ol>

  \<li>Coffee\</li>
  
  \<li>Tea\</li>
  
  \<li>Milk\</li>
  
\</ol>



<br/><br/>



## HTML Description Lists
- HTML also supports description lists.

- A description list is a list of terms, with a description of each term.

The <dl> tag defines the description list, the <dt> tag defines the term (name), and the <dd> tag describes each term:

#### Example
\<dl>

  \<dt>Coffee\</dt>
  
  \<dd>- black hot drink\</dd>
  
  \<dt>Milk\</dt>
  
  \<dd>- white cold drink\</dd>
  
\</dl>


<br/><br/>


## What are Emojis?
- Emojis look like images, or icons, but they are not.

- They are letters (characters) from the UTF-8 (Unicode) character set.


<br/><br/>


## The HTML charset Attribute
To display an HTML page correctly, a web browser must know the character set used in the page.

This is specified in the \<meta> tag:

\<meta charset="UTF-8">


<br/><br/>




## Emoji Characters
- Emojis are also characters from the UTF-8 alphabet:

- 😄 is 128516
- 😍 is 128525
- 💗 is 128151
#### Example
\<!DOCTYPE html>

\<html>

\<head>

\<meta charset="UTF-8">

\</head>

\<body>

\<h1>My First Emoji\</h1>

\<p>&#128512;\</p>

\</body>

\</html>


<br/><br/>



## The \<form> Element
- The HTML \<form> element is used to create an HTML form for user input
- The \<form> element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.


<br/><br/>



## The \<input> Element
- The HTML \<input> element is the most used form element.

- An \<input> element can be displayed in many ways, depending on the type attribute.


<br/><br/>



## Text Fields
- The \<input type="text"> defines a single-line input field for text input.


<br/><br/>



## The \<label> Element


The \<label> tag defines a label for many form elements.

The \<label> element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focuses on the input element.

The \<label> element also helps users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the \<label> element, it toggles the radio button/checkbox.

The for attribute of the <label> tag should be equal to the id attribute of the \<input> element to bind them together.


<br/><br/>



## Radio Buttons
The \<input type="radio"> defines a radio button.

Radio buttons let a user select ONE of a limited number of choices.


<br/><br/>



## Checkboxes
The \<input type="checkbox"> defines a checkbox.

Checkboxes let a user select ZERO or MORE options of a limited number of choices.


<br/><br/>



## The Submit Button
The \<input type="submit"> defines a button for submitting the form data to a form-handler.

The form-handler is typically a file on the server with a script for processing input data.

The form-handler is specified in the form's action attribute.
