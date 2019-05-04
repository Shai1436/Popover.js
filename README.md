<!-- <p align="center">
  <a href="https://prateekkalra.github.io/Selection-js"><img alt="SelectionJS" src="./logo.png" width="150px"></a>
</p> -->
<p align="center">
  A javascript snippet which provides a highly customizable popover with a set of options over the selected portion of text.
</p>

 <p align="center">
  <a href="https://shai1436.github.io/TextPopover.js/" target="_">Live Demo</a>
</p>

## Usage

To get started with Selection.js, download the [Script](https://raw.githubusercontent.com/Shai1436/Popover.js/master/selection.min.js) and add it to your project

### Basic Usage

```html
<script src="text-popover.min.js"></script>
<script>
  var popover = new TextPopover();
  popover.init();
</script>
```

### Advanced Usage

```html
<script src="text-popover.min.js"></script>
<script>
  var popover = new TextPopover();
  popover
    .configPopoverButtons({ //enables the popover actions (Boolean)
      facebook: true,
      twitter: true,
      search: true,
      copy: true,
      speak: true
    })
    .configPopover({
			bgColor: 'crimson', //sets the background color (Hexadecimal color )
			iconColor: 'white', //sets the icon color (Hexadecimal color)
			hideArrow: false, //hides the little arrow icon at the bottom of the popover (Boolean)
			showTooltip: true, //shows the tooltip for each action (Boolean)
      iconTransition: true, //enables the icon transition (Boolean)
      popoverShadow: '0 14px 28px rgba(0,0,0,0.25), 0 10px 10px rgba(0,0,0,0.22);' //set the box-shadow css property for the popover (CSS string)
		})
    .init();
</script>
```

# Result

<p align="center">
<img alt="Demo" src="https://user-images.githubusercontent.com/29385192/38880290-f5e173ce-4282-11e8-9447-6cab91540735.PNG">
</p>
