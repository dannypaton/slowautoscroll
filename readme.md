#Slow Auto Scroll
A JQuery plugin build to assist your web pages that have a large amount of content.

The page will scroll at certain speeds selected by the user without having to use a mouse or trackpad!

##Getting Started
1. Download the zip file off of Github

2. Open the files in a text editor such as Sublime Text 3

3. Copy and paste the 'slowautoscroll.css' file from the downloaded folder to your CSS folder

4. Copy and paste the 'slowautoscroll.js' file from the downloaded folder to your Javascript folder

5. Copy and paste the following code in the head section of your HTML (these will link the CSS, jQuery and Javascript files to your site)
```html
<link rel="stylesheet" type="text/css" href="css/slowautoscroll.css">
<script type="text/javascript" src="js/slowautoscroll.js"></script>
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js">
```
##Including Slow Auto Scroll in your HTML
6. Copy and paste the following code into your HTML body to use the animal images provided
<br>
```html
<ul class="scroller">
  <li class="scroll"><img src="images/click.png" class="img" alt=""></li>
    <ul class="speeds">
      <li class="slow"><img src="images/turtle.png" class="img" alt=""></li>
      <li class="medium"><img src="images/rabbit.png" class="img" alt=""></li>
      <li class="fast"><img src="images/cheetah.png" class="img" alt=""></li>
    </ul>
  </li>
</ul>
```
That's it! The plugin will now show up on your page.
Happy scrolling!
##Example
[See a demo of Slow Auto Scroll](http://dannypaton.github.io/slowautoscroll/demo)