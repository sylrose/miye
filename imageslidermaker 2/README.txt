Image Slider Maker README
=========================
ImageSliderMaker.com


Using in your website
---------------------

Please first make sure you have fully extracted the contents of the zip file.
In Windows, right-click on imageslidermaker.zip and select Extract All...

To get your slider working in your web page, you must add
my-slider.css, ism-2.2.min.js and the slide images to your project
directory and paste the markup (included below) into your HTML.

The directory structure of this package:

  imageslidermaker/
    README.txt
    example.html
    ism/
      css/
        my-slider.css
      js/
        ism-2.2.min.js
      image/
        slides/
          _u/1688386575426_48387.png
          _u/1688386534071_814244.png
          _u/1688386508977_288013.png
          _u/1688386559965_187015.png
          _u/1688386567091_86711.png
          _u/1688386597045_683002.png
          _u/1688386610138_696468.png
          _u/1688386615156_815866.png
          _u/1688386604006_56587.png
          _u/1688386583335_537976.png

For a working example, open example.html in your web browser or
follow the instructions below to integrate the slider into your
project.


Step by step instructions
-------------------------

1. Paste the following into the head of your HTML file:

<link rel="stylesheet" href="ism/css/my-slider.css"/>
<script src="ism/js/ism-2.2.min.js"></script>


2. Paste this into the body of your HTML file (at the location where:
   you would like your slider to appear in the page):

<div class="ism-slider" data-play_type="once" data-radio_type="thumbnail" id="my-slider">
  <ol>
    <li>
      <img src="ism/image/slides/_u/1688386575426_48387.png">
    </li>
    <li>
      <img src="ism/image/slides/_u/1688386534071_814244.png">
    </li>
    <li>
      <img src="ism/image/slides/_u/1688386508977_288013.png">
    </li>
    <li>
      <img src="ism/image/slides/_u/1688386559965_187015.png">
    </li>
    <li>
      <img src="ism/image/slides/_u/1688386567091_86711.png">
    </li>
    <li>
      <img src="ism/image/slides/_u/1688386597045_683002.png">
    </li>
    <li>
      <img src="ism/image/slides/_u/1688386610138_696468.png">
    </li>
    <li>
      <img src="ism/image/slides/_u/1688386615156_815866.png">
    </li>
    <li>
      <img src="ism/image/slides/_u/1688386604006_56587.png">
    </li>
    <li>
      <img src="ism/image/slides/_u/1688386583335_537976.png">
    </li>
  </ol>
</div>
<p class="ism-badge" id="my-slider-ism-badge"><a class="ism-link" href="http://imageslidermaker.com" rel="nofollow">generated with ISM</a></p>


3. Copy the ism/ directory into the root directory of your project.

   The css, js and image paths are relative, meaning the ism/
   directory should be in the same directory (path) as your HTML
   file containing the slider.


