# Welcome to the ReadMe for this Project

Hoping there is no merge conflict!

Emoji are also supported in Markdown! :thumbsup: :shipit:
See the [Emoji Cheat Sheet](http:http://emoji-cheat-sheet.com) for the complete list.

You can learn more about Markdown here - and you can also create a link automatically like this - https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf

SAMPLE TEXT

## More about Markdown

First, the simple stuff: *This is Italic* **This is Bold**

You can also create unordered lists:

* Item 1
* Item 2
* Item 3
* Item 5

And also ordered lists (of course):

1. Item 1
2. Item 2
3. Item 3
4. Item 4
1. testing if I can really put any number in the markdown. I typed a "1", but a "4" should show up.
   * Item 3a
   * Item 3b

## Task Lists

Can be handy to keep track of things to do:

- [x] Task one is done
- [x] Task two is done
- [x] Task three is done
- [ ] This task is not yet done

## Code Blocks

Are easy; just open and close with three backticks.

```javascript
var first
    var name
    first = name = prompt("Enter new name, or OK to end")
    while (name != "" && name != null) {
    	if (name < first)
		first = name
    	name = prompt("Enter new name, or OK to end")
    }
    document.write("

 First name alphabetically = " + first)
