# Header 1
## Header 2
### Header 3
________________________________________________________


*italics*  _italics_

**bold** __bold__

**bold and nested _italic_**

***all bold and italic***

~~strikethrough~~

_____________________________________________________________

**Quote using >**

In the words of Abraham Lincoln
> Pardon my French

**Quote inline code** `return 'Some custom error message'` with backticks on either side

**Quote blosks of code:** Fence code with triple back ticks to assign its own block
```
try:
    new_file_name = input("Enter the name of the file you want to make: ")
    if new_file_name.isnumeric():
        raise Exception('Do not use numbers for the file\'s name')
    elif new_file_name.endswith('txt') == False:
        raise FileNotTXTError()
    else:
        raise CustomError()

except Exception as e:
    print("There was a non-specific error!")
    print("Built-In Python error info: ")
```

Or indent code with four spaces

    class CustomError(Exception):
    """  Some custom error info in the DocString  """
    def __str__(self):
        return 'Some custom error message'

    class FileNotTXTError(Exception):
    """  File extension must end with txt to indicate it is a text file  """
    def __str__(self):
        return 'File extension not txt'
        
            
  ______________________________________________________
**Numbered list**

 
1) list item one

    a) sublist a
    
    b) sublist b
3) list item two
4) list item 3

___________________________________________________  
**Unordered list**

* unordered list
- unordered list
+ unordered list

  
___________________________________________________________
**Links**

[Google](https://www.google.com/)

Google search website <https://www.google.com/>


______________________________________________________________


**Table 1. My first table in markdown**

|     **Header1**        |      **Header2**        |      **Header 3**       |
|:------------------     |:-------------------:    |--------------------:    |
|   content goes here    |   and more content      |  plus more here         | 
|  apples                |   bananas               | oranges                 | 

* use colons to the left or right to indicate right and left line adjustment respectively
* use two colons on either side of 3 or more dashes to indicated centered text
_____________________________________________________


Images - inline style
Images – reference style

Code & syntax highlighting

Tables
Blockquotes
Horizontal line across page
Line breaks

	#, ##, ###, …
*italics*     or      _italics_
**bold**    or    __bold__
~~ strikethrough~~
use numbers
use *, + or –
use two trailing spaces
[This is a link to website_name](URL)    or
URL and <URL> will automatically get turned into links
![alt text](URL)
![alt text][logo]
[logo]: URL
fence blocks of code with ‘’’ or indent with four spaces
inline code written as ‘inline code here’
constructed using |,-, and :
use >
use three or more sequential ---, ***, or underscores
hit enter once or twice
