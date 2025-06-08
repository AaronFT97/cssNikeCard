# Responsive CSS Card

This is my first little project using new CSS skills I learned along the way. It's definitely not a perfect layout, but it gave me a better grasp of concepts like CSS Flexbox and media queries. 

![Mobile Design](/design/mobile-design.png)
![Desktop Design](/design/desktop-design.png)
### Challenges

Throughout this project, I worked through several CSS challenges:

* **Getting the Two Main Containers Horizontally Aligned for Desktop Viewport** I learned that to get that effect, I had to apply `display:flex` to the parent element.
* **Centering and Spacing Buttons** I had my doubts whether I should use the `position` property. But later on I learned it was not a good approach. And after some research, I found out that I could use `gap` and `justify-content` properties.
* **Being Meticulous with the Position of Span Element into a Container** I wanted to exactly replicate the position of an element from another layout which I inspired on. For `.product-description-span` , I tried with `position` property. The result was not strictly the same but it was the closest approach I could get. However, I'm not sure if there's a better method or practices to get this work done.
* **Adapting the Card for Mobile Screens** I didn't think about this decision when I started this project. In fact, the design I inspired on had only a desktop version. I just wanted to make it responsive when I completed the main code. And even though I initially wanted to change the position of some buttons and text, this time I decided to make it simpler and easier and just applied `flex-direction: column;` for the main container on the media query.      


### Key Takeaways

This small project was a great learning experience. My main takeaways are:

* **The Power of Flexbox:** I gained practical experience using `display: flex` for layout. Specifically, I learned how `flex-direction`, `justify-content`, `align-items`, and `gap` work together to create clean, responsive designs.
* **Mobile-First Thinking with Media Queries:** Using a `@media` query to change the `flex-direction` from `row` to `column` was an "aha!" moment. It's a simple yet powerful technique for responsive design. Next time, I'll try a mobile-first approach as I find it simpler than starting with the desktop layout.
* **CSS Custom Properties (Variables):** Using variables like `--mainColor` at the `:root` level made managing the color scheme incredibly easy and efficient. It's clear how valuable this would be in a larger project.

### Technologies Used

* HTML
* CSS
* [Google Fonts](https://fonts.google.com/)
* [Font Awesome](https://fontawesome.com/) (for the thumbs-up icon)
