# Markdown Syntax

## \#\# Paragraph and headings \#\#

#### Example:
```
This is a short paragraph (p)

This is a long paragraph where we have not given a line break as a result, it will be rendered into a single block in your readme.md file. If you want to write a long paragraph block, do not break that into multiple paragraphs.

This is a long paragraph where we have given a line break. 

As a result, it will be rendered into multiple blocks in your readme.md file.

<!--- And this block will not get rendered, not visible in readme.md and used as comment --->

# This is Heading1 (H1)
## This is Heading2 (H2)
### This is Heading3 (H3)
#### This is Heading4 (H4)
##### This is Heading5 (H5)
###### This is Heading6 (H6)
```

#### Rendered Output:
This is a short paragraph (p)

This is a long paragraph where we have not given a line break as a result, it will be rendered into a single block in your readme.md file. If you want to write a long paragraph block, do not break that into multiple paragraphs.

This is a long paragraph where we have given a line break. 

As a result, it will be rendered into multiple blocks in your readme.md file.

<!--- And this block will not get rendered, not visible in readme.md and used as comment --->

# This is Heading1 (H1)
## This is Heading2 (H2)
### This is Heading3 (H3)
#### This is Heading4 (H4)
##### This is Heading5 (H5)
###### This is Heading6 (H6)
---
## \#\# Text formatting \#\#

#### Markdown uses combination of special characters to format text. Below table list most common text formatting options available in Markdown language.
| Style |	Syntax |
| --- | --- |
| Bold	| \*\*text\*\* or \_\_text\_\_ |
| Italic	| \*text\* or \_text\_ |
| Strike	| \~\~text\~\~ |
| Code | \`code\` |
| Quote	| \> quote |

#### Examples:

```
This is a plain text

This is a **bold** text

This is an _italic_ text

This is a ~~strike through~~ text

This is a `code` block

**This is _italic_ within bold text**

**This is ~~strike through~~ within bold text**

_This is ~~strike through~~ within italic text_

***This is bold and italic text***

**~~This is bold and strike through text~~**

_~~This is italic and strike through text~~_

> This is a quote block
>
>> This is a quote block within quote block
```

#### Rendered Output:

This is a plain text

This is a **bold** text

This is an _italic_ text

This is a ~~strike through~~ text

This is a `code` block

**This is _italic_ within bold text**

**This is ~~strike through~~ within bold text**

_This is ~~strike through~~ within italic text_

***This is bold and italic text***

**~~This is bold and strike through text~~**

_~~This is italic and strike through text~~_

> This is a quote block
>
>> This is a quote block within quote block
---
## \#\# Footnote \#\#

#### You can use caret `[^.]` sign followed by number or words to insert a footnote in your README.md file. Footnotes are used to add reference in your documents and is rendered at the bottom of the page.

#### Examples
```
Markdown is a lightweight markup language[^1] for creating formatted text.

John Gruber[^2] and Aaron Swartz[^3] created Markdown in 2004 as a markup language

Markdown language is used to write README[^readme] files.

[^1]: A lightweight markup language (LML), also termed a simple or humane markup language, is a markup language with simple, unobtrusive syntax. 
  It is designed to be easy to write using any generic text editor and easy to read in its raw form. 
  Lightweight markup languages are used in applications where it may be necessary to read the raw document as well as the final rendered output.
[^2]: John Gruber (born 1973) is a technology blogger, UI designer, and one of the inventors of the Markdown markup language. 
[^3]: Aaron Hillel Swartz (November 8, 1986 – January 11, 2013) was an American computer programmer, entrepreneur, writer, political organizer, and Internet hacktivist. He was involved in the development of the web feed format RSS, the Markdown publishing format, the organization Creative Commons, and the website framework web.py, and joined the social news site Reddit six months after its founding.
[^readme]:
    A README file contains information about the other files in a directory or archive of computer software.
    A form of documentation, it is usually a simple plain text file called README, Read Me, READ.ME, README.TXT, README.md (to indicate the use of Markdown), or README.1ST
```

#### Rendered Output:

Markdown is a lightweight markup language[^1] for creating formatted text.

John Gruber[^2] and Aaron Swartz[^3] created Markdown in 2004 as a markup language

Markdown language is used to write README[^readme] files.

[^1]: A lightweight markup language (LML), also termed a simple or humane markup language, is a markup language with simple, unobtrusive syntax. 
  It is designed to be easy to write using any generic text editor and easy to read in its raw form. 
  Lightweight markup languages are used in applications where it may be necessary to read the raw document as well as the final rendered output.
[^2]: John Gruber (born 1973) is a technology blogger, UI designer, and one of the inventors of the Markdown markup language. 
[^3]: Aaron Hillel Swartz (November 8, 1986 – January 11, 2013) was an American computer programmer, entrepreneur, writer, political organizer, and Internet hacktivist. He was involved in the development of the web feed format RSS, the Markdown publishing format, the organization Creative Commons, and the website framework web.py, and joined the social news site Reddit six months after its founding.
[^readme]:
    A README file contains information about the other files in a directory or archive of computer software.
    A form of documentation, it is usually a simple plain text file called README, Read Me, READ.ME, README.TXT, README.md (to indicate the use of Markdown), or README.1ST

---
## \#\# Horizontal rules \#\#

#### You can use three hyphens `---` , asterisks `***` or under scores `___` to insert a horizontal line in README.md file.

#### Examples:
```
---
line one
***
line two
___
line three
- - - -
line four
* * * *
line five
_ _ _ _
```

#### Rendered Output:

---
line one
***
line two
___
line three
- - - -
line four
* * * *
line five
_ _ _ _

<br>

## \#\# Code snippet \#\#

#### Examples:

Use \`echo Hello World!\` command to print in shell

Use below code to print in java


\`\`\`
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World!"); 
    }
}
\`\`\`

Same java code with syntax highlight

\`\`\`java
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World!"); 
    }
}
\`\`\`


#### Rendered Output:

Use `echo Hello World!` command to print in shell

Use below code to print in java
```
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World!"); 
    }
}
```

Same java code with syntax highlight
```java
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World!"); 
    }
}
```
---
<br>

## \#\# List \#\#

#### Examples:

```
### Ordered List
1. First item
2. Second item
    1. First sub item
    2. Second sub item
        1. First sub sub item
3. Third item
4. Fourth item

### Unordered List
- First item
- Second item
    - First sub item
    - Second sub item
        - First sub sub item
- Third item
- Fourth item

### Task List
- [x] First item
- [ ] Second item
    - [ ] First sub item
    - [x] Second sub item
        - [x] First sub sub item
- [ ] Third item
- [ ] Fourth item
```

#### Rendered Output:

### Ordered List
1. First item
2. Second item
    1. First sub item
    2. Second sub item
        1. First sub sub item
3. Third item
4. Fourth item

### Unordered List
- First item
- Second item
    - First sub item
    - Second sub item
        - First sub sub item
- Third item
- Fourth item

### Task List
- [x] First item
- [ ] Second item
    - [ ] First sub item
    - [x] Second sub item
        - [x] First sub sub item
- [ ] Third item
- [ ] Fourth item

---
<br>

## \#\# Tables \#\#

#### Examples:
```
### Tables

| heading1 | heading2 |
| -------- | -------- |
| 11       | 12       |

| heading1 | heading2 |
| --- | --- |
| 11 | 12 |
| 21 | 22 |

### Tables alignment 

| heading1 | heading2 | heading3 |
| :--- | :---: | ---: |
| left | center | right |
| **bold** | _italic_ | ~~strike~~ |
```

#### Rendered Output:

### Tables

| heading1 | heading2 |
| -------- | -------- |
| 11       | 12       |

| heading1 | heading2 |
| --- | --- |
| 11 | 12 |
| 21 | 22 |

### Tables alignment 

| heading1 | heading2 | heading3 |
| :--- | :---: | ---: |
| left | center | right |
| **bold** | _italic_ | ~~strike~~ |

---
<br>

## \#\# Collapsed section \#\#


#### Examples":

```
<details><summary>Get details</summary>

### This section is hidden until you press "Get details"

You can include any markdown block here for view!

</details>
```

#### Rendered Output:

<details><summary>Get details</summary>

### This section is hidden until you press "Get details"

You can include any markdown block here for view!

</details>

---
<br>

## \#\# Links \#\#

#### You can create an inline link by wrapping link text in brackets [ ], and then wrapping the URL in parentheses ( ).

#### Examples:

```
### External links

Welcome to [CloudAffaire](https://cloudaffaire.com)

This will autolink https://cloudaffaire.com

This will not autolink `https://cloudaffaire.com`

### Selection links

Here is a link to [code snippet](https://github.com/CloudAffaire/Markdown#-code-snippet-) covered earlier. 

### Relative links

Here is a [link](docs/author.md) to another markdown file!
```
#### Rendered Output:

### External links

Welcome to [CloudAffaire](https://cloudaffaire.com)

This will autolink https://cloudaffaire.com

This will not autolink `https://cloudaffaire.com`

### Selection links

Here is a link to [code snippet](https://github.com/CloudAffaire/Markdown#-code-snippet-) covered earlier. 

### Relative links

Here is a [link](docs/author.md) to another markdown file!

---
<br>

## \#\# Images \#\#

#### To add an image, add an exclamation mark (!), followed by alt text in brackets, and the path or URL to the image asset in parentheses. You can optionally add a title after the URL in the parentheses. To add a link to an image, enclose the Markdown for the image in brackets, and then add the link in parentheses. You can also resize the image using HTML img tag which is supported by most sites.

#### Examples:
```
### Internal Image

![image not found](images/cloudaffaire.png "CloudAffaire")

### External Image

![image not found](https://cloudaffaire.com/wp-content/uploads/2018/09/LOGO11.png "CloudAffaire")

### Anchor Image

[![image not found](images/cloudaffaire.png "CloudAffaire")](https://cloudaffaire.com)

### Resized Image
<img src="images/cloudaffaire.png" alt="image not found" width="200" height="200"/>
```

#### Rendered Output:
### Internal Image

![image not found](images/cloudaffaire.png "CloudAffaire")

### External Image

![image not found](https://cloudaffaire.com/wp-content/uploads/2018/09/LOGO11.png "CloudAffaire")

### Anchor Image

[![image not found](images/cloudaffaire.png "CloudAffaire")](https://cloudaffaire.com)

### Resized Image
<img src="images/cloudaffaire.png" alt="image not found" width="200" height="200"/>

---
<br>

## \#\# Escape Special Characters \#\#

### Without escape
You can escape special characters like:
backslash `\`
backtick \`
asterisk `*`
underscore `_`
curly braces `{}`
square brackets `[]`
angle brackets `<>`
parentheses `()`
hash `#`
plus sigh `+`
hyphen `-`
dot `.`
exclamation mark `!`
and pipe `|`
in markdown using backslash `\`
