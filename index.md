# Index
- Hompages
  - [Terrive](https://terrive.on.fleek.co)
  - [3D-CSS-lib](#3D-CSS-lib)
  - [Fuzzy Invention](https://fzin.ga)

- Docs / Info
  - [3D-CSS-lib](#3d-css-lib)
  - [Terrive](#Terrive)

- Tutorials
  - 3D-CSS-lib
    - [A Simple Cube/Cuboid](https://peakd.com/hive-169321/@appukuttan66/how-to-make-a-3d)
    - [Cube/Cuboid Grid](https://peakd.com/hive-169321/@appukuttan66/multiple-cubes-with-css-3d)

# Docs / Info

## Terrive

[Terrive](https://terrive.on.fleek.co) is a decetralized social media platform that supports images, albums and videos. The UI/UX was made using Bootstrap 5.
It uses the [Hive Blockchain](https://hive.io) as an immutable database while leaving the image & video hosting to be independently hosted by the user.


## 3D-CSS-lib

A simple 3d css library to help you get started with CSS 3d

## Including in browser
```html
<link href="https://appukuttan66.github.io/3D-CSS-lib/lib.css" rel="stylesheet" type="text/css">
```

## Creating a simple cuboid

### HTML
```html

<div class="c">
  <div class="s"></div>
  <div class="s"></div>
  <div class="s"></div>
  <div class="s"></div>
  <div class="s"></div>
  <div class="s"></div>
</div>

```
### CSS

```css

.c {
  transform: rotateX(20deg) rotateY(30deg);
}

```
## Changing the height, width and depth
```css
.c {
  --height: <the height you want>
  --width: <the width you want>
  --depth: <the depth you want>
}
```
## Changing the color
```css
.c {
  --bg: <color>;
}
```
