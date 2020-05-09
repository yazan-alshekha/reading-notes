# HTML5
### the most important things about **HTML**


- you should use *DOCTYPES* to tell the browser which version of HTML you are using 

 for  **HTML5 you should use this code**
```
<!DOCTYPE html>
```
- Comments 
 If you want to add a comment to your code 
 ```
 <!--your comment -->
 ```
 - **ID and classes** 
 Every HTML element can carry the id attribute.
 ```
 <p id="pullquote">hello world</p>
 <p class="important">hello world</p>
 ```
 - iframe ``` <iframe>```
   is like a little window that has been cut into your page and in that window you can see another page.
 
 ![googl maps](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcS-vP31Udxq_FaIbobXEWK06d0cd2FYO8Xp6iNPkdaUpxpF9D-V&usqp=CAU)
 
 - **Html5 provide a very  nice experiment to developer and clients**
 
 - The new HTML5 elements indicate the purpose of different parts of a web page and help to describe its structure.
 
 - Site mape 
   The aim is to create a diagram of the pages that will be used to structure the site.
 
 ![website mape](https://qph.fs.quoracdn.net/main-qimg-3cc479e9a5885c68548f1928801bc588.webp)
 
 - **WireFrames**
 
  a wireframe is a simple sketch of the key information that needs to go on each page of a site
 
 ![wireframe page ](https://www.graphicpear.com/wp-content/uploads/2016/03/BIG-1260x936.jpg)





# JavaScript 

## HOW A BROWSER SEES A WEB PAGE 

 
2. receive a page as html code
3. create a model of the page and store it in memory
4. use a rendering engine to show the page on screen

### All major browsers use a JavaScript interpreter to translate your instructions (in JavaScript) into instructions the computer can follow. 


## HOW HTML, CSS, & JAVASCRIPT FIT TOGETHER 

#### Web developers usually talk about three languages that are used to create web pages: HTML, CSS, and JavaScript.

``` <html> ```  **CONTENT LAYER**
 This is where the content of the page lives. The HTML gives the page structure and adds semantics. 

```<css>  ``` **PRESENTATION LAYER**
The CSS enhances the HTML page with rules that state how the HTML content is presented (backgrounds, borders, box dimensions, colors, fonts, etc.). 

```<javascript> ``` **BEHAVIOR LAYER**
This is where we can change how the page behaves, adding interactivity. We will aim to keep as much of our JavaScript as possible in separate files. 

### How do i write a script for a web page?

- It is best to keep JavaScript code in its own JavaScript file. JavaScript files are text files (like HTML pages and CSS style sheets), but they have the . j s extension. 

- The HTML ```<script>``` element is used in HTML pages to tell the browser to load the JavaScript file (rather like the ```<link>``` element can be used to load a CSS file). 

- If you view the source code of the page in the browser, the JavaScript will not have changed the HTML, because the script works with the model of the web page that the browser has created. 