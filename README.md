# fly-css Helper
While developing CSS (with or without CSS-Frameworks) over the years, I often find myself adding little helper
rules for padding, margin etc. As I often find myself copying this CSS rules from one project to another, I decided
to put them all together in a little Helper-CSS file and share them with the community maybe someone else finds
it helpful.

###Todo List
- [ ] Add sass support
- [ ] Change pixel values to em
- [ ] Add more color tones

## Usage
Description of how the helper classes can be used.

### Box-Model
The CSS file contains Box-Model Helpers for `padding`, `margin` and `border` in the following style.
E.g

```html
 <div class="pad-5__h"><!-- this class adds 5px padding horizontal --></div>
 <div class="mar-10__to"><!-- this class adds 10px margin top --></div>
 <div class="bor-1__bo"><!-- this class adds a 1px solid bottom border --></div>
```

Modifier | Explanation
------------ | -------------
__h | horizontal
__v | vertical
__to | top
__ri | right
__bo | bottom
__le | left


Set the `display` attribute to block/hide with the following classes

```html
 <div class="blo"><!-- this class sets display: block--></div>
 <div class="hid"><!-- this class sets display: hidden --></div>
```

Set the `transform` attribute to rotate a Box-Model 90 degrees

```html
 <div class="rot-90"><!-- this sets transform: rotate(90deg); --></div>
```

### Fonts
Use the class `.bolder` for more font-weight, use the `.small` class to minify text
```html
 <div class="bolder"><!-- this sets font-weight: bolder; --></div>
 <div class="small">
    <!-- this makes text small and changes the
    font-family to arial for better reading; -->
</div>
```

### Colors
Use the color classes to set the color for text and links
```html
<div class="black">
    This text will be black and also
    <a href="#foo">links will be black</a>
</div>

<a class="black" href="#foo">Black link text</a>

<div class="bor-1__to bor-black">This box will have a 1pixel solid top border</div>
```



##Changelog
- **v0.1 beta**, 15, Februar 2016
