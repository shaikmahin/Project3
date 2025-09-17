# Project3
Rotating navigation is a web design technique where the main content area of a page visually rotates (or slides) to expose a side menu, often a hidden navigation list.

It's achieved by combining the core web technologies:

HTML: Provides the basic structure, including the main content container, the off-screen navigation menu, and the toggle button (often a "hamburger" icon).

CSS: The most crucial part. It uses the transform: rotate() property (often around −20 
∘
 ) on the main content container. The transform-origin: top left; property sets the pivot point, making the content appear to swing from the side. A transition property ensures the movement is smooth.

JavaScript: Handles the user interaction. It listens for a click on the toggle button and then dynamically adds (or removes) a CSS class (e.g., .show-nav) to the main container. This class triggers the CSS transformations that perform the rotation and reveal the menu.
