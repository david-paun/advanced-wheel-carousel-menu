A fork of an HTML/JS/CSS Advanced Spinning Wheel Carousel

I created this for the purpose of my own portfolio website. You can see a live implementation of it here: https://david.mvisionhost.com/contact-me/

I tried to make some of the functionalities dynamic in nature so that a future user can modify/remove them by tweaking global variables individually

---------------------------------------------------------------------------------------------------------------------------------------------------------

Here's a list of fuctionalities that were added:

added a content section to the right of the gallery that updates dynamically based on user interaction with the wheel

added a back-end global variable to dynamically set the amount of entires in the gallery and made sure that the rest of the logic adjusts to this dynamically

added click functionality that works interchangably with the scrolling functionality of the wheel

adjusted the wheel radius of the gallery to grow slightly disproportianately as the screen increases to accomodate for mobile and desktop screen at the same time

created a 360 spin animaition on screen load which can be toggled on/off in the back end via a global variable

made some slight mobile optimizations to the gallery as well as the content section

changed the logic of the main spinning function as well as the onLoad trigger to make sure that the gallery is in a predefined ON position when the page loads (as opposed to waiting for user interaction in order to show something in the content section and enlarge the entry that's located in the focus position on screen load)

gallery entries are styled dynamically based on whether they are currently in focus or not

---------------------------------------------------------------------------------------------------------------------------------------------------------

If you need help in uderstanding some of the math and structure of the JavaScript code start by reffering to the YouTube videos of the original creator:

Original Creator's Initial video: https://www.youtube.com/watch?v=boTzMxNn7UE&t=0s

Original Creator's Improved video: https://www.youtube.com/watch?v=w_t-y_kKGoY&t=211s

---------------------------------------------------------------------------------------------------------------------------------------------------------

If you have any questions about the added functionalities in this fork feel free to reach out! :)
