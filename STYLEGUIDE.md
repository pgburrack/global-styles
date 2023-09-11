# CSS Style Guide


## Color units
hsl


## Sizing Units

Options:
- px
- percentage
- em
- rem

- font size - EM or REM
- line height - numbers 1.2
- padding - use pixels.
  pixel will make a page more accessible.
- border - pixels
-
### Font Size
**Do not use pixels** as this is not good for accessibility.

User either EM Or REM.

### line height
User numbers.
1.2 etc

### padding
use pixels


### When to use px?

### When to use em?

### When to use rem?

### When to use percentage?

## Logical properties

Example of logic properties:
  margin-block-start: 1em;
  margin-block-end: 1em;
  margin-inline-start: 0px;
  margin-inline-end: 0px;

When should we use logical properties?
Logical properties are intended to entirely replace their conventional alternatives. In the future, we might all write margin-inline-start instead of margin-left!

The main selling point for logical properties is internationalization. If you want your product to be available in a left-to-right language like English and a right-to-left language like Arabic, you can save yourself a lot of trouble by using logical properties.

## Resources
- Specificity - https://2019.wattenberger.com/blog/css-cascade
