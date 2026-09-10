# Content styles for web design

Select content specific styles for web design summarised as follows: 

- Theme variables and HTML content reset styles. 
- Primary color variables and smart multi-use utilities. 
- Content helper classes and text utilities.
- Border style and radius utilites.

The styles can be customized using CSS variables in real-time and the colors and smart utilities used to create custom components on-the-fly. The source files can also be recompiled using Sass to customize the style sheet to suit project parameters such as: 

- Selectively including colors and utilities with `true` and `false` statements.
- Customizing the default values for theme text, font and color-scheme.
- Customizing the default primary colors and/or adding new colors.
- Enabling breakpoint modifiers for the text, border and utilities.
- Adding custom CSS variables for compiling with the default tokens.

__Contrast-color__

The color utilities use `'contrast-color()'` values for text colors which automatically calculates the appropriate color (white or black) from the background color. This is only baseline 2026 so still tagged as 'newly available' to modern browsers meaning full coverage won't be until mid 2029 (2.5 years from baseline).

For flexibility wherever the technique is used the property values are all written with higher-specificity CSS variables for including custom text colors in real-time or accompanying style sheets if full coverage is preferred or required.
