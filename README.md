# 🌷 LilaCSS – Simply useful & modern.


![Image](https://i.ibb.co/CwKV5Pv/drawing.png)
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

## Download (Linux)
```sh
wget https://cdn.jsdelivr.net/gh/nsde/lilacss/lila.min.css
```

## Demo (Linux)
```sh
rm -rf lilacss # remove if already existing
mkdir lilacss && cd lilacss # prepare
wget -O lila.css.zip https://codeload.github.com/nsde/lilacss/zip/refs/heads/main > /dev/null 2>&1 # download
unzip lila.css.zip > /dev/null 2>&1 && rm lila.css.zip # install and remove the unneeded zip file 
firefox lilacss-main/examples/demo.html # show
clear && echo "Done! Showing LilaCSS demo in Firefox" # info message
```

## Use
```html
<!doctype html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://cdn.jsdelivr.net/gh/nsde/lilacss/lila.min.css" rel="stylesheet">
</head>
<body>
  <h1>
    Hello world!
  </h1>
</body>
</html>
```

## Why just not use Simple.CSS?
The reason is basically that I think my theme just looks more modern, I especially think my dark mode looks quite nice.  

I created LilaCSS because don't like its borders and the color theme. Of course, you can just take a moment to configure it, but I just want my theme to look great out of the box!

## Credits & License
This project is based on Simple.css:
- https://github.com/kevquirk/simple.css/blob/main/LICENSE

Support the team of Simple.css:
- https://github.com/sponsors/kevquirk
- https://ko-fi.com/kevquirk