Markdown Quick Reference Guide
===
This is a wuck reference guide for various Markdown syntax. Please enjoy!

Headings
---
* Prefix ```#``` to what you want your heading to be, the more ```#``` prefixed the smaller the heading will be
* Headers can be underlined using ```=``` or ```-```.

Example usage:

    # Header one
    ## Header two
    ### Header three
    #### Header four

    Sub-header one
    ====
    Sub-header two
    ---

Italics and Bold
---
* Specific words or whole phrases can be italicized by wrapping it in ```*``` or ```_```.
* Specific words or whole phrases can be italicized by wrapping it in ```**``` or ```__```.
* These effects can be combined.

Example usage:

    Those words are *italicized*.
    Those words are **bolded**.
    Those words are **_bolded and italicized_**.

Lists and nested lists
---
* Lists can either be ordered or unordered.
* To create an ordered list begin the list item with ```n.``` where ```n``` is the number of the list item.
* To create an unordered list being each item with an ```*```.
* Lists can be nested by using white space to indent the nested items.

Example usage:
    
    1. Lather
    2. Rinse
    3. Repeat
    
    * Milk
    * Eggs
    * Cheese

    1. Lather
        * with milk
    2. Rinse
        * the eggs
    3. Repeat
        * and eat the cheeese

Block Quotes
---
* Block quotes can be used by appening ```>``` to anything that should be within the block quote.

Example usage:

    > This is inside of the quote.
    > And so is this.
    > Also this.

Code
---
* To insert code into your Mardkwon documents surrounding the code with at least 1 `` ` `` on each side.
* You can indacte syntac highlighting specific to a language by adding the name of the language after the opening `` ` ``s, for this to work you must use at least 3 `` ` ``.

Example usage:
    
    ``cout << "Hello, world!" << endl;``
    
    ```python
    x = "Hello, world!"
    print x
    ```
Links and Images
---
* Links can be embedded through the syntax ```[word or words](the link)```
* Images can be inserted with the syntax ```![alt text](url or path of image)```

Example usage:

    [This link will take you to a website!](https://google.com)
    
    Only the last word will take you to a [website](https://google.com)
    
    ![alt text](http://upload.wikimedia.org/wikipedia/en/c/c8/Alan_Turing_photo.jpg)
