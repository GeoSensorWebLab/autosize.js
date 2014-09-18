# Autosize.js

This script will automatically resize the body element to match the window width and height. This is intended for full-page JS applications like Map viewers, where the map is defined using percentage widths and heights. Alternatively, the map can be resized with the window at the same time, but this code is easier.

But maps already work with percentage widths and heights for their element? Not in HTML5.

## Usage

Include the script in your page.

    <script src="js/autosize.js"></script>

To enable automatic body element resizing:

    Autosize.enable();

To disable automatic resizing:

    Autosize.disable();

## License

See LICENSE.
