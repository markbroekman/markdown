<!-- Mark's Markdown cheatsheet -->
### Format / Opmaak 
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

<!-- Italics -->
*This text* is italic

_This text_ is italic

<!-- Strong -->
**This text** is strong

__This text__ is strong

<!-- Strikethrough -->
~~This text~~ is strikethrough

<!-- Horizontal rule -->
- - - 
___

<!-- Escape special characters -->
\*This text\* heeft escaped special characters

<!-- Block quote -->
### Block quote
> This is a block quote

&nbsp;
<!-- Links -->
### Links
[Nu.nl](http://www.nu.nl)

[De Stentor](www.destentor.nl "Krant van Deventer")

<!-- UL -->
### Ongeordende lijst
* Item 1
* Item 2
* Item 3
    * Genest item 1 (door tab)
    * Genest item 2

<!-- OL -->
### Geordende lijst
1. Item 1
1. Item 2
1. Item 3

&nbsp;

<!-- Inline codeblock -->
### Inline codeblock

`<p>This is a paragraph</p>`

<!-- Images -->
### Images

![Markdown logo](https://markdown-here.com/img/icon256.png)

<!-- Github Markdown -->


<!-- Code blocks -->
## Code blocks (with language)

``` bash
npm install

npm start

```

```javascript
function add(num1, num2) {
    return num1 + num2;
}
```

```python
def add(num1, num2):
    return num1 + num2
```

<!-- Tables -->
## Tables 

In overzichtelijke brontekst
| Naam        | id   | Email               |
| ---         | ---  | ---                 |
| Mark        | 1    | info@mark.nl        |
| Lotte       | 2    | postvoor@lotte.nl   |
| Rebuma      | 3    | briefvoor@rebuma.et |

Met minder uitlijning:
| Naam | id | email |
| - | -| -|
| Dit | kan|ook|
|Stel dat je een hele lange naam hebt|2|info@nu.nl|

<!-- Task lists -->
Task list
* [x] Task 1 (checked)
* [ ] Task 2 (unchecked)
* [ ] Task 3