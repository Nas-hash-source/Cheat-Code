# Markdown

## Formatting text

Italic: _text_ enclose with an underscore _ or one asterisk, always use asterisk in a middle of sentence

Bold: **text** enclose with two asterisks or two underscores, always use two asterisks in a middle of sentence

NB: you can nest the one within the other

## Header

Use Hash sign (#) plus a space (recommended) for making a header, the number of it will determine the header to one, two or three...

Best practice to leave a blank line before and after the header.

#Header One 

##Header Two

###Header Three

...

######Header Six

You can also use === under the text for level 1, whatever the number of the =! and --- for level 2

## Link in Markdown

### Inline link

[Link to the markdown tutorial where I got those notes](https://www.markdowntutorial.com/), enclose your linked words with [], followed by the link enclosed with ()

### Reference link

Instead of making a lot of inline links for the same website link, enclose your linked words with [], followed with a reference or a variable with another [].

At the end of a markdown document. Assign the variable, should be enclosed again with [] followed by a colon : then after the link

[Link to google][google]

[Link to google again][google]

[google] : www.google.com

## Insert an image

Inserting an image is like adding a link but only, before the first bracket, need a "!"

![Alt text][Image link]

And it can be referenced like the referenced link as well. ANd we declare it at the end of the document

## Blockquote

adding ">" before the blockquote, or adding several ">" if it contains multipled paragraphs

best practice to add a blank line before and after a block quote, you can nest blocquote and other elements in a blockquote

> This is a quote

## List

1) Unordered list, add juste one "*" or "+" or "-" and just one space before the list item

when you have to start the list with a number , especially a dot, you need to escape it by using \

* List number 1
* List number 2

2) Ordered list, add number like "1.space" "2.space"
1. ordered list number 1
2. ordered list number 2

3) Nested list, you just indent one more space and start the list again
* unordered list
 * nested list number 1
 * nested list number 2

4) Recommended not to use over three nested list, and when you want the list like the lines below, you should step one space and write again.
* This is my list
 And I want to align this line to my list above
 Same for it

## Paragraph

Use a blank line to seperate the text, recommended not to indent it literally, for a normal break!

But when you want to assemble and categorize paragraph such as a poem -- add two space after each line of sentences (You can use this technique for the list as well for the sense of assembling)

## Line Break

add two space after the statement, but sometimes it is hard for the editor, so use <br> if your editor supports HTML Tag

## Code Block

Step 4 spaces or one tab, if in a list step 8 spaces or two tabs
    <html>
    <head>
        <title>Code Block</title>
    </head>
    </html>

## Code

Enclose the code with a backtick (`)

Use double backtick if the code contain backtick

### Horizontal Rules

Add a blank line before and after a three asterisks (***) or three dashes (---) or three underscores (___)










