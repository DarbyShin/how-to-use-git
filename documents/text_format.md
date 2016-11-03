This document is to test the format of text in github.  

Line 1: format applied  
Line 2: plane text  
Line 3: how to apply  

#The largest heading  
The largest heading
```
#The largest heading
```  
##The second largest heading  
The second largest heading
```
##The second largest heading
```  
#####The smallest heading  
The smallest heading
```
#####The smallest heading
```  
**This is Bold text**  
This is Bold text
```
**This is Bold text**
```  
*This text is italicized*  
This text is italicized
```
*This text is italicized*
_This text is italicized_
```  
~~This is strikethrough~~  
This is strikethrough
```
~~This is strikethrough~~
```  
**Bold with _Italic text_ format**  
Bold with Italic text format
```
**Bold with _Italic text_ format**
```  
>Quoting line  

Quoting line
```
>Quoting line
```  
`Quoting` word  
Quoting word
```
`Quoting` word
```  
```
Quoting
paragraph
```
Quoting
paragraph
```
.```
Quoting
Paragraph
.``` (remove dots)
```  
This is [Jack's github link](https://github.com/pwcasdf)  
This is Jack's github link
```
This is [Jack's github link](https://github.com/pwcasdf)
```  
- List 1
- List 2
- List 3
```
- List 1
- List 2
- List 3
```  
1. List 1  
2. List 2  
3. List 3  
```
1. List 1
2. List 2
3. List 3
```  
1. List1
    1. List 1-1
    2. List 1-2
        * List 1-3
2. List 2
    1. List 2-1
    2. List 2-2
        * List 2-3  
```
1. List1
    1. List 1-1
    2. List 1-2
        * List 1-3
2. List 2
    1. List 2-1
    2. List 2-2
        * List 2-3  
(4 spaces)
```  
- [x] check box1
- [ ] check box2
```
- [x] check box1
- [ ] check box2
```  
| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |
```
| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |
```  
| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff \|   |
```
| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff \|   |
```  
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
```
.```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
.``` (remove dots)
```  
