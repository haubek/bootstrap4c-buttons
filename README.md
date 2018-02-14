# Bootstrap4C

### buttons

The *buttons* is a simple Bootstrap 4 component that extend your default Bootstrap buttons classes with a few usefull once. The component is 100% CSS, no JavaScript needed.

See demo here => https://haubek.github.io

### NPM install

```
npm install bootstrap4c-buttons
```

### CSS

```
<link href="path/to/component-buttons.min.css" rel="stylesheet">
```

### HTML5 markup

```
<button type="button" class="btn btn-primary btn-pill">I'm a pill button</button>
<button type="button" class="btn btn-white">I'm a white button</button>
<button type="button" class="btn btn-outline-white">I'm a white outline button</button>
```

```
<div class="btn-group btn-group-toggle btn-group-pill" data-toggle="buttons">
  <label class="btn btn-outline-secondary btn-switch-on active">
    <input type="radio" name="options" id="on" autocomplete="off" checked> On
  </label>
  <label class="btn btn-outline-secondary btn-switch-off">
    <input type="radio" name="options" id="off" autocomplete="off"> Off
  </label>
</div>
```

```
<div class="btn-toolbar btn-toolbar-row" role="toolbar" aria-label="A11Y">
  <div class="btn-group btn-group-xs-6 btn-group-md-reset" role="group" aria-label="A11Y">
    <button type="button" class="btn btn-primary btn-block">Save</button>
  </div>
  <div class="btn-group btn-group-xs-6 btn-group-md-reset" role="group" aria-label="A11Y">
    <button type="button" class="btn btn-secondary btn-block">Cancel</button>
  </div>
</div>
```
