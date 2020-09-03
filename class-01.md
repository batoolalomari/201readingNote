
# Read: 01 - Introductory HTML and JavaScript



# Introduction

## **How the Web Works ?**


  When you visit a website, the web server hosting that site could be anywhere in the world. In order for you to find the location of the web server, your browser will first   connect to a Domain Name System (DNS) server.
  
  1. When you type a web address in a browser you connect to the internet service provider (ISP) 
  2. Your computer contacts the DNS(Domain Name Adress) servicess that provide your computer with the IP adress of the website that you visit
  3. Your computer conect to the web server that host the website using the IP adress that the DNS return
  4. The web server return the web page to your computer
  
  
  

# Structure


   The HTML code is made up of characters that live inside angled brackets — these are called HTML elements. Elements are usually made up of two tags: an opening tag and a closing tag. (The closing tag has an extra forward slash in it.) Each HTML element tells the browser something about the information that sits between its opening and closing tags.
   
   DOCTYPES tell browsers which version of HTML you are using.
   
   

    <html>
    <body>
    <h1>This is the Main Heading</h1>
    <p>This text might be an introduction to the rest of
    the page. And if the page is a long one it might
    be split up into several sub-headings.<p>
    <h2>This is a Sub-Heading</h2>
    <p>Many long articles have sub-headings so to help
    you follow the structure of what is being written.
    There may even be sub-sub-headings (or lower-level
    headings).</p>
    <h2>Another Sub-Heading</h2>
    <p>Here you can see another sub-heading.</p>
    </body>
    </html>
    
   ![Html Structure](htmlstructure.png)     ![Description](desc.png)
   
   
      
 ## HTML Uses Elements to Describe the Structure of Pages 
 
  HTML has several different elements each element has an **Opening** and **Closing** tags
  
  
   ![Description](open.png)        ![Description](close.png)
   
   
   
   
   Some HTML Element | Example 
   ----------------- | ----------------- 
   commint | <!-- -->
   block | <h1>, <p>, <ul>, and <li>
   inline | <a>
   inframe | <inframe>
   information | <meta>
  
  
 ##  Grouping Text & Elements In a Block
 
 ## **<div> element**
   The <div> element allows you to group a set of elements together in one block-level box.
   
    <div id="header">
    <img src="images/logo.gif" alt="Anish Kapoor" />
    <ul>
    <li><a href="index.html">Home</a></li>
    <li><a href="biography.html">Biography</a></li>
    <li><a href="works.html">Works</a></li>
    <li><a href="contact.html">Contact</a></li>
    </ul>
    </div><!-- end of header -->
     
  
 ## Attributes Tell Us More About Elements 
 
   Attributes provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts: a name and a value,  separated by an equals sign.
   
   ![Description](attribute.png)
   
   Some HTML attribute | Example 
   ------------------- | ----------------- 
   id | <p id="pullquote">
   class | <p class="important">
   inframe | <inframe>
   information | <meta>
   
 # 
 
 
  
  
  
  
  
  
  
