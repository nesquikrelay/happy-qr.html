# happy-qr.html
Based on six-two's standalone offline 'HTML5 QR code generator' (https://github.com/six-two/qr.html) and the MIT-licensed 'qr-creator'. Optimized for friendly priting to 4x6 shipping labels from a browser environment and for key entry from barcode scanners.

## Changes to 'six-two/qr.html':
- Most links have been removed from the header for a minimalist interface. The clipboard link is still present, but cloaked with formatting changes.
- CSS colors changed from gray/silver to yellow/gold.
- Textbox is empty when the page loads - ready for instant input.
- Textbox is smaller - optimized to display one identifying string at the top of a 4x6 label.
- Textbox is now located above the generated QR code rather than to the left of the generated QR code.
- Textbox omits newline entries and the CTRL+J keyboard shortcut to prevent unintentional misreads with barcode scanners programmed to Add Enter Key (i.e. scanning into a textbox in a browser opens the Downloads tab or Windows search bar).
- QR codes are smaller - CSS entries on line 123 & 124 were resized to 10% (for 'qr_10.html'), 20% ('qr_20.html'), 30% ('qr_30.html'), and 40% ('qr_40.html'), respectively.
- QR codes now appear below the textbox instead of to the right.
- Error message box changed to friendly instructional prompt box.
- Error message box background changed from red to green.

'qr_10.html', 'qr_20.html', 'qr_30.html', and 'qr_40.html' are identical. The only difference between them are unique titles and headers to easily denote size (line 9 and 138 respectively), and CSS height/width properties at lines 123/124.

** Note: the CSS height and width percentages applied to draw QR codes at different sizes are relative to the resolution of the display. As they are, they are optimized for 1080p.

## Changes to repo
- 'tinyqr.html' has been removed.
- 'special.html' has been removed.
- 'index.html' has been removed.

## License
Like six-two's generator, the Happy QR Generator is licensed under The Unlicense and uses the MIT-licensed 'qr-creator'. You can fork, use, and modify this code however you want to.
