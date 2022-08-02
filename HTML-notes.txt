## HTML basic Syntax

# Header-Syntax

<h1>"header"</h1>   // Numbers 1-6 work here //

# Paragraph

<p>"paragraph"</p>   // normally text that is input following your headrer //

# Images

<img src="file or link">   // The image source can be included by adding the file or "save/copy image address"

<img src-"file" width"100%"> // Width is an html tool that scales image (instead of CSS) //   // CSS method is correct way, this is just a tip //

# Nesting

Divs: Divs are used for grouping lines of code to add styling with CSS or manipulate with javascript

    - You can have divs within divs based on what you want styled the same or different

Example:

<div>   
    
    <h1>Keyboard Finder</h1>

    <div>
        <img src="keyboard.jpg>
    </div>

</div>

# Button

<button>button name</button>   // displays button on website. Functionality is included with javascript //

# input

The input tag is a versitile tool used for many aspects of designing a website. There are many elememts with this tag, here are a few basic elelemts

<input type="text">   // This inserts a textbox on the website //

<input type="text" placeholder="anything">   // This displays placeholder text in text box, before you begin to type. Ex: "Enter Username" //

<input type="password">   // This creates a textbox where the input is masked. Ex: Used for password input //

<input type="date">   // This creates a textbox where you can select a date //

<input type="time">   // This creates a textbox where you can select a time //

<input type="color">   // This creates a textbox where you are promot with a color picker //

<input type="file">   // Select file from local files //

# Anchor Tags

<a href="the link">Hyperlinked text</a>   // hypertext refrence inbeds the link within the text of the anchor tag //

<a href="the link" target="_blank">Hyperlinked Text</a>   // This will open up new tab when clicking on hyperlink //

# Document Structure

Structuring your code is important when building a website.

<!doctype html>   // Ensures that you are using the latest version of HTML when depolying to a website //

<html> all code </html>   // All sourcecode embedded within these tags //

<head> Metadata </head>   // Include styles, titles, scripts, etc. //

<body> Tags </body>   // Include tags you see on the page (ex: img, input, button, paragraph, anchor) //

Example below:

<!doctype html>
<html>
    <head></head>
    <body>
        <h1>Not much to see here</h1>
        <p>Return <a href="index.html">back to Google.</a></p>
    </body>
</html>

#Lists

2 types of tags are used to make a list on a website. Wrapper tags are used to wrap the list; li tag is for each list item

<ol> list content </ol>   // wraps list to be ordered numerically //

<ul> list content </ul>   // wraps list to be unordered with bullet points //

<li> each list item </li>   // displays each output within wraps list //

Example:

<!doctype html>
<html>
    <head></head>
    <body>
        <p>My top 3 favorite foods!</p>
        <ol>
            <li>Pizza</li>
            <li>Enchaladas</li>
            <li>Soup</li>
        </ol>
    </body>
</html>

#Personal Webpage

Head was included in the class

<!doctype html>
<html>
    <head>
        <link rel="stylesheet" href="styles.css" />
        <link href="https://fonts.googleapis.com/css2?family=Bangers&family=Black+Ops+One&family=Creepster&family=La+Belle+Aurore&family=MedievalSharp&family=Orbitron&family=Rye&display=swap" rel="stylesheet">
        <script src="index.js"></script>
    </head>
    <body>
        <img src="cropped.jpg"><h2>Hello, my name is Steven Maneri</h2>
        <h4>Fun facts about me</h4>
        <ol>
            <li>I'm 6'5</li>
            <li>I like to longboard</li>
            <li>I like build keyboards and computers</li>
            <li>I like to play videogames</li>
        </ol>
        <h5>Please connect with me on <a href="https://www.linkedin.com/in/steven-maneri-41b59319b/LinkedIn">LinkedIn</a></h5>
        <input type="text" placeholder="Email here.."> <button>Join Newsletter</button>
    </body>
</html>