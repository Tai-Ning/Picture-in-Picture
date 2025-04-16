#  Picture-in-Picture 
A floating screen sharing demo using the modern **Picture-in-Picture API**.  
Useful for multitasking — keep a mini screen window while browsing other content.  
This project demonstrates how to capture the screen and display it in a small movable window using native browser APIs.

👉 **[Live Demo](https://tai-ning.github.io/Picture-in-Picture/)**

##  Features

-  **Live screen capture** with `getDisplayMedia()` — captures full-screen or app window based on user selection
-  **Floating video window** with `requestPictureInPicture()` — allows multitasking while keeping the screen visible
-  **Responsive UI design** with custom fonts, shadows, and gradient-styled buttons
-  **Error-handling included** — detects permission denial or unsupported browsers gracefully
-  **Auto-init on page load** — screen prompt starts automatically without extra user setup


##  Tech Stack

- HTML5
- CSS3 (Flexbox, linear gradients, custom fonts)
- JavaScript 
- MediaDevices API
- Picture-in-Picture API

##  Preview 
![Quote Screenshot](Picture-in-Picture.gif)
This demo shows how the Picture-in-Picture API allows a user to share their screen and pop it into a floating video window that stays visible while browsing other tabs or apps — great for multitasking!

##  How to Use

1. When the page loads, it will prompt you to share your screen.
2. Click the `START` button to activate Picture-in-Picture mode.
3. A floating video window will appear with your shared screen.
4. You can click outside to work freely while keeping the mini screen visible.

> 💡 **Browser Support:** Only supported in modern browsers like **Chrome**, **Edge**, and some versions of **Opera**.

