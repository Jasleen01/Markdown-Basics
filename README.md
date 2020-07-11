# Markdown-Undiscovered-Things
# A CLOSER LOOK - Markdown 

*Author~Jasleen Kaur*

Before I knew about Markdown,I have come across files with .md as extensions.However,I never peeped into it to extract all to know about it.But now,as I have gained much knowledge about the language,I cannot resist appreciating its beauty!

Being familiar with HTML,I can surely say that HTML users will find Markdown to be far more easier than it.Yes!it just does **not** use any kind of **formatting tags** at all unlike HTML!Not only this it is widely used and accessible too.It is a light-weight markup language used to format the text appearing on webpages just like HTML.It is used to add formatting elements to plain text documents.

One feature that makes Markdown more likely to be accepted is that it is **portable**.Markdown files can be opened using any app or any device having any Operating System!

Not only this if the current editor stops working then these files can be accessed using another text editing applications too..

The basic process is that .md or.markdown files are first processed using a Markdown application which converts them into HTML files to render output on the screens!

Any text editor and Markdown application like atom can be used for creating .md files.I personally use **vim** editor.And then I save the file and preview it online..Also you can use ReText.It is amazing as it provides you with live preview!

My experience at learning Markdown was amazing..and the same I want it to be yours too..

Let's take a look at some basic concepts of Markdown:

**1.HEADING**

There are six heading levels.
For using each heading level, put the corresponding number of # signs before the text to be formatted.

For e.g

# heading level 1  
This is done by ---\# heading level 1
## heading level 2
This is done by ---\## heading level 2
### heading level 3
This is done by ---\### heading level 3
#### heading level 4
This is done by ---\#### heading level 4
##### heading level 5
This is done by ---\##### heading level 5
Try sixth one!
**2.Paragraph**
It is as easier to do as possible..where you don't require any <p \> and </p\>tags as in HTML.
You just need to have a blank line.eg.

Here is it!

And this Yeah..

Yes..it is as simple as that..

**3.Line Breaks**
To do this you need end a line with two or more spaces and then press return.e.g

I am writing it and    
now I am on the next line!

Well,<br\> can also be used.
 
**4.BOLD**  

A word or a phrase can be made bold using \** at the starting as well as ending of that particular word or phrase.
e.g

**HELLO!**

This is done by-\*\*Hello!**
**Italicize**   

A word or a phrase can be italicized using \* at the starting as well as ending of that particular word or phrase.
e.g

*HELLO!*

This is done by-\*Hello!*

**BOLD AND ITALICIZE**      

A word or a phrase can be made bold and italic using \*** at the starting as well as ending of that particular word or phrase.
e.g

***HELLO!***

This is done by-\*\*\*Hello!***

**BLOCKQUOTES**    

Text can be made to appear blockquoted by using \> (angle bracket)
at the starting of the text.e.g

\> Hi..what's going on?

The text looks like:

> Hi..what's going on?
 
You can also blockquote the text with multiple paragraphs e.g

\>We went on a trip.   
\>   
\>It was awesome. 

The text looks like:

>We went on a trip.  
>  
>It was awesome. 

Nested BLockquote:

\>We went on a trip.   
\>    
\>>It was awesome. 

The text looks like:

>We went on a trip.  
>  
>>It was awesome.

You can also use other elements along with blockquote.e.g

\>\## FRUITS   
\>  
\>\- Apple   
\>\- Orange    
\>\- Guava  
\>    
\> \*Did you get it?*

The text looks like:

>## FRUITS  
>  
>- Apple   
>- Orange  
>- Guava  
>  
> *Did you get it?*

**5.LISTS**

-   ORDERED LISTS

These lists always start from 1. e.g

1. Item 1   
2. Item 2   
1. Item 3   
6. Item 4   

The list would appear like:

1.  Item 1   
2.  Item 2   
3.  Item 3   
4.  Item 4   

**Another way out there**

1.  Item 1    
    1.sub-item 1   
    2.sub-item 2   
2.  Item 2  
3.  Item 3   
4.  Item 4  

The list will appear like:

1.  Item 1   
    1.sub-item 1   
    2.sub-item 2    
2.  Item 2   
3.  Item 3    
4.  Item 4      

Use just need to indent some spaces to begin your sub-list as shown
above..

-   UNORDERED LISTS

Dashes(-),asterisks(\*) or plus signs(+) are used to make unordered
lists.e.g

\- item 1    
\- item 2    
\+ item 3     
\* item 4     

The output is:    

-   item 1    
-   item 2    
-   item 3    
-   item 4    

**Another way out there**

\- item 1    
   \- sub-item1   
   \- sub-item 2    
\- item 2    
\+ item 3    
\* item 4    

It would appear like:

-   item 1    
    - sub-item1    
    - sub-item 2      
-   item 2     
-   item 3    
-   item 4    

**Also other elements can be used along with lists.**

**6.CODE**

If you want to denote a word or a phrase as code,enclose it in
backticks(\`)e.g

At command prompt write \`vim Template.md\`

Output will be:

At command prompt write `vim Template.md`

**7.HORIZONTAL RULE**

HR can be added using three or more (\*)or (-) or (\_).e.g

\*\*\*

This is what appears:

------------------------------------------------------------------------

It is a good practice to leave a blank line after using \*\*\*

**8.LINKS**

You can insert hyperlinks to make your page interactive.\
The syntax is:

\[Link Text Goes Here\](URL)\
This is how it looks!:\
[Link Text Goes Here](URL)

Also you can add title to your link which can be seen when user hovers
the pointer over it.To do this:\
\[Link Text Goes Here\](URL"Title")\
This looks like:\
[Link Text Goes Here](URL%22Title%22)\
Hover over the link to see the magic!

**URLs AND e-mail ADDRESSES**

If you want to write URLs and e-mail addresses with another method, well
there is one!

\<Write URl or e-mail within these angle brackets\> e.g\
\<ram\@gmail.com\>

It looks like:\
<ram@gmail.com>

**9.IMAGES**

You can add attractive and catchy images too.\
The syntax is:\
\![Alt text\](URL to the image "Title")\
e.g

\![It is a flower!\](../Undiscovered-Things/download.jpg "Flower")

It looks like:  
![It is a flower!](download.jpg "Flower")

**linked images**

Images can also be used as a link.

The syntax is:\
\[!\[Alt text\](URL to the image "Title")](url) e.g

\[!\[It is a flower!\](../Undiscovered-Things/download.jpg "Flower")\](https://github.com)
It looks like-  

[![It is a flower!](download.jpg "Flower")](https://github.com)

**Task lists**   

You can create task lists containing checkboxes using - and \[ \] as
shown   
\- \[\] Red   
\- \[\] Blue
\- \[\] Purple    
It appears like:
- [ ] Red
- [ ] Blue
- [ ] Purple    

You can also check the box using \[x\] as shown   
\- \[x \] Red      
\- \[\] Blue      
\- \[\] Purple      

It appears like:
- [x] Red
- [ ] Blue
- [ ] Purple

**There are many other things like tables,using emojis(extended syntax)
and much more!**\
The basic syntax has already been covered..

I had a wonderful experience learning markdown..Hope you enjoyed it too!
