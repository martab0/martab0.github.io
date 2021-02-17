---
layout: default
title: Markdown syntax
nav_order: 2
---


<!-- Example for normal text -->
Here comes the sun!
<!-- Example for title -->

Sample document
===============

<!-- Here comes the TOC -->
Table of content

- [Sample document](#sample-document)
- [Header of chapter](#header-of-chapter)
- [Header of another chapter](#header-of-another-chapter)
  - [Chapter](#chapter)
  - [Another chapter](#another-chapter)
    - [Lower level chapter](#lower-level-chapter)
- [One more header of chapter](#one-more-header-of-chapter)
- [New header](#new-header)
  - [Sub-header](#sub-header)
  - [Second sub-header](#second-sub-header)

<!-- Example of paragraph of text -->
This is a paragraph of text.

This is another paragraph of text.

This is a paragraph of text. This is a paragraph of text. This is a paragraph of text. This is a paragraph of text. This is a paragraph of text.

This is a line.  
This is another line.
This is not a new line.

<!-- Example of another paragraph -->
Paragraph of text that spans over one line. See how this displays when I write and write and write.
What happens when I press Enter? - Nothing!  
If I want a new line, I put two spaces and then Enter. This is still the same paragraph.

Second paragraph of text.

[PDF with Markdown syntax](/assets/pdfs/markdown-cheatsheet.pdf)

<!-- Example for Bold -->
See how to insert **bold** text!

<!-- Example for Italic  -->
And that's *how italic is defined*.

<!-- Example for Links -->
[Weather](http://meteo.pl)

[Localization](https://localization.pl)

<!-- Example for Images -->
![Alternative text for no image](/assets/images/inglisz.jpg "even longer hover text"){ : style="width: 200px;"}

<!-- Example for linking to another file-->
[Reference text](Reference.md)
[With space](Additional file.md)


<!-- Example for Headers -->
# Header of chapter
This is a paragraph of text. This is a paragraph of text. This is a paragraph of text. This is a paragraph of text. This is a paragraph of text.
# Header of another chapter
This is a paragraph of text. This is a paragraph of text. This is a paragraph of text. This is a paragraph of text. This is a paragraph of text.
## Chapter
Chapter text.
## Another chapter
More chapter text.
### Lower level chapter
Bla bla!
# One more header of chapter
This is a paragraph of text. This is a paragraph of text. This is a paragraph of text. This is a paragraph of text. This is a paragraph of text.
Some text.
# New header
## Sub-header
## Second sub-header

<!-- Just text with equation -->
If x=2 then it's a relatively small x.
<!-- Example for inline code -->
If you specify `x=2;` then your program substitutes 2 for x.
<!-- A block of code -->
Here comes a codeblock:
```
x=2;
y=7;
z=x+y;
```


<!-- Example for Quote -->
A wise man once said: 
>Don't listen to me!  
>Why would you?  

And he was right.

<!-- Example for Bullet List -->
* bullet 
* another bullet
* one more bullet here

<!-- Example for Numbered List -->
1. First point
2. Second point
3. Third point
4. Fourth Point

<!-- Example for Tables -->

| header           | another header        |
| ---------------- | --------------------- |
| row content      | another row content   |
| more row content | even more row content |

Paragraph after table. Business as usual.

Here I am testing an *inline style*{: style="text-decoration: underline; font-style: normal;"}. Let's hope it works.
