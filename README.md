##Assignment: Advanced CSS

It's now time to lift your CSS skills to a new level with the following CSS challenges. In a real-world scenario, you as a developer will likely be given designs made by a UX department that you'll have to convert to code. That is exactly what you'll be doing today: you'll be turning a design into code! That means there are going to be multiple ways to achieve the desired result. Use your skills to come up with the solution you think is best. Recreate each design using HTML and CSS. You should not need to use JavaScript.

The assignment consists of 3 CSS challenges, each one being a little more difficult than the previous one.

You are allowed to use our Slack channels to ask any questions to your fellow students.

General requirements
For each exercise, use the SCSS principles you've learned throughout the course.

Complete all exercises on a single HTML page.
Consistently use SCSS nesting.
Consistently use SCSS variables.
Consistently use SCSS partial imports to separate your SCSS.
The page is not allowed to have horizontal scrolling unless the window is very small (less than 400px).
Bonus:

Use mixins.
Part 1 - Testimonial
Design
Recreate this design using HTML and CSS.

Testimonial card

Specifications
Footer testimonial - purple/blue: #686de0
Page background - gray: #c3cfe2
Text background - white: #fff
Use a random portrait image. This could be an image of yourself, or you could use a stock-photo
Part 2 - Portfolio Grid
In this part, you're going to make a portfolio grid. For now, we will have images in the grid, but you could put anything in it. For example, feel free to replace the image of our colleague Niels with the testimonial that you made in part 1.

Design & interaction
Watch the following video:

Specifications part 2
Page background - gray: #c3cfe2
The grid should be responsive on 3 screens: desktop (3 columns), tablet (2 columns), mobile (1 column)
When hovering an item in the grid, a button should appear, and the image should slowly fade away.
You do not need any JavaScript. Think back to the pseudo class :hover.

Placing elements on top of each other is known as "stacking". You can achieve this using the CSS attribute position. More about stacking here.

Part 3 - Social Media Buttons
Self-made social media buttons are always nice to have. These are very fancy; there's even a little animation!

You'll be recreating this:

Specifications part 3
Design & interactions

In the video, you can see a green line on the right-hand side. This is the desktop and not part of the website. The buttons are on the very edge of the page.

Colors

.social-media.blog {
background-color: #e17b77;
}

.social-media.facebook {
background-color: #3b5998;
}

.social-media.twitter {
background-color: #00aced;
}

.social-media.github {
background-color: #333;
}

.social-media.linkedin {
background-color: #007bb6;
}
Icons

Option 1: Look up the icons and use them as images in your CSS. this is correct and perfectly fine.

Option 2: Next level - add the images using ::before using, for example, font awesome:

Font Awesome

Font Awesome icons

In this last case, use the following code:

.fa-laptop-code::before {
content: "\f5fc";
}
.fa-twitter::before {
content: "\f099";
}
.fa-linkedin-in::before {
content: "\f0e1";
}
.fa-facebook-f::before {
content: "\f39e";
}
.fa-github::before {
content: "\f09b";
}
