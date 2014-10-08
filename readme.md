
sass breakpoints
================


A small experiment. Structuring sass to create an automatic fall-back for browsers that don't support media queries.

creates two css files.

#### style.css
The style for all modern browsers. Mobile first building on each breakpoint.

#### style_ie.css
Style for older (pre IE9) IE browsers. Includes all the base styles (mobile) then appends all styles for each breakpoint up to the breakpoint defined in $ie_breakpoint