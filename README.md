# HTML-and-CSS-crash-course
## What is HTML?
HTML stands for <strong> Hyper Text Markup Language. </strong> <br>
HyperText Markup Language (HTML) is the set of markup symbols or codes inserted into a file intended for display on the Internet. The markup tells web browsers how to display a web page's words and images.<br>
HTML is the standard markup language for creating Web pages.<br>
HTML consists of a series of elements.<br>
HTML elements tell the browser how to display the content that this is heading (h1, h2, h3, h4, h5, h6) and this is a paragraph and this is link and this is an image etc.<br>
<b>NOTE</b> There is no space between the angle bracket and tagname you have to remember.< h1 >

## A Simple HTML Docoment
<img src="https://github.com/amuhaiminshah/HTML-and-CSS-crash-course/blob/main/How%20to%20write%20link%20in%20html.png" alt="Example of HTML docoment"> 

### Explanation of this image
<li>The <b>!DOCTYPE html</b> declaration defines that this document is an HTML5 document.</li> 
<li>The <b>html</b> element is the root element of an HTML page.</li>
<li>The <b>head</b> element contains meta information about the HTML page like its title, scripts, and style sheets.</li>
<li>The <b>title</b> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab).</li>
<li>The <b>body</b> element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.</li>
<li>The <b>h1</b> element defines a large heading, you have to know that there are 6 heading (h1, h2, h3, h4, h5, h6.</li>

## What is an HTML element?
An HTML element is defined by a start tag, some content, and an end tag: <br>
< tagname > content goes here... < /tagname > <br>
The HTML <b>element</b> is everything from the start tag to the end tag: <br>
< h1 >My First Heading< /h1 > <br>
< p > This paraghraph.< /p > <br>
<pre>
<b>Starting tag</b>            <b>Element content</b>            <b>End tag</b>
< h1 >                  My First Heading           < /h1 > 
< p > 	                My first paragraph. 	   < /p >
< br > 	                none 	                   none
</pre>
<b>Note:</b> Some HTML elements have no content (like the < br > element). These elements are called empty elements. Empty elements do not have an end tag!

## Web Browsers
The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.

A browser does not display the HTML tags, it only display the content which is inside the tag.
#### For example:
<img src="https://github.com/amuhaiminshah/HTML-and-CSS-crash-course/blob/main/Example%20of%20web%20browser.png" alt="Example of Web Browser"> 

# Editor?
### How to save the HTML work in <b>Windows</b>
##### Mostly people will be tinking where to write the code if you are beginner so first use <b>Notepad</b> or <b>Text Editor</b>.
## How to use the Notepad or Text editor?
### Step-1:
First write the following HTML code.<br>
<img src="https://www.w3schools.com/html/img_notepad.png" alt="Example of some html">
### Step-2:
Then save the file on your computer and Name the file <b> "index html." </b>
<img src="https://www.w3schools.com/html/img_saveas.png" alt="How to save file of html?">
### Step-3:
Open the save file on browser(<b>right click</b> on file and choose the <b>open with</b> any browser you have in your computer.<br>
Your browser will looks like this:
<img src="https://github.com/amuhaiminshah/HTML-and-CSS-crash-course/blob/main/Example%20of%20web%20browser.png" alt="Example of browser">

<also show that how to save the work in ubuntu>


# HTML Basic Examples

## HTML Headings
HTML headings are defined with the <b>< h1 ></b> to <b>< h6 ></b> tags.<br>
< h1 > defines the most important heading. < h6 > defines the least important heading
<b> NOTE:</b> There are 6 heading in HTML.
#### For example:
<img src="https://github.com/amuhaiminshah/HTML-and-CSS-crash-course/blob/main/Example%20of%20web%20browser.png" alt="Example of Heading 1 to 6">

## HTML paragraphs
HTML paragarphs are defined with the < p > tag:
#### For example:
<img src="https://github.com/amuhaiminshah/HTML-and-CSS-crash-course/blob/main/Example%20of%20web%20browser.png" alt="Example of paragraph">

## HTML Links
HTML link are defined with the < a > tag:
#### For example:
<img src="https://github.com/amuhaiminshah/HTML-and-CSS-crash-course/blob/main/How%20to%20write%20code%20for%20link%20in%20html.png" alt="Example of HTML Links">

## HTML Images
HTML Images are defined with the < img > tag.<br>
The source file ( src ), alternative text ( alt ), width, and height are provided as attributes:
#### For example:
<img src="https://github.com/amuhaiminshah/HTML-and-CSS-crash-course/blob/main/Example%20of%20link%20display.png" alt="Example of HTML Image">


### How to View HTML Source?
Have you ever seen a Web page and wondered "Hey! How did they do that?"

#### View HTML Source Code:
Right-click in an HTML page and select "View Page Source" (in Chrome) or "View Source" (in Edge), or similar in other browsers. This will open a window containing the HTML source code of the page.

#### Inspect an HTML Element:
Right-click on an element (or a blank area), and choose "Inspect" or "Inspect Element" to see what elements are made up of (you will see both the HTML and the CSS). You can also edit the HTML or CSS on-the-fly in the Elements or Styles panel that opens.

## HTML Attributes
### What is html attributes?
<li>All HTML attributes can have <b>attributes</b></li><br>
<li>Attributes provide <b>additional information</b> about elements</li><br>
<li>Attributes are always specified in the <b>start tag</b></li><br>

### The href Attribute
The <b>< a ></b> tag defines a <b>hyperlink</b>. The <b>href</b> attribute specifies the URL of the page the link goes to.
#### For example:
<img src="https://github.com/amuhaiminshah/HTML-and-CSS-crash-course/blob/main/Example%20of%20%3Ca%20href%3E%20tag.png" alt="Image of < a href >">

### The src, width, height and alt attributes
The <b>< img ></b> tag is used to embed an image in an HTML page. The <b>src</b> attribute specifies the path to the image to be displayed.<br>
The <b>< img ></b> tag should also contain the <b>width</b> and <b>height</b> attributes, which specifies the width and height of the image (in pixels).<br>
The required <b>alt</b> attribute for the <b>< img ></b> tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to slow connection, or an error in the <b>src</b> attribute, or if the user uses a screen reader.
#### For example:
<img src="https://github.com/amuhaiminshah/HTML-and-CSS-crash-course/blob/main/pic%20of%20img%20tag.png" alt="Example of src attribute">

### The style attribute
The <b>style</b> attribute is used to add styles to an element, such as color, font, size, and more.
#### For example:
<img src="https://github.com/amuhaiminshah/HTML-and-CSS-crash-course/blob/main/style.png" alt="">

### Heading tag
HTML headings are defined with the <b>< h1 ></b> to <b>< h6 ></b> tags.<br>
<b>< h1 ></b>defines the most important heading. <b>< h6 ></b> defines the least important heading.
##### You know that how to write the code for heading.

### How to style the heading?
Each HTML heading has a default size. However, you can specify the size, font family, background-color etc for any heading with the <b>style</b> attribute.
#### For example:
<img src="https://github.com/amuhaiminshah/HTML-and-CSS-crash-course/blob/main/style.png" alt="style heading">

### Paragraph tag
<b>< p ></b> This element define paragraph.<br>
With HTML, you cannot change the display by adding extra spaces or extra lines in your HTML code.<br>
The browser will automatically remove any extra spaces and lines when the page is displayed.<br>
The <b>< hr ></b> tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule.<br>
<b> < br ></b> </b> This command is used to brake the line. It has no end tag.<br>
<b>< pre></b> Starting tag. <b> < /pre ></b> Closing tag. (pre) Defines pre-formatted text. The text inside a <b>< pre ></b> element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks.
#### For example:
<img src="https://github.com/amuhaiminshah/HTML-and-CSS-crash-course/blob/main/paragraph%20tags.png" alt="paragraph tags">

## Style attribute:
The HTML <b>style</b> attribute is used to add styles to an element, such as color, font-family, , font-size, and more.
#### How to write the <b>Syntax for style</b>
<pre>< tagname style="property:value;" ></pre><br>
The <b>property</b> is a CSS property. The <b>value</b> is a CSS value.

### Background-color, color, font-family, text-size, text-alignment
<li>Use the <b>style</b> attribute for styling HTML elements</li>
<li>Use <b>background-color</b> for background color.</li>
<li>Use <b>color</b> for text colors.</li>
<li>Use <b>font-family</b> for text fonts.</li>
<li>Use <b>font-size</b> for text sizes.</li>
<li>Use <b>text-align</b> for text alignment.</li>

#### For example:
##### Input:
<img src="https://github.com/amuhaiminshah/HTML-and-CSS-crash-course/blob/main/Style%20attributes.png" alt="Style attribute">

##### Output:
<img src="https://github.com/amuhaiminshah/HTML-and-CSS-crash-course/blob/main/Web%20browser.png" alt="Web brower">

## HTML text formatting 
<b>MHTML contains several elements for defining text with a special meaning</b>.</li>
<li> <b> < b > </b> element defines bold text, without any extra importance.</li>
<li> <b> < strong > </b> element defines text with strong importance. The content inside is typically displayed in bold.</li>
<li> <b> < i > </b> element defines a part of text in an alternate voice or mood. The content inside is typically displayed in italic.</li><b>Tip:</b> A screen reader will pronounce the words in <em> with an emphasis, using verbal stress.<br>
<li> <b> < em > </b> - Emphasized text.</li>
<li> <b> < mark > </b> - Marked text or highlighted text.</li>
<li> <b> < small > </b> - Smaller text.</li>
<li> <b> < del > </b> element defines text that has been deleted from a document. Browsers will usually strike a line through deleted text.
<li> <b> < ins > </b> element defines a text that has been inserted into a document. Browsers will usually underline inserted text.</li>
<li> <b> < sub > </b> element defines subscript text. Subscript text appears half a character below the normal line, Subscript text can be used for chemical formulas, like H2O.</li>
<li> <b> < sup > </b> element defines superscript text. Superscript text appears half a character above the normal line, Superscript text can be used for footnotes, like WWW[1].</li>

#### For example:
##### Input:
<img src="https://github.com/amuhaiminshah/HTML-and-CSS-crash-course/blob/main/Formatting%20html%20code.png" alt="formatting html code">
##### Output:
<img src="https://github.com/amuhaiminshah/HTML-and-CSS-crash-course/blob/main/Formatting%20display.png" alt="dispay of formatting text">

## HTML Quotation Elements
In this chapter we are going to cover the following elements:
<p> < blockquote >,< q >, < abbr >, < address >, < cite >, and < bdo > </p>

### Short Quotation
<li> <b> < q > </b> This tag is used for small quotation.</li>
<li> <b> < abbr > </b> This tag is used for abbreviation or an acronym, like "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM".</li>
<b>Tip:</b> Use the global title attribute to show the description for the abbreviation/acronym when you mouse over the element. 
<li> <b> < address > </b> This tag is used for contact information for the author/owner of a document or an article.</li>
<li> <b> < cite > </b> This tag defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.).</li>
<b> NOTE:</b> A person's name is not the title of a work.
<li> <b> < bdo dir="rtl or ltr"> </b> BDO stands for Bi-Directional Override. This tag is used to override the current text direction</li>
<b> NOTE:</b> There <b>rtl</b> stands for <b>right to left</b> and <b>ltr</b> stands for <b>left to right</b><br>

#### For example:

##### Input:
<img src="https://github.com/amuhaiminshah/HTML-and-CSS-crash-course/blob/main/Input%20of%20quotation" alt="Input of quotation">

##### Output:
<img src="https://github.com/amuhaiminshah/HTML-and-CSS-crash-course/blob/main/Output%20of%20quotation.png" alt="Output of quotation">

## Comments
### Add comment
<b> < !-- content goes here -- ></b>

### Hide content
Comments can be used to hide content.
<br>
Which can be helpful if you hide content temporarily
#### For example:
< p >This is a first paragraph.< /p >

< !-- <p>This is hide paragraph.< /p > -- >

< p >This is a last paragraph too.< /p >

### comment inline
< p > This < !-- This is comment -- > is a paragraph.< /p >

#### All comment example: 
##### Input:
<img src="https://github.com/amuhaiminshah/HTML-and-CSS-crash-course/blob/main/Input%20of%20comments.png" alt="Example of comment code">

##### Output:
<img src="https://github.com/amuhaiminshah/HTML-and-CSS-crash-course/blob/main/Output%20of%20comments.png" alt="Output example of comment">

## Colors
In HTML color can specified by using color name. You can use website or extension for color.
#### For example:
<a href="https://htmlcolors.com/google-color-picker">Click here</a>
You can use this website for generate different type of color.<br>
<b>Tip:</b> Just simply copy the code of color and use it.

### Where to use the color:
You can use the color to make the text colorful, background, border etc.<br>
<b> For borders</b> the syntex is like this:<br>
< h1 > style="border:value color name;" > Hello World < /h1 >


#### For example:
##### Input:
<img src="https://github.com/amuhaiminshah/HTML-and-CSS-crash-course/blob/main/Input%20of%20border.png" alt="Input of color">

##### Output:
<img src="https://github.com/amuhaiminshah/HTML-and-CSS-crash-course/blob/main/Output%20of%20border.png" alt="Output of color">

## Color value
In HTML, colors can also be specified using RGB values, HEX values, HSL values, RGBA values, and HSLA values.
### What is RGB?
<b>rgb(red, green, blue)</b><br>
Each parameter (red, green, and blue) defines the intensity of the color with a value between 0 and 255.<br>

This means that there are 256 x 256 x 256 = 16777216 possible colors!<br>

<b>For example,</b> rgb(255, 0, 0) is displayed as <b>red</b>, because red is set to its highest value (255), and the other two (green and blue) are set to 0.<br>

Another example, rgb(0, 255, 0) is displayed as <b>green</b>, because green is set to its highest value (255), and the other two (red and blue) are set to 0.<br>

To display <b>black</b>, set all color parameters to 0, like this: rgb(0, 0, 0).<br>

To display <b>white</b>, set all color parameters to 255, like this: rgb(255, 255, 255).<br>
<img src="https://www.maketecheasier.com/assets/uploads/2020/01/color-models-rgb.png.webp" alt="color models(rbg).">
### What is RGBA?
<b>rgba(red, green, blue, alpha)</b>
Here <b>alpha</b> specifies the opacity for a color.<br>
The alpha parameter is a number between 0.0 (fully transparent) and 1.0 (not transparent at all).
#### NOTE:
There are HEX, HSL, HSLA values if you want to learn more about the color these values so try to search in google.<br>

## HTML CSS
### What is CSS?
<b>CSS</b> stands for <b>Cascading Style Sheets.</b> <br>
<b>CSS</b> saves a lot of work. It can control the layout of multiple web pages all at once.
Cascading Style Sheets (CSS) is used to format the layout of a webpage.<br>

With CSS, you can control the color, font, the size of text, the spacing between elements, how elements are positioned and laid out, what background images or background colors are to be used, different displays for different devices and screen sizes, and much more!
<b> Tip: </b> The word cascading means that a style applied to a parent element will also apply to all children elements within the parent. So, if you set the color of the body text to "blue", all headings, paragraphs, and other text elements within the body will also get the same color (unless you specify something else)!

### How to use CSS?
CSS can be added to HTML documents in 3 ways:<br>

<li> <b> Inline </b> - by using the style attribute inside HTML elements. </li> <br>
<li> <b> Internal </b> - by using a <b>< style ></b> element in the <b>< head ></b> section </li> <br>
<li> <b> External </b> - by using a <b>< link ></b> element to link to an external CSS file. </li> <br>
The most common way to add CSS, is to keep the styles in external CSS files. However, in this repository we will use inline and internal styles, because this is easier to demonstrate, and easier for you to try it yourself.

#### Inline CSS
An inline CSS uses the <b>style</b> attribute of an HTML element.
##### For example:
< h1 style="color:blue;"> This blue heading. < /h1 >

#### Internal CSS
An internal CSS is defined in the <b>< head > </b> section of an HTML page, within a <b> < style > </b> element.
##### For example:
<pre>
< !DOCTYPE html >
< html >
< head >
< style >
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
< /style >
< /head >
< body >

< h1 >This is a heading< /h1 >
< p >This is a paragraph.< /p >

< /body >
< /html >
</pre>

#### External CSS
An external style sheet is used to define the style for many HTML pages.<br>
To use an external style sheet, add a link to it in the <head> section of each HTML page
##### For example:
<pre>
< !DOCTYPE html >
< html >
< head >
 <b> < link rel="stylesheet" href="styles.css" > </b>
< /head >
< body >

< h1 >This is a heading< /h1 >
< p>This is a paragraph.< /p >

< /body >
< /html >
</pre>
##### NOTE:
The external style sheet can be written in any text editor.

##### Style CSS
<pre>
body {
  background-color: powderblue;
}
h1 {
  color: blue;
}
p {
  color: red;
}
</pre>
<b> NOTE:</b>
With an external style sheet, you can change the look of an entire web site, by changing one file!

#### CSS padding
<pre>
p {
  border: 2px solid powderblue;
}
</pre>

#### How to Link to external CSS?
External style sheets can be referenced with a full URL or with a path relative to the current web page.
###### For example:
<pre>
< link rel="stylesheet" href="style.css" >
</pre>

## Links
HTML links are hyperlinks.<br>

You can click on a link and jump to another document. <br>
<b> NOTE:</b> A link does not have to be text. A link can be an image or any other HTML element.

### Syntex
The HTML <a> tag defines a hyperlink. It has the following syntax:
<pre>
< a href="url">link text < /a >
</pre>
The most important attribute of the <a> element is the href attribute, which indicates the link's destination. The link text is the part that will be visible to the reader. Clicking on the link text, will send the reader to the specified URL address.

### The target attribute
By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link. The target attribute specifies where to open the linked document.<br>

<b>The target attribute can have one of the following values:</b> <br>

<li> <b>_self </b> - Default. Opens the document in the same window/tab as it was clicked </li> <br>
<li> <b>_blank </b> - Opens the document in a new window or tab </li> <br>
<li> <b>_parent </b> - Opens the document in the parent frame </li> <br>
<li> <b>_top </b> - Opens the document in the full body of the window </li> <br>
#### For example:
<pre>
< a href="https://github.com/amuhaiminshah" target="_blank">Learn HTML< /a >
</pre>

## Absolute URLs vs. Relative URLs
A local link (a link to a page within the same website) is specified with a relative URL (without the "https://www" part):
#### For example:
<pre>
<h2>Absolute URLs</h2>
<p><a href="https://github.com/amuhaiminshah/">github.com/amuahiminshah</a></p>
<p><a href="https://www.google.com/">Google</a></p>

<h2>Relative URLs</h2>
<h2>Relative URLs</h2>
<p><a href="html_images.asp">HTML Images</a></p>
<p><a href="/css/default.asp">CSS Tutorial</a></p>
</pre>

### Use an image as a link
#### For example:
<pre>
< a href="github.com/amuhaiminshah" >
< img src="someimagename" alt="somealt" style="width:value;" >
< /a >
</pre>

### Link to email address
Use <b>mailto:</b> inside the <b>href</b> attribute to create a link that opens the user's email program (to let them send a new email) <br>
<pre>
< a href="mailto:someone@example.com">Send email< /a >
</pre>


<!-- 
### Button as a link
To use button as a link you have to add some javascript code.
##### For example:
<pre> 
< button onclick="document.location='default.asp'" > HTML Tutorial < /button >
</pre> -->

### Link title
The <b>title</b> attribute specifies extra information about an element. The information is most often shown as a tooltip text when the mouse moves over the element.
##### For example:
<pre>
< a href="somelink" title="Title" >content< /a >
</pre>
