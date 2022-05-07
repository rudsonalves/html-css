A basic HTML page have a struct like:

Example
<pre>
<!DOCTYPE html>
<html>
    <head>
        <title>Page Title</title>
    </head>

    <body>
        <h1>This is a Heading</h1>
        <p>This is a paragraph.</p>
    </body>
</html> 
</pre>

Where <!DOCTYPE html> declaration defines that this document is a HTML5 document. The <html> element is the root of an HTML page. The <head> element contains meta information about the HTML page. The <title> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab). The <body> element defines the document's body, and is a container for all the visible contents, such as heading, paragraphs, images, hyperlinks, tables, list, etc.
The <h1> element defines a large reading and <p> defines a paragraph.


The href Attribute

The <a> tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to:

Example
<a href="https://my-blog.com">Visit may blog</a>


The src Attribute

The <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be desplayed:

Example
<img src="photo.png">

You can specify the URL in the src attribute as:

1. Absolute URL - links to a external image that is hosted on another website: src="https://my-blog.com/photo.jpg"

2. Relative URL - links to an image that is hosted within the website: src="/images/phto.jpg"


The width and height Attributes

The <img> tag should also contain the width and height attributes, which specifies the width and height of the image in pixels:

Example
 <img src="albert.jpg" width="110" height="110">

 
 The alt attribute

The rewuired alt attribute for the <img> tag specifies an alternativa text for a image, if the image for some reason canot be displayed. This can be due to slow connection, or an error in the src attribute, or if the user uses a screen reader.

Example
 <img src="albert.jpg" alt="Sorry, Albert Einstein is gone!">


 The style Attribute

 The style attribute is used to add styles to an element, such as color, font, size, and more.

Example
 <p style="color:red;">This is a red paragraper.</p>


 The lang Attribute

 You should always include the lang attribute insite the <html> tag, to declare the language of Web page. This is a meant to assist search engines and browsers.

Example
<!DOCTYPE html>
<html lang="en-US">
<body>
...
</body>
</html>


The title Attribute

The title attribute defines some extra information about an element. The value of the title attribute will be dosplayed as a tooltip when you mouse over the element:

Example
<p title="I'm a tooltip">This is a paragraph with a tooltip.</p>


HTML Headings

HTML headings are defined with the <h1> to <h6> tags. <h> defines the most important heading.

Each HTML heading has a default size for any heading with the style attribute, using the CSS font-size property:

Example
<h1 style="font-size:60px;">Heading 1</h1>


HTML Horizontal Rules

The <hr> tag defines a thematic break in a HTML page, and is most often displayed as a horizontal rule. The <hr> elemente is used to separate content (or define a change) in an HTML page:

Example
<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>
<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr> 


HTML Line Breaks

The HTML <br> element defines a line break. Use <br> if you want a line break (a new line) without starting a new paragraph:

Example
<p>This is <br> a paragraph<br>with line breaks.</p>


The Poem - HTML <pre> Element

The poem must be displayed in multiple lines. The HTML <pre> element defines preformatted text. The text inside a <pre> element is displayed in a fixed-width font (usuallyt Courier), and it preserves both spaces and line breaks.

Example
 <pre>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</pre> 


The HTML Styles Attribute

The HTML styles attribute is used to add styles to an element, such as color, font, size, and more. Setting the style of an HTML element, can be done with the style attribute. The HTML attribute has the following sytax:

Example
<tagname style="property:value;">

The property is a CSS property. The value is a CSS value.


Backgourd Color

The CSS background-color property defines the background color for a n HTML element.

Exemple: Set the background color for a page to powderblue:

Example
<body style="background-color:powderblue;">

Example
<pre style="background-color:powderblue; color:red;">

The last line define a <pre> block with background color powderblue and font color red.


Fonts

The CSS font-family property defines the font to be used for an HTML element.

Example
<h1 style="font-family:verdana;">This is a headling in verdana font</h1>


Text Size

The CSS font-size property defines the text size for an HTML element.

Example
<p style="font-size:160%;">Thie is a paragraph with 160% resized.</p>


Text Alignment

The CSS text-align property defines the horizontal text alignment for an HTML element.

Example
<h1 style="text-align:center;">Centered Heading</h1>


HTML Text Formatting

HTML contains several elements for defining text qith a special meaning, like bold, italic, sub and superscript, ...


HTML Formatting Elements

Formatting elements were designed to display special types of text:

- <b> - bold text
- <strong> - importante text
- <i> - italic text
- <em> - emphasized text
- <mark> - marked text
- <smal> - smaller text
- <del> deleted text
- <ins> - inserted text
- <sub> - subscript text
- <sup> - superscript text


HTML Quotating and Citation Elements

In this chapter we will go through the <blockquote>, <q>, <abr>, <address>, <cite>, and <bdo> HTML elements.


HTML <blockquote> for Quotations

The HTML <blockquote> element defines a section that is quoted form anoter source. Browsers usually indent <blockquote> elements.

Example
<h3>Albert Einstein</h3>

<blockquote cite="https://en.wikipedia.org/wiki/Albert_Einstein#Academic_career">
Albert Einstein was born in Ulm,[7] in the Kingdom of Württemberg in the German Empire, on 14 March 1879 into a family of secular Ashkenazi Jews.[20][21] His parents were Hermann Einstein, a salesman and engineer, and Pauline Koch. In 1880, the family moved to Munich, where Einstein's father and his uncle Jakob founded Elektrotechnische Fabrik J. Einstein & Cie, a company that manufactured electrical equipment based on direct current.[7]
</blockquote>


HTML <q> for Short Quotations

The HTML <q> tag defines a short quotation. Browsers normally insert quotation marks around the qoutations.

Example
<p>One German magazine included him in a list of enemies of the German regime with the phrase, <q>not yet hanged</q>, offering a $5,000 bounty on his head.</p>

