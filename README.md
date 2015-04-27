# Scrollspy-mini
This code example is my version of Scrollspy and offers a way to fine tune it's operation.
## Implementation:
1. jquery.scrollspy-mini.js is commented to allow for easy implementation.
2. Each nav anchor must have an id for the addClass and removeClass to target.
3. Each section or div must have an jQuery offset() method to find the top and left coordinates to compare to the scrollTop() method.
4. You must add a comparision statement for each section or div.
5. Manual fine tune functionality by adjusting the yPos variable up or down.
6. Call the plugin using:  $(document).scrollspy(); inside a document ready function.
