# Animation-webpage

Hosted Link:- https://lok-ii.github.io/Animation-webpage/

![Screenshot 2023-08-25 202306](https://github.com/Lok-ii/Animation-webpage/assets/129180844/a7d3f537-d34f-4116-bd4c-0814f45735ca)

        This HTML document represents a simple webpage with a <main> section containing three images.

        CSS Used:

            *: Selects all elements on the page.
                box-sizing: border-box;: Ensures all elements include padding and border dimensions in their total width and height calculations.
                margin: 0; padding: 0;: Removes margin and padding from all elements, ensuring a consistent baseline.
            
            Body Styles:
            
                body: Styles for the entire page body.
                display: flex;: Uses flexbox to align content.
                background-color: black;: Sets the background color of the body to black.
                justify-content: center; align-items: center;: Centers content horizontally and vertically.
                min-height: 100vh;: Ensures a minimum height of the viewport to ensure content is visible.
           
            Main Styles:
            
                main: Styles for the <main> element.
                display: flex;: Uses flexbox to arrange child elements.
                justify-content: space-between;: Creates even spacing between child elements.
                -webkit-box-reflect: below 1px linear-gradient(transparent, transparent, #0004);: Adds a subtle reflection effect beneath images.
            
            Image Styles:
            
                main img: Styles for the images within the <main> section.
                max-width: 350px;: Limits the maximum width of images to 350 pixels.
                border-radius: 5px;: Adds a slight border radius to create rounded corners.
                box-shadow: 0px 0px 6px -2px white;: Adds a white box shadow to images for a subtle 3D effect.
                transform-origin: center;: Sets the transformation origin to the center.
                transform: perspective(800px) rotateY(20deg);: Applies a 3D rotation effect with a perspective, giving images a tilted appearance.
                transition: 0.5s;: Specifies a smooth transition effect for changes to the images' properties.
            
            Hover Effects:
            
                main:hover img: Styles for images when hovering over the <main> section.
                
                    opacity: 0.1;: Reduces the opacity of images when hovering over the <main> section, creating a fade-out effect.
                
                main img:hover: Styles for images when hovering over individual images.
                
                    transform: perspective(800px) rotateY(0deg);: Removes the rotation effect, returning images to their original state.
                    opacity: 1;: Restores full opacity when hovering over individual images, creating a fade-in effect.
                      
            This code results in a webpage with a centered <main> section containing three images.
            The images have several stylistic effects, including rounded corners, a 3D rotation on hover, and opacity changes.
            The layout is responsive, adjusting to the screen size while maintaining alignment and visual appeal.
