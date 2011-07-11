Effect wherein hovering over a "foreground" element causes the "background" to blur, & vice versa.

**Demo:** http://sethbro.com/demo.html

## Usage
Apply the mixin to a container class with two children elements. These will be the "fields."

```
+depth_of_field( $color: #000, $amt: 5px, $init_blur: background )

# $color ­ text color within the child elements
# $amt ­ pixel amount of the blur
# $init_blur ­ sets which "field" will be blurred initially. Defaults to background.
```

You'll most likely want to position the two elements relative to each other in a way that supports the illusion.
Javascript to add a [parallax scrolling effect](http://dev.jonraasch.com/scrolling-parallax/docs) is also helpful.

## TODO
* Support for 3+ field levels
* Support for sub-elements (links within text, etc)
