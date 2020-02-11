<p align="center">
  <img width="142" height="142" src="https://github.com/jgphilpott/particleWeb/blob/master/demo/icon.png">
</p>

# Intro

This particle web generator is a refactored version of [Jacquelin Clément](https://github.com/jacquelinclem)'s particle web on [CodePen](https://codepen.io/jacquelinclem/pen/udnwI).

# Usage

To get started download the [particleWeb.js](https://raw.githubusercontent.com/jgphilpott/particleWeb/master/particleWeb.js) file in this repository and add a script tag to your HTML:

```
<script type="text/javascript" src="particleWeb.js"></script>
```

Next, be sure to add a canvas element to your HTML like this:

```
<canvas id="canvas"></canvas>
```

The size and location of the canvas is up to you but you probably want a full screen canvas so I recommend the following styling:

```
#canvas {
  display: block;
  margin: auto;
  width: 100%;
  height: 100%;
}
```

Finally, summon the particle web with the following function call:

```
summonParticleWeb()
```

If everything worked you should see 42 black particles bouncing around your HTML page.

# Features

## Count

You can optionally specify the number of particles, like so:

```
summonParticleWeb(count=number)
```

## Colors

You can also specify the colors you want in an array, like so:

```
summonParticleWeb(count=number, colors=["red", "blue", "yellow"])
```

You can use HEX and RGBA codes as well as common color names.

## Canvas

If you want you can also use a different ID for the canvas, like so:

```
summonParticleWeb(count=number, colors=["red", "blue", "yellow"], canvas="wallpaper")
```
