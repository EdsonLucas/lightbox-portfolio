# Lightbox Portfolio
A simple way to use lightbox with Cube Portfolio - Responsive jQuery Grid Plugin. Cube Portfolio is a jQuery grid plugin that provides powerful portfolio system, beautiful animated filtering, custom captions and it’s perfect for portfolio projects, horizontal slider, images gallery and etc.

![](http://i.picasion.com/pic86/bc9b5a2cbf333e9cb9199a130440afa1.gif)

## Requirements

**You just need:**

- JQuery.

### Installation Overview

To clone the repo, run:

```git
git clone https://github.com/EdsonLucas/lightbox-portfolio.git
```

After this, you have to add this tag in your css area.

```
<link href="cubeportfolio/cubeportfolio.min.css" rel="stylesheet" type="text/css">
```

And you have to add these tags in your js area (after the JQuery file).

```
<!-- cubeportfolio -->
<script src="cubeportfolio/jquery.cubeportfolio.min.js" type="text/javascript"></script>
<script src="cubeportfolio/main.js" type="text/javascript"></script>
```

To make this simple, you can add this code in the end of your portfolio file.

```
<div id="js-grid-full-width" class="cbp" style="display: none;">
  <div class="cbp-item" style="display: none;">
  </div>
</div>
```

In the end, when you'll create your portfolio layout, you just have to put this class in your `<a>` tag.
```
<a class="images/{image_name}.jpg" class="cbp-caption cbp-lightbox">
```

It will create a directory folder called `lightbox-portfolio*` inside the current folder.<br>
**OBS.: You should copy this folder to your project and use like the tutorial above.**

```
lightbox-portfolio
├── README.md
└── cubeportfolio
    └── cubeportfolio.min.css
          └── cbp-sprite.png
    └── jquery.cubeportfolio.min.js
    └── main.js
```
