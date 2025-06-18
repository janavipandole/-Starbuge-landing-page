JavaScript Functionality (app.js)

Purpose:
Controls the carousel's behavior, such as navigating between slides, triggering animations, and setting automatic transitions.
Key Features:
next.onclick / prev.onclick: Handles next/previous button clicks and updates the active slide.
changeSlider(): Updates the active, other_1, and other_2 classes to show/hide slides and restart animations.
autoPlay: Automatically moves to the next slide every 5 seconds.

HTML Structure
Purpose:
Defines the content and layout for a Starbucks coffee product carousel.
Key Elements:
<header>: Contains the logo and navigation menu.
<section class="carousel">: The carousel component with multiple .item articles.
.item: Each product slide includes:
Product info (.main-content)
Product image and name (<figure class="image">)
Navigation Arrows: Buttons (#prev, #next) to change slides manually.


CSS Styling (style.css)
Purpose:
Handles layout, transitions, animations, and responsiveness for the carousel.
Key Components:
Base Styles
Sets fonts, box model, and basic layout using Grid.
Uses custom properties (--w-image, --calculate) to adapt layout.
Carousel
.item.active: Main visible item.
.item.other_1 / .item.other_2: Previous/next items used for smooth transition effect.
Uses @keyframes animations like effectNext, effectPrev, and showContent.
Arrow Controls
Styled buttons for previous/next navigation.
Appear over the content and change background on hover.
Responsive Design
Adjusts layout and font sizes for tablets and mobile.
Hides textual content on small screens and centers images.

