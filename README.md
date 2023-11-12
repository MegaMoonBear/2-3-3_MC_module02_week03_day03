# JavaScript Events

## Assignment: Emoji Puppeteering

For this assignment you will make emojis come to life and perform an action when an event happens on the webpage

### Instructions
Link the script file (index.js) to the htnl file (index.html):
- Add a script tag to the **bottom** of the html file (index.html)
  - Change value of the 'src' attribute on the script tag to a file-path of the stylesheet.
  
**Part 1: Fade-In animation (FadeIn Folder)**
1. Create a "Fade-in" CSS animation for the banner.
   - Animate the banner's text color to gradually transition from white to black
     - Create a 'keyframes' block called 'FadeIn' that will transiton the color property from white to black
     - Define the styles for the "banner" class in your CSS. 
       - Set the text color to white.
       - Bind the animation to the style block by setting the value of the 'animation' property to the name of the keyframes block you created and the amount of time the animation should take  (FadeIn 1s)

**Part 2: Slide animation (Slide Folder)**
1. Create a "Slide" CSS animation for an emoji.
    - Animate the emoji to slide from left-screen to right-screen
       - Create a 'keyframes' block named 'Slide' that will change the position of an element from the left side of the screen to the right.
         - Use either the left or the right css property to achieve this 
      - Create a style block for the "#emoji" id
        - Set the position property to 'absolute'
        - Bind the animation to the style block by setting the value of the 'animation' property to the name of the keyframes block you created and the amount of time the animation should take (Slide 3s)

**Part 3: Grow animation (Grow Folder)**
1. Create a "Grow" CSS animation for an emoji.
    - Animate the emoji to grow in size 
       - Create a 'keyframes' block named 'Grow' that will change the font-size of an element to a larger size.
         - Use the 'font-size' property to achieve this 
      - Create a style block for the "#emoji" id
        - Bind the animation to the style block by setting the value of the 'animation' property to the name of the keyframes block you created and the amount of time the animation should take (Grow 1s)


Take a look at Example.png for an idea of how the end result should look.