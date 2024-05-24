# inp-click-on-empty-test

Testing INP when clicking on empty.

## How to use

Add querystring parameter `blockFor={{ms}}` to block the main thread repeatedly for `ms` milliseconds, with 1 second break after each blocking time.

Try clicking on the button, but also in the empty space, and you will see that INP can be attributed to the HTML element with Input Delay if clicking during blocking time.