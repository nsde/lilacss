# Example structures
> **Notice:** The framework is under construction and the screenshot might not be 100% accurate! Most of the screenshots are done shortly after the programming of the feature. The screenshots usually show the default dark theme. 

## Cards

### Simplified example
```css
- div.cards
    - div.card
        - img
        - h4
        - p
        - a
    - ...
```

### Actual example code
```html
<div class="cards">
    <div class="card" onclick="window.location.href = 'blog/log4shell';">
        <img src="image.jpg">
        <h4>Log4Shell Info</h4>
        <p>Lorem ipsum dolor sit amet</p>
        <a href="#">Learn more...</a>
    </div>
    <div class="card" onclick="window.location.href = 'blog/example';">
        <img src="image.jpg">
        <h4>Example text</h4>
        <p>Lorem ipsum dolor sit amet</p>
        <a href="#">Learn more...</a>
    </div>
</div>
```

## Rows
Not recommended, this is for experimental purposes and testing.

```html
<div class="row">
    <p class="w-2">One</p>
    <p class="w-2">Two</p>
</div>

<div class="row">
    <p class="w-3">One</p>
    <p class="w-3">Two</p>
    <p class="w-3">Three</p>
</div>

<div class="row">
    <p class="w-4">One</p>
    <p class="w-4">Two</p>
    <p class="w-4">Three</p>
    <p class="w-4">Four</p>
</div>
```
... and so on:

![](media/rows.png)


## Blog
### Simplified example (!)
```css
- body
    - header
        - nav 
            - a
            - a
            - svg /* Social Media Icons */
    - main

        - div class="text-box article-info" /* Basically just a box */
            - p
            /* or, for a more detailed info-box: */
            - p.reading-time
            - p.published
            - p.author
    - footer
        - socials
```

## Info Box (Simple)
```html
<div class="text-box article-info">
    <p>
        by <strong>ONLIX</strong>・ <strong>Mar 14, 2022</strong>
    </p>
</div>
```

![Info Box (Small)](media/infobox-small.png)

## Info Box (Detailed)

```html
<div class="text-box article-info">
    <p class="author">ONLIX</p>
    <p class="published">Mar 14, 2022</p>
    <p class="reading-time">5</p>
</div>
```

The emojis & text will be added automatically. If you don't like how it looks, just use your custom `<p>` elements without the classes.

![Info Box (Large)](media/infobox-large.png)

## "Recommended Articles"-Overview
Pretty much every single website has them, and your's will, too!

![](media/articles.png)

These are called "cards" (mentioned before) and can be used like so:

```html
<h2>New articles</h2>
<div class="cards">
    <div class="card" onclick="window.location.href = 'http://www.example.com';">
        <img src="image.jpg">
        <h4>This is an example article</h4>
        <p>Lorem ipsum dolor sit amet, consectetur adipis lac consetetur sad et.</p>
        <a href="#">Learn more...</a>
    </div>
    <div class="card" onclick="window.location.href = 'http://www.example.com';">
        <img src="image.jpg">
        <h4>This is an example article</h4>
        <p>Lorem ipsum dolor sit amet, consectetur adipis lac consetetur sad et.</p>
        <a href="#">Learn more...</a>
    </div>
    <div class="card" onclick="window.location.href = 'http://www.example.com';">
        <img src="image.jpg">
        <h4>This is an example article</h4>
        <p>Lorem ipsum dolor sit amet, consectetur adipis lac consetetur sad et.</p>
        <a href="#">Learn more...</a>
    </div>
</div>
```

## Posts & Action Bars
> **Notice:** [Bootstrap Icons](https://icons.getbootstrap.com/#cdn) is needed for the icons to render properly!

```html
<div class="posts">
    <div class="post">
        <img src="image.jpg">
        <h4>Should YOU learn Python?</h4>
        <p>This is just an example. What are the benefits of learning Python?</p>
    
        <div class="actions">
            <i class="bi bi-heart-fill active"></i> <!-- for when the user already clicked on the heart (keep in mind to use -fill and active) -->
            <i class="bi bi-bookmark"></i>
            <i class="bi bi-flag"></i>
            <i class="bi bi-chat-dots"></i>
            <i class="bi bi-info"></i>
        </div>
    </div>
```
![](media/post.png)