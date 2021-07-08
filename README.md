# How to use

![image.png](https://i.postimg.cc/Pf2NncY3/image.png)

### 1. Use prefixed and minifed version of css file

```html
<link rel="stylesheet" href="box.min.css" />
```

### 2. Available css variables

```css
.box-bounced {
  --width: 120px;
  --height: 120px;
  --length: 120px;

  --color1: #f1e767;
  --color2: #feb645;
  --color3: #7c5620;
  --color4: #8e6425;
  --color5: #020201;
  --duration: 0.3s;
  --rotateX: -23deg;
  --rotateY: 45deg;
  --bounce-down-distance: -400px;
}
```

### 3. Markup, add/remove `.animated` class to control animation

```html
<div class="box-bounced animated">
  <div class="box-jello">
    <div class="box-cube">
      <div class="box-side box-cover">
        <div class="box-cover-side box-cover-left"></div>
        <div class="box-cover-side box-cover-right"></div>
        <div class="box-cover-side box-cover-back"></div>
        <div class="box-cover-side box-cover-front"></div>
      </div>
      <div class="box-side box-front">
        <div class="box-label"></div>
      </div>
      <div class="box-side box-back"></div>
      <div class="box-side box-left"></div>
      <div class="box-side box-right"></div>
      <div class="box-side box-bottom"></div>
    </div>
  </div>
</div>
```
