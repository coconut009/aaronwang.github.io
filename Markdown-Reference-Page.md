---
title: Markdown Reference Page
date: 2019-08-20 12:10:43
tags: [Technical,Ref_Page, MD] 
description: Short Markdown Reference Sheet
---
 

__<h2>Header Section</h2>__
 
# H1 #
## H2 ##
### H3 ###
#### H4 ####
##### H5 ####
###### H6 ######
 
```java
# H1
## H2
### H3
#### H4
##### H5
###### H6
```
<!-- more -->

__<h2>Emphasis</h2>__


Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strike through uses two tildes. ~~Scratch this.~~


```bash

Bold emphasis, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strike through uses two tildes. ~~Scratch this.~~
```

__<h2>Lists</h2>__
<h3>List item can simply start with the number at the beginning of the line:</h3>

1. this is the first list
2. this can be the second one
3. if you want an unordered list, you can start with asterisks/* plus/+ or  minuses/-
   
* This is an unordered list 
- This one also works
+ and this one

```bash
1. this is the first list
2. this can be the second one
3. if you want an unordered list, you can start with asterisks/* plus/+ or minuses/-
   
* This is an unordered list 
- This one also works
+ and this one
```
## __Link__
[This an inline-style link](https://aaronjianlanwang.github.io/)

[This an inline-style link with title](https://aaronjianlanwang.github.io/ "My Blogger")

[This is a reference-style link][Arbitrary case-insensitive reference text]

[This is a relative reference to a repository file](../blob/master/LICENSE)
 
[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.google.com or <http://www.google.com> and sometimes 
google.com.

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://aaronjianlanwang.github.io/
[1]: https://aaronjianlanwang.github.io/
[link text itself]: https://aaronjianlanwang.github.io/
```bash
[This an inline-style link](https://aaronjianlanwang.github.io/)

[This an inline-style link with title](https://aaronjianlanwang.github.io/ "My Blogger")

[This is a reference-style link][Arbitrary case-insensitive reference text]

[This is a relative reference to a repository file](../blob/master/LICENSE)
 
[You can use numbers for reference-style link definitions][1]

[arbitrary case-insensitive reference text]: https://aaronjianlanwang.github.io/
[1]: https://aaronjianlanwang.github.io/
[link text itself]: https://aaronjianlanwang.github.io/
```

## __Image__
The following imges are all from my blog (hover to see the title text):

Inline-style: 
![alt text](https://aaronjianlanwang.github.io/galleries/img/Bugatti.jpg "LEGO-Bugatti")

Reference-style: 
![alt text][pic]

[pic]: https://aaronjianlanwang.github.io/galleries/Fullmetal-Alchemist/img/s/fa-2.jpg "Iron Hand"

```bash
Inline-style: 
![alt text](https://aaronjianlanwang.github.io/galleries/img/Bugatti.jpg "LEGO-Bugatti")

Reference-style: 
![alt text][pic]

[pic]: https://aaronjianlanwang.github.io/galleries/Fullmetal-Alchemist/img/s/fa-2.jpg "Iron Hand"
```

## __Code and Syntax__
For simple in line code can simply use `back-ticks around the coude section`
```bash
jsut use `back-ticks around the coude section` and the syntax will hightlight
```
for section of code blocks start with 3 back-ticks ``` follow with the language name at the end of the code use 3 back ticks to wrap the code block.
```
    ```javascript
    var s = "this is js syntax highlighting";
    ```
    ```python
    s = "this is python syntax highlighting"
    ```
``` 

```javascript
var s = "this is js syntax highlighting";
```
```python
s = "this is python syntax highlighting"
```
 
## __Inline HTML__
In markdown format it supports the  raw HTML, and it'll mostly work pretty well.
