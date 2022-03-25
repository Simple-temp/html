# Html
# Are the html tags and elements the same things?<br>
ANS : No..Because html elements are , there will be a starting tag at the beginning and some content in it and a closing tag at the end. html tag is a starting tag and a closing tag .<br>

# What are tags and attributes in html?<br>
Ans : Tags are the primary component of the HTML that defines how the content will be structured/ formatted, whereas Attributes are used along with the HTML tags to define the characteristics of the element. ‘align’ is the attribute using which we will align the paragraph to show in the center of the view.<br>

# What are void elements in html?<br>
Ans : Void tag are that tag who have no closing tag .. Example img tag, br tag, hr etc.<br>

# What is the advangtage of collapsing white space?<br>
Ans : In HTML, a blank sequence of whitespace characters is treated as a single space character, Because the browser collapses multiple spaces into a single space character and this helps a developer to indent lines of text without worrying about multiple spaces and maintain readability and understandability of HTML codes.<br>

# What are html entities? <br>
Ans : In HTML some characters are reserved like ‘<’, ‘>’, ‘/’, etc. To use these characters in our webpage we need to use the character entities called HTML Entities. Below are a few mapping between the reserved character and its respective entity character to be used.<br>

# What are defferent type of list in html ?<br>
Ans : There are two types of list in html . one is the order list and other is the unorder list.<br>

# What is the class attribute in html ?<br>
Ans : The class attribute is used to specify the class name for an HTML element. Multiple elements in HTML can have the same class value. Also, it is mainly used to associate the styles written in the stylesheet with the HTML elements<br>

What is the defference of id attribute and class attribute of html elements ?<br>
Ans : Multiple elements in HTML can have the same class value, whereas a value of id attribute of one element cannot be associated with another HTML element.<br>

Define multipart from data ?<br>
Ans : Multipart form data is one of the values of the enctype attribute. It is used to send the file data to the server-side for processing. The other valid values of the enctype attribute are text/plain and application/x-www-form-urlencoded<br>

Describe html layout structure ?<br>
Ans : Every web page has different components to display the intended content and a specific UI. But still, there are few things which are templated and are globally accepted way to structure the web page, such as:<br>

1. header: Stores the starting information about the web page.
2. footer: Represents the last section of the page.
3. nav: The navigation menu of the HTML page.
4. article: It is a set of information.
5. section: It is used inside the article block to define the basic structure of a page.
6. aside: Sidebar content of the page
<br>

How to optimize assets loading ?<br>
Ans : To optimize website load time we need to optimize its asset loading and for that:<br>

1. CDN hosting - A CDN or content delivery network is geographically distributed servers to help reduce latency.
2. File compression - This is a method that helps to reduce the size of an asset to reduce the data transfer
3. File concatenation - This reduces the number of HTTP calls.
4. Minify scripts - This reduces the overall file size of js and CSS files
5. Parallel downloads - Hosting assets in multiple subdomains can help to bypass the download limit of 6 assets per domain of all modern browsers. This can be configured but most general users never modify these settings.
6. Lazy Loading - Instead of loading all the assets at once, the non-critical assets can be loaded on a need basis

What are the various formatting tag in html ?
Ans : HTML has various formatting tags:<br>

1. b - makes text bold
2. i - makes text italic
3. em - makes text italic but with added semantics importance
4. big - increases the font size of the text by one unit
5. small - decreases the font size of the text by one unit
6. sub - makes the text a subscript
7. sup - makes the text a superscript
8. del - displays as strike out text
9. strong - marks the text as important
10. mark - highlights the text
11. ins - displays as added text

what are the defferent kinds of doctypes available ? <br>
Ans : The three kinds of Doctypes which are available
1. Strict Doctype
2. Transitional Doctype
3. Frameset Doctype

Please explain how to indicate the character set being used by a document in HTML ?<br>
Ans : The character set is defined in meta tag inside head element

meta charset="UTF-8"

What is the difference between strong, b tags and em, i tags ?<br>
Ans : The effect on a normal webpage of the tags strong, b and em, i is the same. b and i tags stands for bold and italic. These two tags only apply font styling and bold tag b, just adds more ink to the text, these tags don't say anything about the text.<br>

Whereas, strong and em tags represent that the span of text is of strong importance or more importance and emphatic stress respectively than the rest of the text. These tags have semantic meaning<br>

What is the significance of head and body tag in HTML ?<br>
Ans : head tag provides the information about the document. It should always be enclosed in the tag. This tag contains the metadata about the webpage and the tags which are enclosed by head tag like link, meta, style, script, etc. are not displayed on the web page. Also, there can be only 1 head tag in the entire Html document and will always be before the body tag.<br>

body tag defines the body of the HTML document. It should always be enclosed in the html tag. All the contents which needs to be displayed on the web page like images, text, audio, video, contents, using elements like p, img, audio, heading, video, div, etc. will always be enclosed by the body tag. Also, there can be only 1 body element in an HTML document and will always be after the head tag<br>

Can we display a web page inside a web page or Is nesting of webpages possible ?<br>
Ans : Yes, we can display a web page inside another HTML web page. HTML provides a tag iframe using which we can achieve this functionality
`iframe src=url of the web page to embed `

How is Cell Padding different from Cell Spacing ?<br>
Ans : Cell Spacing is the space or gap between two consecutive cells. Whereas, Cell Padding is the space or gap between the text/ content of the cell and the edge/ border of the cell. Please refer to the above figure example to find the difference

How can we club two or more rows or columns into a single row or column in an HTML table ?<br>
Ans : HTML provides two table attributes “rowspan” and “colspan” to make a cell span to multiple rows and columns respectively.

Is it possible to change an inline element into a block level element ?<br>
Ans : Yes, it is possible using the “display” property with its value as “block”, to change the inline element into a block-level element.

What are the permissible values of the position attribute ?<br>
Ans : There are 6 values of position attribute that can be used to position an html element.
1 . relative
2 . fixed
3 . static
4 . absolute
5 . inherit
6 . initial

In how many ways you can display HTML elements ?<br>
Ans:
1 . block
2 . none
3 . inline
4 . inline-block
5 . flex
6 . inline-flex
7 . grid

What is the difference between “display: none” and “visibility: hidden”, when used as attributes to the HTML element?<br>
Ans : used to visibility : hidden the html element are hidden and still takes up space. but the display : none hidden the element and it dont take any space .

How to specify the link in HTML and explain the target attribute ?<br>
Ans : There are 4 types terget attribute
1. _blank
2. _top 
3. _self 
4.  _parent

In how many ways can we specify the CSS styles for the HTML element ?<br>
Ans : There are 3 types css styles in html element
1. inline
2. external
3. internal
  
Difference between link tag link and anchor tag a ?<br>
Ans : a tag is create a hyperlink to another webpage . On the other hand link is connected to the external resources.

How to include javascript code in HTML ?<br>
Ans : Use a script tag after the body closing tag.

When to use scripts in the head and when to use scripts in the body ?<br>
Ans : if the scripts contain some event-triggered functions or jquery library then we should use them in the head section. If the script writes the content on the page or is not inside a function then it should be placed inside the body section at the bottom

What are forms ?<br>
Ans : The HTML form is used to collect the user inputs

How to handle events in HTML ?<br>
Ans : Using javascript , jquery to handle events in html . there are a lot's of type event onclick , onchnage etc.

What are some of the advantages of HTML5 over its previous versions ?<br>
Ans : advangtage is semantic , capability , run in background etc

How can we include audio or video in a webpage ?<br>
Ans : audio tag and video tag include audio or video in a webpage.

Inline and block elements in HTML5 ?<br>
Ans : inline element are img, a, button, label , input etc. block element are p , all heading tag header , section , footer

What is the difference between figure tag and img tag?<br>
Ans : figure tag is used to semantically organize the contents . img tag is used to embed the picture in the HTML5 document

How to specify the metadata in HTML5?<br>
Ans : To specify we can use meta tag which is a void tag,i.e., it does not have a closing tag. Some of the attributes used with meta tags are name, content, http-equiv, etc. The below image tells how to specify the metadata

Is the datalist tag and select tag same ?<br>
Ans : No. The datalist tag and select tag are different

Define Image Map ?<br>
Ans : It can be achieved by the map tag in HTML5

What are Semantic Elements ?<br>
Ans : Semantic elements are those which describe the particular meaning to the browser and the developer. Elements like from, table, article, figure, etc., are semantic elements.

Convert the below data into Tabular format in HTML5 ?<br>
Ans : this is table formate

Is drag and drop possible using HTML5 and how ?<br>
Ans : Yes, in HTML5 we can drag and drop an element

What is the difference between meter tag and progress tag ?<br>
Ans : meter tag has extra attribute like ‘form’, ‘low’, ‘high’, ‘min’, etc but progress tag should be used when we want to show the completion progress of a task

Difference between SVG and Canvas HTML5 element ?<br>
Ans
SVG is a vector based i.e. , highly scalable , high quality
Canvas It is Raster based i.e. , less scalable , quality avarage

What type of audio files can be played using HTML5?<br>
Ans
MP3... WAV... Ogg...

What are the significant goals of the HTML5 specification ?<br>
Ans : better structure , Forming a standard in cross-browser behavior without the dependency of plugins such as video tag

Explain the concept of web storage in HTML5 ?<br>
Ans : local storage and session storage

what is microdata in html5? <br>
ANS : Microdata is a standardized way to provide additional semantics in your web pages. for example itemid , itemprop, itemscope.. <br>

Which tag is used for representing the result of a calculation? <br>
ANS : The <output> tag is used for representing the result of a calculation
  
What is new about the relationship between the header and h1 tags in HTML5 ? <br>
ANS : the header for one section such as article or section. According to the HTML5 specification, each header element must at least have one h1 tag
  
Explain HTML5 Graphics <br>
ANS : html5 support two types of graphics  1.canvas(it is like drawing a whitepaper) 2.svg(it is used for icon)
  
Explain new input types provided by HTML5 for forms <br>
ANS : new input types provided by html5 are Date, week, month, datetime, datetime-local, color, email, search, number, tel, placeholder,url,range  
  
What are the New tags in Media Elements in HTML5 <br>
ANS : the new tags in media elements in html5 are audio, video, source, embed, track  
  
How will you make an image draggable in HTML5 ? 
ANS : to enable this functionality there is a draggable attribute in img tag
  
Why do we need the MathML element in HTML5? <br>
ANS : Mathml is a mathematical markup languege. it used for displaying mathematical expression on webpage 
  
What are the server-sent events in HTML5 ? <br>
ANS : The events pushed from the webserver to the browsers are called server-sent events . <eventsource> element is used
  
What are Web Workers?<br>
ANS : there are three types of web workers 1.dedicated, 2.shared, 3.service
  
What is the usage of a novalidate attribute for the form tag that is introduced in HTML5?<br>
ANS : Its value is a boolean type that indicates whether or not the data being submitted by the form will be validated beforehand. By making this false, forms can be submitted without validation which helps users to resume later also
  
What are raster images and vector images?<br>
ANS : raster img is non-editable and vesctor img is used algorithm and it extension is svg.
  
How to support SVG in old browsers?
ANS : To support old browsers instead of defining the resource of svg in src attribute of <img> tag, it should be defined in srcset attribute and in src the fallback png file should be defined
  
What are different approaches to make an image responsive?
ANS : width:auto
  
What is a manifest file in HTML5?<br>
ANS : The manifest file is used to list down resources that can be cached. there are three types of cache 1.Cache mainfest 2.network 3.fallback
  
What is the Geolocation API in HTML5?<br>
ANS : Geolocation API is used to share the physical location of the client with websites
  
What is a marquee?<br>
ANS : Marquee is used for the scrolling text on a web page
  
What is the difference between DIV and SPAN in HTML?  <br>
ANS : div is block-level element and a span element is in-line and usually used for a small chunk of HTML inside a line,such as inside a paragraph
  
What is the purpose of using alternative texts in images? <br>
ANS : The purpose of using alternative texts is to define what the image is about
  
Is the <!DOCTYPE html> tag considered as a HTML tag??
ANS : No, the <!DOCTYPE html> declaration is not an HTML tag
  
Why is a URL encoded in HTML?<br>
ANS : An URL is encoded to convert non-ASCII characters into a format that can be used over the Internet
  
What is the use of a span tag? Explain with example <br>
ANS : For adding color on text
      To add background on text
      Highlight any color text  
  
What is the HTML article element?<br>  
  ANS : The HTML <b>article</b> Element specifies independent and self-contained content in a document, page, application example <br>
Forum post
Blog post
Newspaper article  

What are the different media types and formats supported by HTML?<br>
ANS : 
1. Images: jpg, jpeg, png, gif, svg, apng, BMP ico
2. Audio: RealAudio, WMA, MIDI, AAC, WAV, MP3, MP4 
3. Video: MPEG, AVI, QuickTime, RealVideo, WMV, Flash, WebM, and MP4 


  
  
  


  
  
  
  
  
  
  
  

  




