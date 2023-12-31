Chapter 1: Introduction.

        -> What is HTML?
            1. HTML stands for Hyper Text Markup Language.
            2.HTML is the standard markup language for creating Web pages.
            3.HTML describes the structure of a Web page.
            4.HTML consists of a series of elements.
            5.HTML elements tell the browser how to display the content.
            6.HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.

        -> Opening and Closing tags: 
            opening: <tag>
            closing: </tag>
        
        -> basic structure of html file:
            <html>
                <head>
                    <title> </title>
                </head>
                <body>

                </body>
            </html>
        
        -> HTML tags: 
            The <html> element is the root element of an HTML page.
            The <head> element contains meta information about the HTML page.
            The <title> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab).
            The <body> element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
            The <h1> element defines a large heading.
            The <p> element defines a paragraph.

        -> Element:
            Start tag         Element           End Tag
              <h1>           My Name is          </h1>
              <p>          Soyam kapasiya         </p>
            <title>           My Page           </title>

        -> Self closing tags:
            1. <br/>
            2. <img/>
            3. <input/>
            4. <hr/>
            5. <link/>

Chapter 2: Head Element

        -> Definition and Usage: 
            The <head> element is a container for metadata (data about data) and is placed between the <html> tag and the <body> tag.
            Metadata is data about the HTML document. Metadata is not displayed.            
            Metadata typically define the document title, character set, styles, scripts, and other meta information.
        
        -> Tags inside the head tag:
            1. <title> </title>
            2. <style> </style> 
            3. <link/>
            4. <base>
            5. <meta>
            6. <script> </script>
            7. <noscript> </noscript>
        
        -> CSS File:
            0. CSS Cascading Style Sheets.
            1. CSS is the language we use to style an HTML document.
            2. CSS describes how HTML elements should be displayed.

        -> How to add CSS in html:
            1. Inline - by using the style attribute inside HTML elements.
            2. Internal - by using a <style> </style> element in the <head> </head> section.
            3. External - by using a <link/> element to link to an external CSS file.
            
            
        
(Anime Summer time rendaring)

Chapter 3: Text Basics

        ->  HTML 4 Entity Names:

            1. &lt; tag: Less than.
            2. &nbsp; tag: No-break space.
            3. &gt; tag: Greater than.
            4. &copy; tag; Copyright symbols.

        -> Tags which are used in Text:

            1. <strong></strong> tag: Important text.
            2. <hr> tag: Add line. 
            3. <abbr title=""></abbr> tag: 
            4. <br> tag: Next Line.
            5. <sub></sub> tag: Subscript text.
            6. <sup></sup> tag: Superscript text.
            7. <ins></ins> tag: Inserted text.
            8. <b></b> tag: Bold text.
            9. <del></del> tag: Deleted text.
            10. <i></i> tag: Italic text.

Chapter 4: List Types

        -> Unordered List

            1. An unordered list starts with the <ul> tag. Each list item starts with the <li> tag.
            2. The list items will be marked with bullets (small black circles) by default:
            Example:
                    <ul>
                        <li>Coffee</li>
                        <li>Tea</li>
                        <li>Milk</li>
                     </ul>

        -> Ordered List
        
            1. An ordered list starts with the <ol> tag. Each list item starts with the <li> tag.
            2. The list items will be marked with numbers by default:
            Example:
                    <ol>
                        <li>Coffee</li>
                        <li>Tea</li>
                        <li>Milk</li>
                    </ol>
        
        -> Description Lists
        
            1. HTML also supports description lists.
            2. A description list is a list of terms, with a description of each term.
            3. The <dl> tag defines the description list, the <dt> tag defines the term (name), and the <dd> tag describes each term:

        
        -> Tag Description

            1. <ul>	Defines an unordered list
            2. <ol>	Defines an ordered list
            3. <li>	Defines a list item
            4. <dl>	Defines a description list
            5. <dt>	Defines a term in a description list
            6. <dd>	Describes the term in a description list

Chapter 5: Add Links 

        -> HTML Links - Hyperlinks
            1. HTML links are hyperlinks.
            2. You can click on a link and jump to another document.
            3. When you move the mouse over a link, the mouse arrow will turn into a little hand.

            Syntax:
                    <a href="url">link text</a>

        -> The target Attribute:
        
            1. By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link.
            2. The target attribute specifies where to open the linked document.
            3. The target attribute can have one of the following values:
                
                # self - Default. Opens the document in the same window/tab as it was clicked
                # blank - Opens the document in a new window or tab
                # parent - Opens the document in the parent frame
                # top - Opens the document in the full body of the window
            
        -> Use an Image as a Link
        
            1. To use an image as a link, just put the <img> tag inside the <a> tag:
        
            Example:
                    <a href="About.html">
                        <img src="free-images.avif" alt="lomda" style="width:42px;height:42px;">
                    </a>

Chapter 6: Add Images

        -> HTML Images Syntax
            
            1. The HTML <img> tag is used to embed an image in a web page.
            2. Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.
            3. The <img> tag is empty, it contains attributes only, and does not have a closing tag.
        
            The <img> tag has two required attributes:
        
                # src - Specifies the path to the image.
                # alt - Specifies an alternate text for the image.
                
                Example:- 
                    <img src="james.jpg" alt="James">

Chapter 7 : Semantic Tags 

        -> Semantic Elements in HTML
        
            1. Many web sites contain HTML code like: <div id="nav"> <div class="header"> <div id="footer"> to indicate navigation, header, and footer.
            2. In HTML there are some semantic elements that can be used to define different parts of a web page:  
            
                <article>
                <aside>
                <details>
                <figcaption>
                <figure>
                <footer>
                <header>
                <main>
                <mark>
                <nav>
                <section>
                <summary>
                <time>

        -> HTML <section> Element
            
            1. The <section> element defines a section in a document.
            2. According to W3C's HTML documentation: "A section is a thematic grouping of content, typically with a heading."
            
            Examples of where a <section> element can be used:
            
                Chapters
                Introduction
                News items
                Contact information
        
        -> HTML <article> Element
            
            1. The <article> element specifies independent, self-contained content.
            2. An article should make sense on its own, and it should be possible to distribute it independently from the rest of the web site.
            
            Examples of where the <article> element can be used:
            
                Forum posts
                Blog posts
                User comments
                Product cards
                Newspaper articles

        -> HTML <header> Element
            
            1. The <header> element represents a container for introductory content or a set of navigational links.
            2. A <header> element typically contains:
            
                one or more heading elements (<h1> - <h6>)
                logo or icon
                authorship information
            
        -> HTML <footer> Element
            
            1. The <footer> element defines a footer for a document or section.
            2. A <footer> element typically contains:
            
                authorship information
                copyright information
                contact information
                sitemap
                back to top links
                related documents

        -> HTML <nav> Element

            1. The <nav> element defines a set of navigation links.
                
                Example: 
                    <nav>
                        <a href="/html/">HTML</a> |
                        <a href="/css/">CSS</a> |
                        <a href="/js/">JavaScript</a> |
                        <a href="/jquery/">jQuery</a>
                    </nav>

Chapter 8 : Create Tables

        -> Table Cells
            
            1. Each table cell is defined by a <td> and a </td> tag.
            2. td stands for table data.
            3. Everything between <td> and </td> are the content of the table cell.

            Example :-
                <table>
                    <tr>
                        <td>Emil</td>
                        <td>Tobias</td>
                        <td>Linus</td>
                    </tr>
                </table>
        
        -> Table Rows
        
            1. Each table row starts with a <tr> and ends with a </tr> tag.
            2. tr stands for table row.

            Example :-
                    <table>
                          <tr>
                            <td>Emil</td>
                            <td>Tobias</td>
                            <td>Linus</td>
                          </tr>
                          <tr>
                            <td>16</td>
                            <td>14</td>
                            <td>10</td>
                          </tr>
                    </table>
        
        -> Table Headers
            
            1.Sometimes you want your cells to be table header cells. In those cases use the <th> tag instead of the <td> tag:
            2. th stands for table header.
            
            Example:-
                    <table>
                          <tr>
                            <th>Person 1</th>
                            <th>Person 2</th>
                            <th>Person 3</th>
                        </tr>
                        <tr>
                            <td>Emil</td>
                            <td>Tobias</td>
                            <td>Linus</td>
                        </tr>
                        <tr>
                            <td>16</td>
                            <td>14</td>
                            <td>10</td>
                        </tr>
                    </table>


Chapter 9 : Forms & Inputs 

            ->The HTML <form> element is used to create an HTML form for user input:

            ->The <input> Element
                
                1. The HTML <input> element is the most used form element.
                2. An <input> element can be displayed in many ways, depending on the type attribute.
                3. Here are some examples:

                            Type	                    Description
                    <input type="text">	        Displays a single-line text input field
                    <input type="radio">	    Displays a radio button (for selecting one of many choices)
                    <input type="checkbox">	    Displays a checkbox (for selecting zero or more of many choices)
                    <input type="submit">	    Displays a submit button (for submitting the form)
                    <input type="button">	    Displays a clickable button.

            -> Text Fields
            
                1. The <input type="text"> defines a single-line input field for text input.
                        Example:- 
                                A form with input fields for text:
                                <form>
                                    <label for="fname">First name:</label><br>
                                    <input type="text" id="fname" name="fname"><br>           
                                    <label for="lname">Last name:</label><br>        
                                    <input type="text" id="lname" name="lname">
                                </form>
            
            -> Radio Buttons
            
                1. The <input type="radio"> defines a radio button.
                2. Radio buttons let a user select ONE of a limited number of choices.
            
                Example:-
                A form with radio buttons:
            
                <p>Choose your favorite Web language:</p>
                <form>
                    <input type="radio" id="html" name="fav_language" value="HTML">
                    <label for="html">HTML</label><br>
                    <input type="radio" id="css" name="fav_language" value="CSS">
                    <label for="css">CSS</label><br>
                    <input type="radio" id="javascript" name="fav_language" value="JavaScript">
                    <label for="javascript">JavaScript</label>
                </form>

            -> Checkboxes
            
                1. The <input type="checkbox"> defines a checkbox.
                2. Checkboxes let a user select ZERO or MORE options of a limited number of choices.
            
                Example:-
                A form with checkboxes:

                <form>
                    <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
                    <label for="vehicle1"> I have a bike</label><br>
                    <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
                    <label for="vehicle2"> I have a car</label><br>
                    <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
                    <label for="vehicle3"> I have a boat</label>
                </form>

            -> The Submit Button
            
                1. The <input type="submit"> defines a button for submitting the form data to a form-handler.
                2. The form-handler is typically a file on the server with a script for processing input data.
                3. The form-handler is specified in the form's action attribute.
            
                Example:-
                A form with a submit button:
            
                <form action="/action_page.php">
                    <label for="fname">First name:</label><br>
                    <input type="text" id="fname" name="fname" value="John"><br>
                    <label for="lname">Last name:</label><br>
                    <input type="text" id="lname" name="lname" value="Doe"><br><br>
                    <input type="submit" value="Submit">    
                </form>

            -> The Name Attribute for <input>
            
                1. Notice that each input field must have a name attribute to be submitted.
                2. If the name attribute is omitted, the value of the input field will not be sent at all.
            
                Example:-
                This example will not submit the value of the "First name" input field: 
            
                <form action="/action_page.php">
                    <label for="fname">First name:</label><br>
                    <input type="text" id="fname" value="John"><br><br>
                    <input type="submit" value="Submit">
                </form>

Chapter 10 : Html Project