# Boilerplate

## Includes:
- Scss Compiler
- Babel with ES2015
- img-loader (image optimizer)
- purify-css (removes unused selectors from css)

### Optional:
- jQuery
- Popper (required for Bootstrap 4)
- Bootstrap 4

#### SCSS folder structure:
Name       | Contains
---------- | --------
base       | global styles, e.g.: resets, typography, colors, etc
components | each self-contained component in its own .scss partial
layout     | styling for larger layout components, e.g.: nav, header, footer, etc
pages      | page-specific styling
themes     | styling for different themes
utils      | global mixins, functions, helper selectors, etc
vendors    | 3rd-party styles, mixins, etc
main.scss  | output that combines all of the above
"# _fiveapp" 
