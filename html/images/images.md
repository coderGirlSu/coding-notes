# Images

How to use the `<picture>` and `<source>` html tags to create a responsive image.
This causes the browser to download a different image based on media queries.
It can be useful for example to download images of smaller file sizes on mobile devices. 

Example
```
<picture>
  <source media="(min-width:650px)" srcset="img_pink_flowers.jpg">
  <source media="(min-width:465px)" srcset="img_white_flower.jpg">
  <img src="img_orange_flowers.jpg" alt="Flowers" style="width:auto;">
</picture>
```
Source: https://www.w3schools.com/tags/tag_picture.asp

See the `/example` directory for a working example.
