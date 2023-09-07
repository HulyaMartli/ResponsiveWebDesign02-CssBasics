# CSS3

* Type selectors => body, h1, nav, etc.

* ***For the styling of the page to look similar on mobile*** as it does on a desktop or laptop:  

  ~~~~
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  ~~~~

* The **div element** is used **mainly for design layout purposes** unlike the other content elements

* To **center an element horizontally** set its ***margin-left*** and ***margin-right*** properties to ***auto***.

* The \<article> tag specifies independent, self-contained content. Examples include: a forum post, a magazine or newspaper article, or a blog entry, a product card, a user-submitted comment, an interactive widget or gadget, or any other independent item of content. 
  ~~~~
  <article>
  	<h2>Google Chrome</h2>
  	<p>Google Chrome is a web browser developed by Google, released in 2008. Chrome is the world's most popular web browser today!</p>
  </article>
  ~~~~

* Block elements behave more like inline elements with **display: inline-block;**  property.

  > Check display property from mdn docs further

* The :root selector matches the document's root element. In HTML, **the root element is always the html element**.  
  ~~~~
  :root {
      --font--size--lg: 40px;
      --font--size--md: 30px;
  }
  ~~~~

* **a pseudo-selector**:  

  ~~~~
  a:visited { 
  	color: purple;
  }
  ~~~~

* **To center** an horizontally element:  

  ~~~~
  img {
      display: block;
      margin: 0 auto;
  }
  ~~~~

> Study again!!! => flex prop
