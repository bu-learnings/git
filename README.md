<!-- 
Headings
Extended this comment over multi lines
 -->

# Sample .md file

Below are sample snippets that can be used to quickly create/edit `.md` file.

## Table of Contents
* [Heading](#heading)
* [Italics](#italics)
* [Bold](#bold)
* [Strikethrough](#strikethrough)
* [BlockQuote](#blockquote)
* [Links](#links)
* [Ordered List](#ordered-list)
* [Unordered List](#unordered-list)
* [Inline Code Block](#inline-code-block)
* [Code Blocks](#code-blocks)
    * [bash](#bash)
    * [python](#python)
    * [javascript](#javascript) 
* [Tables](#tables)
* [Task lists](#task-lists)

### Heading
#### Syntax: 
```
#H1
##H2
###H3
```
#### Output:
## H1
### H2
#### H3
---

### Italics
#### Syntax:
```
_ Text _
```
#### Output:
_text_
___

### Bold
#### Syntax:
```
__ Text __
```
#### Output:
__text__
___

### Strikethrough
#### Syntax:
```
~~ Text ~~
```
#### Output:
~~Text~~
___

### BlockQuote
#### Syntax:
```
>Statement 1
>Statement 2
>Statement 3
```
#### Output:
>Statement 1 \
>Statement 2 \
>Statement 3
___

### Links
#### Syntax:
```
[Display_Link_Name](link_pathname "hoverover_text")
```
#### Output:
[GitHub](https://github.com/KaranVyas "GitHub profile for Karan Vyas")

___

### Unordered List
#### Syntax:
```
* Item 1
* Item 2
* Item 3
```
#### Output:
* Item 1
* Item 2
* Item 3
___

### Ordered List
#### Syntax:
```
1. Item 1
1. Item 2
1. Item 3
```
#### Output:
1. Item 1
1. Item 2
1. Item 3
___

### Inline Code Block
#### Syntax:
```
`Inline code`
```
#### Output:
`Inline code`
___

### Image
#### Syntax:
```
![image](path)
```
#### Output:
![Image][1]
![Image][2]
___

### Code Blocks
### bash
#### Syntax:
\```
bash \
    statement(1) \
    statement(2) \
    statement(n) \
\```
#### Output:
```bash 
    statement(1)
    statement(2)
    statement(n)
```    
___

### python
#### Syntax:
\```
python \
    statement(1) \
    statement(2) \
    statement(n) \
\```
#### Output:
```python 
    statement(1)
    statement(2)
    statement(n)
```    
___

### javascript
#### Syntax:
\```
javascript \
    statement(1) \
    statement(2) \
    statement(n) \
\```
#### Output:
```javascript 
    statement(1)
    statement(2)
    statement(n)
```    
___

### Tables
#### Syntax:
```
| Name  | Attributes  |
|----   |---          |
|       |             |
|       |             |
|       |             |
```
#### Output:
Table syntax : 
| Name  | Attributes  |
|----   |---          |
| Kohli | Batsman         |
|  ABD  | Batsman,WK      |
| Chahal| Spin Bowler     |
___

### Task lists
#### Syntax:
```
* [ ] Task_id 
* [x] Task_id
```
#### Output:
* [ ] Task 1
* [x] Task 2  
___

<!---
If it's a URL/path, please ensure we only reference them in documentation while we keep stacking them below.
--->
[1]: https://logos-download.com/wp-content/uploads/2020/06/Boston_University_Logo_text.png
[2]: Image/ramos.jpg
