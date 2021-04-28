# scingle-page-scroll
Vanilla Javascript tutorial project #10 presented by John Smilga

## dynamic footer date
-date.innerHTML = new Date().getFullYear();

## dynamic navbar height on link toggle
-height of links container is initially hardcoded to 200px which is the height of the links in total.
### calculate and toggle height of the links:
-getBoundingClientrect();

-links-container is nb as a parent container with an initial height of 0 to wrap around the links giving a reference to the total height.
links height is used for new toggle value as the links will have the height value required;
- 