<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Interactive Gallery</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body onload="initGallery()">
  <div class="gallery">
    <img src="image1.jpg" alt="https://timeweb.com/media/articles/0001/09/thumb_8611_articles_standart.jpeg" tabindex="0" onfocus="showImage(1)" onblur="hideImage()">
    <img src="image2.jpg" alt="Image 2" tabindex="0" onfocus="showImage(2)" onblur="hideImage()">
    <img src="image3.jpg" alt="Image 3" tabindex="0" onfocus="showImage(3)" onblur="hideImage()">
    <img src="image4.jpg" alt="Image 4" tabindex="0" onfocus="showImage(4)" onblur="hideImage()">
    <img src="image5.jpg" alt="Image 5" tabindex="0" onfocus="showImage(5)" onblur="hideImage()">
    <img src="image6.jpg" alt="Image 6" tabindex="0" onfocus="showImage(6)" onblur="hideImage()">
  </div>
  <div id="mainImage">
    <img src="" alt="" id="largeImage">
  </div>
  <script src="script.js"></script>
</body>
</html>
