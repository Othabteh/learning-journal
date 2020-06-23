# Introduction to CSS 

* External CSS :
 A way to applaying your CSS style on HTML file by placing CSS in a separate file allows the web designer to completely differentiate between content (HTML) and design (CSS). External CSS is a file that contains only CSS code and is saved with a ".css" file extension. This CSS file is then referenced in your HTML using the <link> instead of <style>. If you're confused, don't worry. We are going to walk you through the whole process. When using CSS it is preferable to keep the CSS separate from your HTML.

~~~

<!DOCTYPE html>
    <html>
        <head>      
            <title>Using External CSS</title>    
            <link href="css/styles.css" type="text/css" rel="stylesheet" />          </head>
    </html>

~~~~

* Inteernal CSS
A way to applaying your CSS style on HTML file by using internal or embedded CSS requires you to add <style> tag in the <head> section of your HTML document.

~~~
<!DOCTYPE html>
 <html>
   <head>
      <title>Using Internal CSS</title>
      <style type="text/css"> body {font-family: arial;background-color: rgb(185,179,175);}h1 {color: rgb(255,255,255);}     
      </style>
   </head>
 </html>
~~~

* Inline CSS
used to style a specific HTML element. For this CSS style, you’ll only need to add the style attribute to each HTML tag, without using selectors.

~~~
<!DOCTYPE html>
<html>
<body style="background-color:black;">

<h1 style="color:white;padding:30px;">Hostinger Tutorials</h1>
<p style="color:white;">Something usefull here.</p>

</body>
</html>
~~~
<h1> Color </h1>


|  Term | Definition  |
|---|---|
|  RGB Values | Values for red, green, and blue are expressed as numbers between 0 and 255.  |
| Hex Codes  | represent values for red, green, and blue in hexadecimal code.  |
| Color Names  |  are represented by predefined names. However, they are very limited in number |
| Hue  |  is near to the colloquial idea of color. Technically speaking however, a color can also have saturation and brightness as well as hue. |
| saturatio  |  refers to the amount of gray in a color. At maximum saturation, there would be no gray in the color. At minimum saturation, the color would be mostly gray. |
| Brightness  | refers to how much black is in a color. At maximum brightness, there would be no black in the color. At minimum brightness, the color would be very dark.  |