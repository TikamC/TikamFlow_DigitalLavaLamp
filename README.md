# TikamFlow_DigitalLavaLamp
The project background for a MacBook in the form of a lava lamp embodies comfort and atmosphere and allows you to adjust the parameters and placement of this lamp for yourself. It is written in HTML and is added via the Plash application.

An animated background for MacBook: a realistic lava lamp with customizable colors, glow, shape, and on-screen position. The entire project consists of a single file, 'TikamFlow_LavaLamp.html'. It works offline and requires no dependency installation.

## Features

-   Lava simulation: blobs heat up, rise, cool down, merge, and split.
-   Glow, reflections on the desk, and soft background lighting.
-   Lamp position: left, center, or right (with smooth transitions).
-   Lamp shapes: Classic, Cylinder, Flask, and Vase.
-   Custom lava, glow, and background colors, plus five ready-made color schemes: Classic, Ocean, Purple, Acid, and Gold.
-   Sliders for glow brightness, animation speed, and lamp size.
-   Settings are saved in the browser.

## Quick Start

1.  Save 'lava-lamp.html' in a permanent folder, for example ~/Documents/TikamFlow/.
2.  Double-click the file. It will open in your default browser (Safari or Chrome is recommended).
3.  Press ⌃⌘F (Control + Command + F) to switch to full-screen mode.

Controls:

  Action           How
  ---------------- -----------------------------------------------
  Open settings    Click the ⚙ button in the top-right corner
  Hide the panel   Press H
  Full screen      Press ⌃⌘F or click “Full Screen” in the panel
  Reset settings   Click “Reset”

After 4 seconds without mouse movement, the interface and cursor disappear automatically.

## How to Set It as Your Desktop Wallpaper

macOS cannot use a web page directly as a wallpaper, so you will need a small utility.

### Option 1: Plash (recommended)

[Plash](https://sindresorhus.com/plash) — Plash is a free app from the Mac App Store that displays a web page directly on your desktop.

1.  Install and launch Plash (its icon will appear in the menu bar).
2.  Select “Add Website…” and choose the lava-lamp.html file using the file picker, or enter a link to the page if you have hosted it online.
3.  If you like, enable Plash to launch automatically when you log in.

The lamp settings in Plash can be accessed in the same way as in a browser. If you want to change the color or shape, temporarily open the file in a browser, adjust the settings, and then return to Plash. Settings are stored in localStorage, which is tied to the page’s address. Therefore, if Plash does not pick them up, change the default values in the code (see below).

### Option 2: As a Screen Saver

The [WebViewScreenSaver](https://github.com/liquidx/webviewscreensaver) utility turns a web page into a system screen saver. Install it, open “System Settings → Screen Saver,” and enter the file address in the WebViewScreenSaver settings, for example: 'file:///Users/NAME/Documents/TikamFlow/lava-lamp.html'. Third-party screen savers may be subject to limitations in newer versions of macOS, so if you run into problems, use Plash instead.

### Option 3: In a Separate App Window

In Chrome, go to “More → Save and Share → Create Shortcut…” and check “Open as window”. This creates a window without the browser interface, which is convenient for using in full-screen mode.

Troubleshooting

-   Black screen or an error. WebGL is required. Enable hardware acceleration in your browser and update it.
-   Battery drain. The animation continuously uses the GPU. When running on battery power, reduce the speed or lamp size.
-   Settings are not saved. Your browser may block localStorage in private browsing mode. If that happens, change the values in DEF.

# Good luck!

# Tikam
