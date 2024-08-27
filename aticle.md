# Nigeria Flag Animation Using HTML and CSS
This article showcase a simple HTML and CSS design that celebrates Nigeria's Independence Day. The implementation contains a structured HTML layout styled with CSS, creating a visually appealing effect.
```html
<div class="flag">
        <div class="green"></div>
        <div class="white"></div>
        <div class="green right"></div>
    </div>
    
    
    <div class="message">
        <p>Today, we celebrate the resilience and strength of our great nation.</p>
        <p>May the spirit of independence live on in our hearts!</p>
    </div>
```
 - The
```html
 <div class="flag">
```
acts as a container for representing a flag image through its child
elements. Each child
(green and white) corresponds to different colors of the flag, which may be styled using CSS . The class attributes allow for targeted styling through CSS or JavaScript.
```css
@keyframes wave {
            0% {
                transform: translateY(0);
            }
            25% {
                transform: translateY(-5px);
            }
            50% {
                transform: translateY(0);
            }
            75% {
                transform: translateY(5px);
            }
            100% {
                transform: translateY(0);
```
- The animation creates a visual effect that mimics the gentle undulating or floating motion, which can make elements (like a flag) appear alive and dynamic.
## conclusion
The HTML structure uses a container along with nested elements to represent the three distinct sections of the Nigerian flag, which are styled through CSS. This approach allows for clear layout organization, ensuring each color segment is distinctly defined.