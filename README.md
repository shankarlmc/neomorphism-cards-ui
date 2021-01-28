# Neomorphism Cards UI

Creating a neumorphic interface with CSS is seemingly as easy as applying a regular box-shadow property on any element, but it’s more nuanced than that. The distinctiveness of a neumorphic UI comes from using multiple box-shadow and background-color values to achieve different types of effects and variations.

### Following options can be adjusted:

- Horizontal offset: 
	A positive value offsets shadow to the right, while a negative value offsets it to the left.
- Vertical offset: 
	A positive value offsets shadow upwards, while a negative value offsets it downwards.
- Blur Radius: 
	The length of the shadow. The longer the length, the bigger and lighter the shadow becomes. There are no negative values.
- Spread Radius: 
	This is another length value, where larger values result in bigger, longer shadows.
- Color: 
	This defines the shadow’s color, just as we’d do for the CSS color property.
- Inset: 
	The default value (initial) results in a drop shadow. Using the inset value moves the shadow inside the frame of the element, resulting in an inner shadow.

### Syntax
```bash
box-shadow: [horizontal offset] [vertical offset] [blur radius] [optional spread radius] [color];
```
