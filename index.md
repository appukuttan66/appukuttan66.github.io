# Index
- Hompages
  - [3D-CSS-lib](#3D-CSS-lib)
  - [Wildberry-io **WORK IN PROGRESS**](https://appukuttan66.github.io/wildberry-io)

- Docs
  - [3D-CSS-lib](#3d-css-lib)

- Tutorials
  - 3D-CSS-lib
    - [A Simple Cube/Cuboid](https://peakd.com/hive-169321/@appukuttan66/how-to-make-a-3d)
    - [Cube/Cuboid Grid](https://peakd.com/hive-169321/@appukuttan66/multiple-cubes-with-css-3d)

# Docs
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

c {
  transform: rotateX(20deg) rotateY(30deg);
}

```
## Changing the height, width and depth
```css
c {
  --height: <the height you want>
  --width: <the width you want>
  --depth: <the depth you want>
}
```
## Changing the color
```css
c {
  --bg: <color>;
}
```
