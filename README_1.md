# Image-ResizerCroper
Image editor, Resize and crop easy

#JQuery Image Resize Plugin (javascript & html)

Important, i did this code for my job, and i used other projects from github, i put here to help the community, i use this two projects:

--> My version upload

 --> JCrop-Master (oficial) --> demos/tutorial2.html  (For the crop) 
      link: https://github.com/tapmodo/Jcrop
      
 
 --> Image Resizer: Dynamic Image Resizing plugin with jquery
      link: http://www.jqueryscript.net/layout/Dynamic-Image-Resizing-Plugin-with-jQuery.html
     
        ####HTML:
        ```html
        <img class="resizeme" src="sample1.jpg">
        ```

        ####JavaScript
         ```javascript
        $(function() {
            $( ".resizeme" ).aeImageResize({ height: 250, width: 250 });
        });
        ```
      
I USE: html, jQUERY, JAVASCRIPT, and css

IMPORTANT: 

-->  to use: Index is the home, you have to create a directoris and organitzate the file into ./css  ./js, etc and have to read the  imprts from index and modficate correctly as like as you created the direcories. 

My directory is like this: 
  
 
- Desktop/
     -/ResizerImage
         - ./css --> Jcrop.css
         - ./example --> index & Images
         - ./js  --> jquery.js
         - ./src --> jquery.ae.image.js
           .json
    

Search: 

    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1/jquery.min.js"></script>
  
    <script src="../js/jquery.min.js"></script>		
  
    <script src="../js/jquery.Jcrop.js"></script>
  
    <script src="../src/jquery.ae.image.resize.js"></script>
...

and Search too:

    <link rel="stylesheet" href="demo_files/main.css" type="text/css" />
    <link rel="stylesheet" href="demo_files/demos.css" type="text/css" />
    <link rel="stylesheet" href="../css/jquery.Jcrop.css" type="text/css" />
...

If you dont do this, probably dont work, you have to read the import lines and change it as you think.

for any problem just comment !

Thanks for read and i wish you the best ! :D
