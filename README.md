# Markdown Tutorial

- [Markdown Tutorial](#markdown-tutorial)
  - [Basic Syntax](#basic-syntax)
    - [Headings](#headings)
- [Heading 1](#heading-1)
  - [Heading 2](#heading-2)
    - [Heading 3](#heading-3)
      - [Heading 4](#heading-4)
        - [Heading 5](#heading-5)
          - [Heading 6](#heading-6)
  - [Text Formatting](#text-formatting)
    - [Italics](#italics)
    - [Bold](#bold)
    - [Strikethrough](#strikethrough)
  - [Blockquote](#blockquote)
    - [Multiple Blockquote](#multiple-blockquote)
    - [Nested Blockquote](#nested-blockquote)
  - [Links](#links)
    - [Links over Title](#links-over-title)
    - [Links - Relative Links](#links---relative-links)
    - [Links - Reference Style Links](#links---reference-style-links)
  - [Lists](#lists)
    - [Unordered List](#unordered-list)
    - [Ordered List](#ordered-list)
    - [Nested lists](#nested-lists)
  - [Images](#images)
  - [Extended Syntax](#extended-syntax)
  - [Task Lists](#task-lists)
  - [Tables](#tables)
    - [Tables Alignment](#tables-alignment)
  - [CSS Style](#css-style)
    - [Entities](#entities)
  - [Code Block](#code-block)
    - [Code Block - Bash](#code-block---bash)
    - [Code Block - JavaScript](#code-block---javascript)
    - [Code Block - Python](#code-block---python)
  - [Emoji](#emoji)
  - [Toggle](#toggle)
  - [Callouts](#callouts)
## Basic Syntax

### Headings

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

## Text Formatting

### Italics

This text is *italic*

This text is _italic_

### Bold

This text is **bold**

This text is __bold__

### Strikethrough

This text is ~~strikethrough~~

## Blockquote

> This is a quote

### Multiple Blockquote

> This is multiple quote
>
> This is multiple quote

### Nested Blockquote

> This is multiple quote
>
>> This is nested quote
> 
> This is multiple quote

## Links

[Mercedes Benz](https://www.mercedes-benz.com/en/)

### Links over Title

[Mercedes Benz](https://www.mercedes-benz.com/en/ "Mercedes Benz")

### Links - Relative Links

[Go to music](/music/)

### Links - Reference Style Links

[Click this link][RR] for more info about Rolls Royce!

[RR]: https://www.rolls-roycemotorcars.com/en_GB/home.html/ "Cool!"

## Lists

### Unordered List

* List 1
* List 2
* List 3
- List 4

- List 5
- List 6

### Ordered List

1. List 1
2. List 2
3. List 3

### Nested lists

1. First List Item
    - First Nested List Item
        - Second Netsed List Item

## Images

![Maybach - Mercedes Benz](https://images.moneycontrol.com/static-mcnews/2022/03/Mercedes-Maybach_Exterior-2.jpg?impolicy=website&width=770&height=431)

![Maybach](img/maybach.jpg)

## Extended Syntax

## Task Lists

[x] Rolls Royce - Phantom

[x] Rolls Royce - Cullinan

[x] Rolls Royce - Ghost

[] Rolls Royce - Wraith

[] Rolls Royce - Dawn

[] Rolls Royce - Black Badge

[x] Rolls Royce - Spectre

## Tables

|Car Name   |Model       |
|-----------|------------|
|Mercedes   |Maybach     |
|Rolls Royce|Phantom     |

### Tables Alignment

|Car Name   |Model     |Description |
|:---       |   :---:  |        ---:|
|Mercedes   |Maybach   |Marvelous   |  
|Rolls Royce|Phantom   |Awesome     |

## CSS Style

<style>
mark
{
    color:red;
}
</style>
<mark>What is Markdown?</mark>

### Entities

&amp;

&copy;

&rarr;

Copyright &copy; 2022

## Code Block

### Code Block - Bash
```bash
npm install
mpm start
```
### Code Block - JavaScript
```javascript
function add(num1, num2){
    return num1 + num2;
}
```
### Code Block - Python
```python
def add(num1, num2):
    return num1 + num2
```
## Emoji

Awesome! :thumbsup: Performance.

That is so funny! :joy:

## Toggle

<details>
<summary>This is a Toggle</summary>
Contents of taggle.
</details>

## Callouts

> :bulb: **Tip** Remember the >important tips!




