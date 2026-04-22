HTML Review

What does HTML stand for?
Hypertext Markup Language

What is the difference between <head> & <body>
    <head> -> Metadata - read by the browser

    <body> -> This content DISPLAYED in the browser

7 Semantic HTML elements:
    <header>
    <footer>
    <nav>
    <main>
    <article>
    <aside>
    <section>

What attribute does a <a> tag need to create a link?
    href

What is a self-closing HTML tag?
    They are tags that dont have closing tags, aka void elements
    <br>
    <img>

What does <!DOCTYPE html> do?
    This tells the browser that the file is an HTML file.

Every HTML file has the same SKELETON (Boilerplate, template) structure

<!DOCTYPE html>
<html lang="en">
    <head>
        <title></title>
        <link>
        <style></style>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=decive-width", intitial-scale="1.0">
            - Makes the page Responsive
    </head>
    <body>
        <header></header>
        <nav>Contains Navigation Bar Elements</nav>
        <h1>Largets header/most important heading. ONLY ONCE per page</h1>
        <!-- ALL VISIBLE elements go inside the body -->
    </body>
</html>

PART 2: Core HTML Elements
Headings 1 - 6
    <h1> -> There should be only 1 <h1> per page
    <h2> -> Section Titles
    <h3> -> sub-sections
    <h4>
    <h5> -> Fine print
    <h6> -> Finer print (Copy Right statements)

Text elements
    <p> -> paragraph
    <strong> -> bold/important text - semantic weight
    <em> -> italic/emphasized text - semantic weight
    <br> -> line break (void element)
    <u> -> underline
    <hr> -> horizontal row
    <span> -> inline element, does not create a line break
    <mark> -> highlights text

HTML Lists

Unorder List (Bulleted)
- Used for Items with no ranking order
    <ul>
        <li>The</li>
        <li>Binding</li>
        <li>Of</li>
        <li>Issac</li>
    </ul>

Ordered List (Numbered)
- Used for steps
    <ol>
        <li>The</li>
        <li>Binding</li>
        <li>Of</li>
        <li>Issac 2</li>
    </ol>

Links & Images

How do I create a link to sllboces.org
    <a href="https://sllboces.org" target="_blank">SLL BOCES</a>

How do I create a link to a relative path (page in the same directory)
    <a href="about.html">

Link to a file in the content folder
    <a href="content/page.html">Page</a>

A Link to another section of the page
    <a href="#about">Jumpto the About section</a>

A link to send an email
    <a href="mailto:student@sllboces.org">Email Me</a>

Image

What are the two required attributes for <img> tags?
alt - accessibility text
src - file path to the image

<img src="images/hero.jpg" alt="Adirondack Mountains in fall">

What is hot-linking an image
- linking to an image somewhere on the internet
- Placeholder images for design purposes
- Replace hotlinks before publishing the site
- If the hotlinked image gets moved, it will break your design

Part 3 
What is a semantic HTML element?
    Semantic elements descibe the meaning of the content inside the element, not just the way it looks

SEO - Search engine optimization - how search engines rank well-structured pages - moves them higher in the search results

Layout Semantic Elements: header, nav, main, section, aside, footer

Content Semantic Elements: 
<figure></figure> - image with a caption
<figcaption> - caption for a figure image
<time>
<address>
<mark> - highlighted text
<details> / <summary> - expand and collapse more details
