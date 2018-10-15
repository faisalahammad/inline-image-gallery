# Inline Image Gallery
There has lots of Image gallery plugin but sometimes those plugins not working when you've different size of images and also it's not possible to make same size image. "Inline Image Gallery" plugin will help you to make a inline image gallery when you've same or different size image and even 100 or more images.

No `Javascript` needed, just HTML & CSS will work well.
this thing needs to be updated
## Preview
Live link at [Codepen](https://codepen.io/faisalahammad/pen/XEMWrN) Or <br>
![Inline Image Gallery](https://preview.ibb.co/iE6Fnx/inline_image_gallery.jpg)


## HTML Code
```html
<ul class="inline-images">
    <li><img class="img-inline" src="http://via.placeholder.com/300x150" alt="Text" /></li>
    <li><img class="img-inline" src="http://via.placeholder.com/300x150" alt="Text" /></li>
    <li><img class="img-inline" src="http://via.placeholder.com/300x150" alt="Text" /></li>
    <li><img class="img-inline" src="http://via.placeholder.com/300x150" alt="Text" /></li>
    <li><img class="img-inline" src="http://via.placeholder.com/300x150" alt="Text" /></li>
</ul>
```

## CSS Code
```css
* {
  margin: 0;
  padding: 0;
}
h1 {
  margin: 50px auto 30px;
  text-align: center;
}
.inline-images {
  display: block;
  text-align: center;
  text-decoration: none;
  list-style: none;
  padding: 0;
  margin: 0;
  overflow: hidden;
  font-size: 0;
}
.inline-images li {
  display: inline-block;
  text-align: center;
  width: 25%;
  margin-top: 20px;
}
.inline-images li img {
    max-width: 100%;
    max-height: 150px;
}

/*---------- Media Query ----------*/
@media all and (max-width: 738px) {
    .inline-images li {
      width: 33.333%;   
    }
}

@media all and (max-width: 414px) {
    .inline-images li {
      width: 50%;   
      padding: 5px;
      box-sizing: border-box;
    }
}
```
