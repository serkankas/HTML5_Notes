There is an online ~~free~~ [course](https://www.youtube.com/watch?v=pQN-pnXPaVg) that i learn the most of the basic from.I found it very useful, and I want it to share the knowledge I got from it as cheatsheet.<br>
Also worth mentioned that there are much more tags that you may want to check, I highly suggest the website called [w3school](https://www.w3schools.com/html/default.asp)

HTML "Hyper Text Markup Language" has lot's of containers to make our browser easily understand. I, ~~although it maybe wrong~~, seperate the containers into two section.

1. The container tags that will need to close
1. The container tags that doesn't required to be closed.

What I mean by need to be closed is
> \<a> This is example for closing \</a><br>
\<img src="Some_source_to.img">

I don't want to focus on the tags meaning directly, the **a** and **img** tag will be written in detail in next sections. What I want to tried is understand the structure of two lines of code, one with closing same tag but start with division sign **\</a>** but the other doesn't.

So with that in mind, HTML have many containers that contains other containers. Basically, it creates the structure that contains lots of containers to easier following.

There is two main containers that we need to learn first.
1. head
1. body

Before we start to dive into those sections, I need to point that every html file should contains the doctype as well as html tag.
>\<!DOCTYPE html><br>
\<html><br>
**some html tags, containers and codes**<br>
\</html><br>

Also, we can comment in html via \<! --- comment something --->

This is good habit to create your HTML file for your application, also it is good for your browser applications.<br>
Just to point that the **html** tag is also a tag that need close. I will give list in upcoming sections.

> head tag

This tag usually contains metadatas, title tag, script tag (**usually JavaScript**) and stylesheet (**aka. CSS**) paths.<br>
This is the container tag that usually does not contain information that user directly monitor, it is more likely setted for browser, etc.

> body tag

Almost everything we saw in web-page is contains under body tag. The pictures, links, infos, bios, etc. Almost everything will be shown in webpage is under this tag.<br>
But as we mentioned before, the body tag need lot's of containers too in order to present in better way.<br>
There is also three main part in body tag
1. header
2. main
3. footer

With that being said, let's see the tags that will need opening and closing.

>Tags that need to have opening and closing tag

|Syntax|Explanation|
|------|-----------|
|html| HTML Container Tag|
|head| Head Container Tag|
|body| Body Container Tag|
|p| Paragraph Container Tag|
|title| Title Content - The one will be shown in page tab view|
|h1-6| Header tag, can be written from 1 to 6 depends on size|
|b| Bold tag|
|i| Italic tag|
|big| Make the text bigger|
|small| Make the text smaller|
|sub| When you write the H2O, the 2 will be sub with the help of sub tag|
|sup| Opposite the sub, used for power sign for example.|
|header| This is the top of page we could think. Anything that we want to contain at top of the page, we could use this.|
|main| This is the section that most of the content will be published. usually, the pictures, vlogs, blogs, contents, sections almost everything will be stored under the main part of body tag.|
|footer| This is the very bottom part of page, we most likely some linking in this section for the pages.|
|a| Tag for creating a link|
|video| video container, it also has some option that need to be checked.|
|ul| unordered list|
|ol| ordered list|
|li| List item|
|table| ??? element ??? |
|tr| table row|
|td| table column|
|th| table header|
|thead|table head|
|form| make an input|
|iframe|Embedding anything.|

The tags that I need to check, since I do not remember at all. I will learn and re-emphasise these tags.

|Syntax|Explanation|
|------|-----------|
|article| ??? |
|section| ??? |
|aside| ??? |
|nav| ??? |
|dl| description list|
|dd| description for list|

>Tags that does not need any closing tag

|Syntax|Explanation|
|------|-----------|
|\<br/>|Breaking tag. It creates new line.|
|\<hr/>|Horizontal line tag.|
|meta|Data tag that contains meta-data. We send some properties to meta-data tag.|
|img| Image tag|


>Also, there are some properties that needs to be followed.

|Syntax|Explanation|
|------|-----------|
|charset| Character set for website (**like UTF-8**)|
|name| ??? |
|content| Content related to that name |
|style| Referencing css ??? |
|href| Reference point|
|target|"_blank" if you gives that as an input, then your link (inside the **a** tag, will be open in new tab, instead of the current tab.|
|src| source, used for image ? or local source?|
|widht| Width for both image and video|
|height| Height for both image and video|
|alt| Alternative explanation for image or video, if the given link is broken.|
|colspan| Metadata for table, it will be shown in **tr** tag|
|span| Inline container|
|div| Block container|

For now, that's it. I will create couple html file to show presentation. For structure, as mentioned above, i will mainly follow this.

    <html>
    
        <head>
        </head>
    
        <body>
        
            <header>
            </header>
            
            <main>
            </main>
            
            <footer>
            </footer>
            
        </body>
        
    </html>

Pages content could be followed in order
1. index.html   --> basic structure
1. 0.html       --> typing
1. 1.html       --> table and lists
1. 2.html       --> the ones that I did not comment

You can easily see that, i did not cover the image and video since I though they are so straightforward. Upon requests, more content can be shared. Please feel free to use according to your needs and learn. Just do not forget to give a credit <3 
