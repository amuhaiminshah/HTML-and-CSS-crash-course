# HTML-and-CSS-crash-course
## What is HTML?
HTML stands for <strong> Hyper Text Markup Language. </strong> <br>
HyperText Markup Language (HTML) is the set of markup symbols or codes inserted into a file intended for display on the Internet. The markup tells web browsers how to display a web page's words and images.<br>
HTML is the standard markup language for creating Web pages.<br>
HTML consists of a series of elements.<br>
HTML elements tell the browser how to display the content that this is heading (h1, h2, h3, h4, h5, h6) and this is a paragraph and this is link and this is an image etc.<br>
<b>NOTE</b> There is no space between the angle bracket and tagname you have to remember.< h1 >

## A Simple HTML Docoment
<img src="https://miro.medium.com/max/1400/1*hQquTqhdj2DVCeeKNk-FGA.png" alt="Example of HTML docoment"> 

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
<img src="https://www.w3schools.com/html/img_chrome.png" alt="Example of Web Browser"> 

# Editor?
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
<img src="https://www.w3schools.com/html/img_chrome.png" alt="Example of browser">

# HTML Basic Examples

## HTML Headings
HTML headings are defined with the <b>< h1 ></b> to <b>< h6 ></b> tags.<br>
< h1 > defines the most important heading. < h6 > defines the least important heading
<b> NOTE:</b> There are 6 heading in HTML.
#### For example:
<img src="https://seranking.com/blog/wp-content/uploads/2019/08/Diagrammatic-Representation-of-Heading-Tag-Hierarchy.png" alt="Example of Heading 1 to 6">

## HTML paragraphs
HTML paragarphs are defined with the < p > tag:
#### For example:
<img src="https://www.techfry.com/images/articles/html/html-paragraph-tag.jpg" alt="Example of paragraph">

## HTML Links
HTML link are defined with the < a > tag:
#### For example:
<img src="https://www.guru99.com/images/image006(1).png" alt="Example of HTML Links">

## HTML Images
HTML Images are defined with the < img > tag.<br>
The source file ( src ), alternative text ( alt ), width, and height are provided as attributes:
#### For example:
<img src="https://s3-ap-southeast-1.amazonaws.com/djamblog/article-180320105942.png" alt="Example of HTML Image">


### How to View HTML Source?
Have you ever seen a Web page and wondered "Hey! How did they do that?"

#### View HTML Source Code:
Right-click in an HTML page and select "View Page Source" (in Chrome) or "View Source" (in Edge), or similar in other browsers. This will open a window containing the HTML source code of the page.

#### Inspect an HTML Element:
Right-click on an element (or a blank area), and choose "Inspect" or "Inspect Element" to see what elements are made up of (you will see both the HTML and the CSS). You can also edit the HTML or CSS on-the-fly in the Elements or Styles panel that opens.

