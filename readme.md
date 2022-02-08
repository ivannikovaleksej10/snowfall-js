# Falling snow animation rendered in jQuery.

For animation, the TweenMax library from GreenSock is used. Snowflakes have a different blur, due to which the effect of three-dimensionality of what is happening is achieved.

In the demo example, I showed how you can apply such an animation only for the background.

## HTML

The snow itself is added to the container with an ID

```html
<div id="snow-animation-container"></div>
```

## CSS

There are no styles, the very design of snowflakes is formed by a js script. We only manage the container that holds all the snowflakes.

## JS

For snow to work, you need to include the jQuery and TweenMax libraries on the page.
I connected them from CDN.

```javascript
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/1.20.3/TweenMax.min.js"></script>
```

And after connecting the file with the script script.js

By manipulating the values of variables:

- MAX_SNOW = 200 — maximum number of snowflakes
- MAX_SNOW_SIZE = 7 — maximum snowflake size in pixels
- MAX_SNOW_SPEED = 1 — snowflake acceleration

You can increase the amount of snow, control the size and speed of falling.

You can see the whole code in the repo.
