# Welcome To Instagram!
You will be recreating your personal Instagram profile! If you do not have an Instagram profile you may look one up to recreate.

## Before you begin
- Find the profile that you want to recreate and get an instructor's approval. **NO INAPPROPRIATE PROFILES ALLOWED!**
- Create a mockup of your profile for an instructor to approve :)

## Set-up your files
Please create the following files:
- index.html
- styles.css<br>
Create a link tag for your CSS stylesheet in your html document.

<br/>
<p align="center">
<b>Here's an example of your final product:</b>
<img src="images/Example.png"></img>
</p>

## HTML
1. Create a header containing the username of your instagram profile using a **header** tag.


2. Create a main container for all of your icons and pictures using a **div** tag and set the value of the id attribute to `container`.


3. Within your `container` div, in **chronological** order: 
  - Create a **div** tag with an id of `top-bar`
  - Create a **div** tag with an id of `follower-count`
  - Create a **div** tag with an id of `bio`
  - Create a **div** tag with an id of `photo-bar`
  - Create a **div** tag with an id of `pictures`
  - Create a **div** tag with an id of `bottom-bar`<br>
_All divs should be sibilings inside the `container` div_

4. Inside the **div** with the id of `top-bar`, create a header using the **h1** tag containing the IG username; give this header an id of `username`.


5. Inside the **div** with the id of `follower-count`, add an **image** tag with an id of `profile-picture`.


6. Inside the **div** tag with an id of `bio`, add a **paragraph** tag containing information about you.


7. Inside the **div** tag with an id of `pictures`, add a **minimum of six** pictures using **image** tags assigning each with a *class* of `ig-image`.

## CSS
1. In your CSS file, set the background color of the body.


2. Using the `id` selector, modify the styles of the `container` accordingly: 
  - Give it a width of 1080 pixels
  - Align it to the center of the page
  - Set the background color to white
  - Using the border style property, add a solid border with a 3px width and hex color #DDDDDD


3. Using the `id` selector, modify `top-bar` accordignly:
  - Give it a height of 145 pixels
  - Set the background image to `Top-Bar.png` found in the *images* folder
  - Ensure that the background image does not repeat 


4. Using the `id` selector, center your username within the `top-bar`.


5. Using the `id` selector, modify `follower-count` accordignly:
  - Give it a height of 355 pixels
  - Set the background image to `Follower-Count.png` found in the *images* folder


6. Using the `id` selector, modify `profile-picture` accordignly:
  - Crop your profile picture to the shape of a circle 
  - Assign it a height and width of 255 pixels
  - Using margin-top and margin-left, position your profile pic within the background circle


7. Using the `id` selector, modify `photo-bar` accordignly:
  - Assign it a height of 140 pixels
  - Set the background image to `Photo-Bar.png` found in the *images* folder


8. Using the `class` selector, modify each picture/image so that there are only *three* images per row with each being square shaped (hint: use the display property to align images side by side while using **percentage** for the width of the image)


9. Using the `id` selector, modify `bottom-bar` accordignly:
  - Assign it a height of 135 pixels
  - Set the background image to `Bottom-Bar.png` found in the *images* folder


10. Continue to modify your elements with these style properties:
  - `padding`
  - `margin`
  - `font-size`
  - `font-family`
  - `height`
  - `width`
  - `text-align`

## Stretch Goals:
  - Use a **hover** pseudo selector to enlarge the picture when hovering over it
  - Add more pictures while maintaining 3 pictures per row
  - Since IG lets users post videos, add a video to you profile with **video** tag
  - Currently there are no numbers above your followers and posts, add numbers above it
  
## Resources:
Background Repeat - https://www.w3schools.com/cssref/pr_background-repeat.asp<br>
In-Line Block - https://www.w3schools.com/css/css_inline-block.asp<br>
Border Radius - https://www.w3schools.com/cssref/css3_pr_border-radius.asp<br>
Display Property - https://www.w3schools.com/cssref/pr_class_display.asp
