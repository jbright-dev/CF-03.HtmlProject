a# Coder Foundry: HTML
## *Introduction to HTML*<hr>

## Key Terms
- <u>HTML-</u> Hypertext Markup language; contains a set of annotations that tell a browser how to display a web pages content
  
- <u>Hypertext-</u> hypertext refers to links that connect webpages to each other, either within a single website or between websites
  
- <u>Markup-</u> markup, or tags, are used by html to annotate content; each piece of markup will be found between a set of open and closed angle brackets; tags are used to produced elements and elements tell the browser how to produce content
  
- <u>Semantic HTML-</u> elements such as header, nav,section, article, aside, and footer which clearly define it's content 
  
- <u>NonSemantic HTML-</u> elements such as div, span, which say nonthing about the content

- <u>HTML Attributes-</u>All elements within HTML have attributes, which are additional elements that configure the element or adjust the behavior in some way; always specified in teh start or opening tag and usually come in name value pairs, such as:  
```
<HTML TAG>
```
<hr>

## Section 1 notes
- Some elements such as the "Meta" tag only need an open element while other elements such as "title" need an open and closing tag. ex:
  ```
  <meta charset="utf-8">; <title> </title>
  ```


- All HTML5 pages require the the document type tag:
  ```
  <!DOCTYPE html>
  ```
    this ensures the format is porperly processed by the browser


- The html element represents the root element, or the top level element of an html document; all other elements must be a descendent of this element
    ```
    <html></html>
    ```


- The head element contains metadata, or machine readable information about the document such as title or scripts and data
    ```
    <head>
    ```


- The meta element contains data that can't be represented by other elements such as charset, name, item prop, http equivalent
    ```
    <meta>
    ```

- The title element defines the document's title that is shown in a browser's title bar the pages tab; it only contains text; tags within the element are generally ignored
    ```
    <title></title>
    ```


- The body elements represents the content of an HTML Document, there can only be one body element in an HTML document
  ```
  <body></body>
  ```
<hr>

## Section 2 notes

- the header element represents introductory content such as a group of introductory or navigational aids, may contain some heading elements, but also things such as logos, search forms, author names, etc
    ```
    <header>
    ```


- The nav elements represents the section of the page who'e purpose is to provide navigation links, whether within the current document or with other documents such as menus, TOC, and indexes
  ```
  <nav>
  ```


- The section elements represents a generic stand alone section of a document, which doesn't have a more specific semantic element to represent it; sections should always have a heading, with very few exceptions
  ```
  <section>
  ```
  

- The article element represents a self contained composition within a document page, application, or site, which is intended to be independently distributible or reusable; such as a foreign post, magazine or newspaper article, or blog entry
  ```
  <article>
  ```

- The aside element represents a portion of the document who's content is only indirectly related to the documents main content; frequently presented as side boxes or call out boxes
  ```
  <aside>
  ```


- The footer element represents a footer for it's nearest sectioning content or sectioning root elemetn; typically contains author information, copyright data, or links to related documents
  ```
  <footer>
  ```


### Full list of Semantic elements

- Article, aside, details, figcaption, figure, footer, header, main, mark, nav, section, summary, time.
  
## Section 3 notes

- All elements within HTML have attributes, which are additional elements that configure the element or adjust the behavior in some way; always specified in teh start or opening tag and usually come in name value pairs, such as:  
    ```
    <name="inserted value">
    ```


- The header title attribute allows for the title desription when hovered on
  ```
  <header title="insert text"></header title>
  ```


- classes can be added to adjust colors outside of the style sheet
  ```
  <nav class="col text-center h2 *bg-warning*">
  ```
  

- Not all tags come with the same attributes, for example: Anchor tags come with an href and target attribute; img tags come with the source attribute and alt attribute; etc. 
  ```
  <a href="httpw://www.website.com">anchor tag</a> - takes us to a new page on the same tab
  <a href="https://www.website.com" target="_blank"> - takes us to a new page in a different tab
  <img src="/path.ico">= points to a path
  <ul class="mt-4 style="list-style-type: none;"> - this style removes the bu*llet from lists
  <img src="/path.ico""alt="> - This shows up when the image is missing> - the alt is placer text for broken image links
  <img src="/path.ico" height="50px" width="50px"> this inline style adjusts the height and width of an image
  ```

- Attributes can be combined within the same element
  ```
  <article class="col text-center h2 bg-secondary" style="color: white" title "Attributes">
  ```


- The header tag includes machine readable metadata
  ```
  <Title></Title>- Page Title
  <meta charset="UTF-8"> - The character Set
  <meta name="author" content="Jason Bright"> - Author designation and content
  <meta name="viewport" content="width=device-width, initial-scale=1.0> - Adjust width to device (Repsonsive)
  <link> style links
  <script></script> scripts
  ```


- The body element represents the content of an html document; possess several attributes such as: background, bg-color, margin, etc. however, these are nonconforming and css should be used instead;
  ```
  <body onload=" ">- calles a function
    <p></p> - paragraph attribute, shows text
  ```

## Diagram 
![Project Diagram](diagrams/CRPDiagram.png)<hr>



## License
<hr>
