# HTML-CSS
HTML stands for HyperText Markup Language, html is used for creating websites. Most tech people refer html as a skeleton because it does not make decorations it needs help from CSS to make decorations nor make the website function where it needs javascript to make the website fuction.HTML is not case sensitive but we prefer structure of the html code to be written in capital lettters and content in both capital letters and small letters.
In text formating we have to types of tags known as opening tag and closing tag. HTML contain element components known as opening tag,content,and closing tag.HTML has text types known as bold, italic, strong,underline,subscription,superscription, etc. Subscript is used to write che  e.g H2O, and Superscript is used to write in powers e.g 2^3.HTML headlines known as h1,h2,h3,h4,h5,and h6 have different size , h1 is the largest and h6 is the smallest.In paragraphs we have no p1,p2,p3,p4,p5,p6 we only use p.HTML listing only contains 3 elements known as ordered list where list will be numbered, unordered list where list will be in bullet form and definition list where list will be defining term, defining descrition or defifining the list.
HTML QUOTES: there is a difference between q and blockqoute, q is for content(sensentence) to be written inside double qoutes and blockqoutes is for adding space before the sentence.
HTML pre,br,code: br is used to break the content to a new line, it only contains opening tag. Elements that contains opening tag only are refered to self closing tag/void elements.Pre is used to define the block of preformatted text which preserves the text spaces, br,and other formatting characters that are ignored by the web browsers.
Creating Links: Use the <a> element (anchor) with the href attribute specifying the link's destination URL.
Place text, images, or other content between the opening and closing <a> tags to make them clickable.
URL Types:Absolute URLs: Include the entire web address (e.g., https://example.com).
HTTPS vs. HTTP: HTTPS provides better security and is recommended.
Links can be inline or wrapped around various elements.
URLs can be more complex than just the basic format
Working with images: Use the <img> element to display an image.
Four attributes are crucial: src: Specifies the image file location (URL).
alt: Provides alternative text for accessibility and SEO.
width: Sets the image width in pixels.
height: Sets the image height in pixels.
Use GIF for animations and simple graphics.
Use SVG for logos, icons, and scalable graphics.
Use JPG for photographs and images where slight quality loss is acceptable.
Use PNG for graphics with sharp details, text, and screenshots.

The <figure> and <figcaption> elements in HTML work together to provide a semantic way to associate a figure (like an image, diagram, or code snippet) with its caption. 

<figure> element:

Represents a self-contained content, typically visual, that is related to the main flow of the document.
Can be moved or removed without affecting the document's overall structure.
Often used for images, illustrations, diagrams, code listings, etc.
<figcaption> element:

Provides a caption or legend describing the content within its parent <figure> element.
Improves accessibility by offering alternative text for screen readers and other assistive technologies.
Can be placed as the first or last child within the <figure> element.
Only the first encountered <figcaption> is considered the caption for the figure
EXAMPLE FOR <FIGURE> AND <FIGCAPTION>
<figure>
  <img src="image.jpg" alt="A beautiful sunset">
  <figcaption>This is a stunning sunset over the ocean.</figcaption>
</figure>
UNIT :WORKING WITH VIDEO
Adding audio to your webpage is achieved through the <audio> element. This element allows you to specify the audio source using the src attribute, and includes controls for playback like play, pause, and volume by default. You can also provide alternative text for accessibility using the alt attribute. Additionally, consider including multiple source files with different formats to ensure wider browser compatibility. Remember to optimize your audio files for web delivery to balance quality and file size for a smooth user experience.
