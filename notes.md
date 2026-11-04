# **PYTHON Notes**  

<!-- In order to create a new line within markdown you need to add two spaces at the end on each line that you are wanting there to be a break -->
  
**Testing this feature**  
*Testing*  
***Testing this one as well***  

<!-- Note: Adding whitespace to strings with tabs or newlines. -->   

### *Whitespace, newlines and code blocks*  

> You can add a tab to your text, by using the character combination "\t".
>  
> ```python
> def hello_world():
>     print("Hello from inside a blockquote!")
> ```
> 
> You can add a newline in a string by using "\n".
>
> You can combine tabs and newlines in a single string "\n\t" which will start a new line indented.  

### *Stripping Whitespace*  

> It’s important to think about whitespace, because often you’ll want to compare two strings to determine whether they are the same. For example, one important instance might involve checking people’s usernames when they log in to a website. Extra whitespace can be confusing in much simpler situations as well. Fortunately, Python makes it easy to eliminate extra whitespace from data that people enter.

> Python can look for extra whitespace on the right and left sides of a string. To ensure that no whitespace exists at the right side of a string, use the rstrip() method:
> ```python
> favorite_language = ' python '
> favorite_language.rstrip()
> ' python'
> favorite_language.lstrip()
> 'python '
> favorite_language.strip()
> 'python'
> ```  
>
> This is only a temporary removal of whitespace.  

### *Removing Prefixes*  

> Example: nostarch_url = 'https://nostarch.com'  
> https://. We want to remove this prefix, so we can focus on just the part of the URL that users need to enter into an address bar.
> nostarch_url.removeprefix('https://')

