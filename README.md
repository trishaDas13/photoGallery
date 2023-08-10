# photoGallery
https://trishadas13.github.io/photoGallery/

Website page:-

![1A](https://github.com/trishaDas13/photoGallery/assets/126088849/668a94d7-5189-4c5d-b587-cda08f9134cf)

HTML:- 

![1B](https://github.com/trishaDas13/photoGallery/assets/126088849/7b2efde7-7d36-4bc6-9413-9899d366f171)

Header: The "header" is a semantic HTML element used to define a container for introductory content or navigation menus typically placed at the top of a webpage.

H1: The "h1" tag represents the highest-level heading, often the main title of a webpage, conveying its primary topic or purpose.

CSS:- 

![BOX1](https://github.com/trishaDas13/photoGallery/assets/126088849/0a45376b-1f25-4a09-b381-b2c63a5b17a9)

For * (all elements):

box-sizing: border-box;
I've applied the border-box box-sizing model to all elements. This ensures that padding and borders are included in the element's total width and height, helping to maintain consistent layouts and preventing unexpected layout changes.
For body:

margin: 0;
I've set the margin of the body element to 0. This ensures that there's no default margin around the entire page, providing a cleaner layout.

font-family: sans-serif;
I've chosen a sans-serif font-family for the text content on the page. This type of font is commonly used for better readability on screens.

background: #f5f6f7;
I've set the background color of the body element to a light grayish color (#f5f6f7). This creates a pleasant background tone for the entire page.

For .header:

text-align: center;
I've centered the text content within elements with the class .header. This applies to the text alignment within the header.

text-transform: uppercase;
I've transformed the text content within elements with the class .header to uppercase. This makes the text appear in all capital letters.

padding: 32px;
I've applied 32 pixels of padding to elements with the class .header. This adds spacing around the content within the header.

background-color: #0a0a23;
I've set the background color of elements with the class .header to a dark blue color (#0a0a23). This creates a visually appealing header background.

color: #fff;
I've set the text color of elements with the class .header to white (#fff). This ensures that the text within the header is easily readable against the dark background.

border-bottom: 4px solid #fdb347;
I've added a 4-pixel solid border at the bottom of elements with the class .header. This creates a colored border line at the bottom of the header, enhancing its visual appeal. The border color is a shade of orange (#fdb347).

Webpage:- 

![1](https://github.com/trishaDas13/photoGallery/assets/126088849/4d4242aa-b22f-4793-ba0e-c7a531a4fadf)

html:-

![1a](https://github.com/trishaDas13/photoGallery/assets/126088849/8c6c4548-fd8d-4b62-aefb-e6d09d0773fb)

Div Tag: The "div" tag is a versatile HTML container used for grouping and styling elements, aiding in layout structuring and design organization.

Img Tag: The "img" tag embeds images in web pages, while the "src" attribute specifies the image file's URL or path, and the "alt" attribute provides alternative text for accessibility or when images cannot be displayed.

css:- 

![1b](https://github.com/trishaDas13/photoGallery/assets/126088849/ef4a10c0-352f-4637-b055-c96972d80412)


For .gallery:

display: flex;
I've set the display property of elements with the class .gallery to flex. This establishes a flex container for the gallery, enabling flexible layout and positioning of its child elements.

flex-direction: row;
I've set the direction of flex items within .gallery to be in a row. This means the images and other content will be arranged horizontally from left to right.

flex-wrap: wrap;
I've specified that flex items should wrap to a new line if they exceed the available width of the container. This ensures that items within the gallery will wrap to a new row when necessary.

justify-content: center;
I'm aligning the flex items along the horizontal axis to the center within .gallery. This centers the items horizontally in the container.

align-items: center;
I've aligned the flex items along the vertical axis to the center within .gallery. This centers the items vertically in the container.

gap: 16px;
I've added a gap of 16 pixels between the flex items in .gallery. This creates spacing between the images and enhances the overall layout.

max-width: 1400px;
I've set a maximum width of 1400 pixels for .gallery. This ensures that the gallery won't exceed this width on larger screens.

margin: 0 auto;
I've centered .gallery horizontally within its parent element using margin: 0 auto;. This provides an equal margin on the left and right sides, effectively centering the gallery.

padding: 20px 10px;
I've added padding of 20 pixels on the top and bottom, and 10 pixels on the left and right sides of .gallery. This creates spacing between the gallery and its surrounding elements.

For .gallery img:

width: 100%;
I've set the width of images within .gallery to be 100% of their containing element's width. This ensures that images scale to fit their container.

max-width: 350px;
I've set a maximum width of 350 pixels for images within .gallery. This limits the image size on larger screens.

height: 300px;
I've set a fixed height of 300 pixels for images within .gallery. This ensures a consistent height for all images, preventing distortion.

object-fit: cover;
I've used object-fit: cover; to ensure that images maintain their aspect ratio while covering the entire available space. This prevents images from being stretched or distorted.

border-radius: 10px;
I've applied a border-radius of 10 pixels to images within .gallery. This gives the images rounded corners, adding a softer visual touch.

For .gallery::after:

content: "";
I've used the ::after pseudo-element to add an empty content box after .gallery. This is used for layout purposes in combination with the specified width below.

width: 350px;
I've set the width of the ::after element to 350 pixels. This creates a placeholder width that aligns with the width of the images, contributing to the overall layout of the gallery.

Final product:--

![1](https://github.com/trishaDas13/photoGallery/assets/126088849/9886bd4e-4557-4cc3-9a9b-61fb51773141)

