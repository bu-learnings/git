<!-- 
Headings
Extended this comment over multi lines
 -->

# Sample .md file

Below are sample snippets that can be used to quickly create/edit `.md` file.

## Table of Contents

* [Unordered List](#unordered-list)

---

>Heading syntax : `##Heading_Name`
>## This is a sub heading
>### Another sub heading 
---

<!-- italics-->
>Italic synatx : `_ Text _` \
>_This text in italic_
___

<!--bold-->
>Bold synatx : `__ Text __` \
__This text in bold__
___

<!--strikethrough-->
>Strikethrough syntax : `~~ Text ~~` \
~~This text is strikethrough~~
___

<!--Horizontal Rule-->
<!--- ___>

<!--BlockQuote-->
>Block quote syntax : `>Statements` \
>It can also be implemented over multiple lines \
>Need to use \\ key for switching to next line
___

<!--Links-->
>Link syntax : `[Display_Link_Name](link_pathname "hoverover_text")`\
>[GitHub](https://github.com/KaranVyas "GitHub profile for Karan Vyas")
___

<!--Unordered List-->
>Unordered List syntax : `* Item_name`
>* Item 1
>* Item 2
>* Item 3

---
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

<!--Ordered List-->
>Ordered List syntax : `1 Item_name`
>1. Item 1
>1. Item 2
>1. Item 3
___

<!--Inline Code Block-->
>Inline Code Block syntax : `` \
>`This is a inline code block`
___

<!--Images-->

>Image syntax : `![image](path)` \
>![Image][1]
>![ramos][2]
___

<!---GitHub Markdown--->

<!---Code Blocks--->

```bash
this is a code block for bash
syntax :  
    ```lang_name 
    statement(1)
    statement(2)
    statement(n)
    ```
```
___

```python
this is a code block for python
print('')
```
___

```javascript
this is a code block for JS
```
___

<!---Tables--->
```
Table syntax : 
| Name  | Attributes  |
|----   |---          |
| Kohli | Batsman         |
|  ABD  | Batsman,WK      |
| Chahal| Spin Bowler     |
```
___

<!---Task lists--->

>Task list syntax : `* [] Task_id`
>* [ ] Task 1
>* [ ] Task 2
>* [x] Task 3

<!---
If it's a URL/path, please ensure we only reference them in documentation while we keep stacking them below.
--->
[1]: https://logos-download.com/wp-content/uploads/2020/06/Boston_University_Logo_text.png
[2]: Image/ramos.jpg
