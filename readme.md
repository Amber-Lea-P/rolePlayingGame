Notes:
Developers use HTML and CSS to control the content and styling of a page. And they use JavaScript to make that page interactive.

JavaScript is a powerful scripting language that you can use to make web pages interactive. It's one of the core technologies of the web, along with HTML and CSS. All modern browsers support JavaScript.

Project One: Role Playing Game will cover arrays, strings, objects, functions, loops, if/else statements, and more. 

Steps:
1.) Create an HTML boilerplate: DOCTYPE, html, head, and body, then add a meta tag for the charset. Add a title element and use the text RPG - Dragon Repeller for it. Include a link tag for your stylesheet to link the styles.css file. 

What is charset="UTF-8"? 
    *The charset attribute specifies the character encoding for the HTML document.

        *The HTML5 specification encourages web developers to use the UTF-8 character set, which covers almost all of the characters and symbols in the  world!

2.) To be able to start writing Javascript a script element must be added to the index.html
3.) Assign values to variables:
    Variables can be assigned a value. When you do this while you declare it, this is called initialization. For example: let age = 32;

    When a variable name has multiple words, the convention in JavaScript is to use what's called camelCase. The first word is lowercase, and the first letter of every following word is uppercase. let thisIsCamelCase;

    You can also declare a variable with out initializing it with a value. Remember to end your line with a semi-colon. 
    JavaScript has multiple different data types. 
        Strings are used to store things like words or text. Strings are surrounded with double quotes, single quotes, or backticks. Example: let developer: "Naomi";
        Array: An array can be used to hold multiple values. For example: let order: ["first", "second", "third"];

4.) Before you can make the interactive JavaScript portion of the game (website), you must create the HTML elementw taht will display the game information. 

5.) JavaScript interacts with the HTML using the Document Object Model, or DOM. The DOM is a tree of objects that represents the HTML. You can access the HTML using the document object, which represents your entire HTML document.
    One method for finding specific elements in your HTML is using the querySelector() method. The querySelector() method takes a CSS selector as an argument and returns the first element that matches that selector. For example, to find the <h1> element in your HTML, you would write:
        let h1 = document.querySelector("h1");

        For queries to work, the script element has to be after the html code. IF not the code runs before the browser has finished reading the HTML and your "document.querySelector()" or another DOM will  not see what is inteded to be seen because the browser hasnt processed it yet. This can be rectified by adding the script text right before the ending </body> tag.

** If you are not going to assign a new value to a variable, it is best practice to use the const keyword to declare it instead of the let keyword. This will tell JavaScript to throw an error if you accidentally reassign it.**