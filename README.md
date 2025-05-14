# 101 Infinite Scroll

This project was created to show how it is possible to implement infinite scroll functionality without the need for external libraries, using only **JavaScript**, **HTML** and **CSS**. Infinite scrolling is a common technique in modern web applications, allowing for dynamic loading of content as the user scrolls down the page. This provides a more fluid and efficient user experience, especially in applications that handle large volumes of data, such as social media feeds, product catalogs, and news listings.

- **Virtualization** (*Virtual Scrolling*): Renders only the elements visible in the viewport and a small buffer of elements above and below. This reduces the number of active DOM elements and improves performance.
- **Lazy Loading**: Loads images and other heavy resources only when they enter the viewport. This saves bandwidth and speeds up the initial page load time.
- **DOM Fragmentation**: Keeps the DOM small by removing or hiding old elements as new elements are added. This prevents the DOM from growing indefinitely, which could cause slowness.
- **Batching Updates**: Groups multiple DOM operations into a single reflow/repaint, reducing the amount of work the browser needs to do.

## License

Project developed for academic purposes.

[![License: MIT](https://img.shields.io/github/license/guiigos/node-express-async?style=flat-square)](./LICENSE)
