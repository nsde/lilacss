# 🌷 LilaCSS – Simply useful & modern.
The aim of LilaCSS is to provide a CSS framework in which classes are completely optional. The website should work fine without them, too! No need to research how to insert a button. Just add one line (see below) to your code and *et voilà*!

<!-- ![Image](https://i.ibb.co/CwKV5Pv/drawing.png) -->
![Screenshot](https://i.ibb.co/KrXqFjD/image.png)

*Demo with dark mode enabled*
***
### [How to see a live demo of LilaCSS](#demo-linux)

## Features
- Auto Dark Mode
- Responsive
- Lightweight
- No `!important`, you decide

### Advantages over Simple.css
- More modern style
  - Animations
  - Shadows
  - New dark mode
  - Improved color scheme

- More features for blogging & articles
  - Article info card `text-box`

- Tools
  - [Rows](docs/structure.md#Rows) `w-<n>`
  - [Dark Mode auto-invertion of images](docs/classes.md#Dark+Invert+for+Images) `dark-invert`

## Use
### CDN (Recommended)
Don't worry, the framework won't change that much that I'll break your website.

```html
<link href="https://onlix.me/cdn/lilacss" rel="stylesheet">
```

### Download
Run this in your website directory:
```sh
wget -O style.css https://onlix.me/cdn/lilacss
```

and insert this:

```html
<link href="style.css" rel="stylesheet">
```

in your HTML file.

## Demo (Linux + Firefox)
```sh
rm -rf lilacss # remove if already existing
mkdir lilacss && cd lilacss # prepare
wget -O lila.css.zip https://codeload.github.com/nsde/lilacss/zip/refs/heads/main > /dev/null 2>&1 # download
unzip lila.css.zip > /dev/null 2>&1 && rm lila.css.zip # install and remove the unneeded zip file 
firefox lilacss-main/examples/demo.html # show
clear && echo "Done! Showing LilaCSS demo in Firefox" # info message
```

## FAQ
### How can I use icons?
Add the stylesheet to your html:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@latest/font/bootstrap-icons.css">
```

Search for an icon [icons.getbootstrap.com](https://icons.getbootstrap.com) and add it:

```html
<!-- Example: icon called "heart" -->
<i class="bi bi-heart"></i>
```

Works great!
![](docs/media/bootstrap-icons.png)
### Why did you create this framework?
The reason is basically that I think my theme just looks more modern, I especially think my dark mode looks quite nice.  

I created LilaCSS because don't like its borders and the color theme. Of course, you can just take a moment to configure it, but I just want my theme to look great out of the box!

Also, want my framework to have a lot of additional features without making it complicated to set up.

## Credits & License
This project is based on Simple.css:
- https://github.com/kevquirk/simple.css/blob/main/LICENSE

Support the team of Simple.css:
- https://github.com/sponsors/kevquirk
- https://ko-fi.com/kevquirk