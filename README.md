# nanoOS

### A tiny desktop inside one QR code

By **nanoLabs**

I wanted to see how much of a desktop I could fit into a single QR code. This is what I ended up with: movable windows, a terminal, notes, files and a clock.

[Open nanoOS](https://nanolabs-dev.github.io/nanoos/launch.html)

![nanoOS desktop](desktop.png)

The actual HTML, CSS and JavaScript are compressed into the URL after the `#`. The hosted page only decodes it. The compressed app is 2,790 bytes and fits in one standard QR.

![Scan to open nanoOS](nanoos-qr.png)

Notes stay in the current browser. The first scan needs internet for the decoder; the desktop works offline after boot. This is a browser interface, so its terminal doesn't run commands on the device itself.

Built by nanoLabs. The unchanged official QR may be shared.


[Download the sharing pack](nanoOS-share.zip) · [QR SVG](nanoos-qr.svg) · [Mobile preview](mobile.png)

Copyright © 2026 nanoLabs. Viewing and personal evaluation only; redistribution, modified publication, sale, sublicensing and reuse require written permission. The unchanged official QR may be shared with attribution. See [LICENSE](LICENSE).

This release uses a new payload. Notes are stored by browser and payload version, so notes from an older QR are not automatically shown here.
