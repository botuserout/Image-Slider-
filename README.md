# Image-Slider-
This is an HTML document that displays an image slider with the title "Image Slider BY RAKESH". The slider contains six items, each with an image and content. The content includes a paragraph and a heading with a link to a Wikipedia page. The slider also has navigation arrows and a thumbnail section.
**Structure**
**The HTML document is structured as follows:**

head section: contains meta tags for character encoding and viewport settings, a title, and a link to an external stylesheet.
body section: contains a header section with a logo, a slider section with a list of slider items, navigation arrows, and a thumbnail section.
Each slider item contains an image and content, which includes a paragraph and a heading with a link to a Wikipedia page.
The thumbnail section contains thumbnail items with images and content.
**The JAVASCRIPT document is structured as follows:**
This script is used to create a basic slider functionality with thumbnails. It allows users to navigate through the slider items using the next and previous buttons and also auto-advances the slider every 3 seconds.
Variables and Selectors
items: Select all slider items with the class slider, list, and item.
next and prev: Selects the next and previous buttons with the IDs next and prev, respectively.
thumbnails: Select all thumbnail items with the class thumbnail and item.
countItem: The total number of slider items.
itemActive: The current active slider item index.
Event Listeners
next. onclick: Increments the active item index and shows the new active slider item.
prev.onclick: Decrements the active item index and shows the new active slider item.
thumbnails.forEach: Adds an event listener to each thumbnail item, setting the active item index to the clicked thumbnail index and showing the new active slider item.
**Functions**
showSlider(): Removes the active class from the old active item and thumbnail, and adds the active class to the new active item and thumbnail. Also, clears and resets the interval to auto-advance the slider every 3 seconds.
**Interval**
refreshInterval: Sets an interval to auto-advance the slider every 3 seconds by simulating a click on the next button.

**--------How to Use-------**

**------Prerequisites------**
A web browser that supports HTML, CSS, and JavaScript
The style.css file for styling the slider
The script.js file for JavaScript functionality
The images used in the slider, stored in an image folder
**---------Usage-----------**
Open the index.html file in a web browser.
The slider will display the list of images with corresponding content.
Use the navigation arrows to move through the slider items.
Click on a thumbnail to view the corresponding image and content.
