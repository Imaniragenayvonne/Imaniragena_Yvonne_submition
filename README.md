
This repository contains code for a web application showcasing a collection of wildlife photos along with their descriptions. Additionally, it includes JavaScript functions for manipulating DOM elements and performing various tasks such as applying hover styles, displaying more information about a photo, and transforming strings based on specific conditions.

 Files:

1. index.html**: This file contains the HTML structure for the web page. It includes div elements for displaying photos, their captions, and a modal for displaying detailed information about a selected photo.

2. style.css: This file contains the CSS styles used to design the layout, appearance, and responsiveness of the web page.

3. script.js: This file contains JavaScript functions that handle user interactions and perform dynamic actions on the web page. Functions include applying hover styles, showing more information about a photo, and transforming strings based on certain conditions.

Functions:

1. hasContiguousSubarrayWithSum(arr, target): This function checks if there is a contiguous subarray within the input array `arr` that sums up to the `target`. It iterates through the array and adjusts the starting and ending indices of the subarray to find the sum that matches the target.

2. applyHoverStyle(photo): This function applies hover styles to a photo when the user hovers over it. It adjusts the opacity, filter, transform, and display properties of the photo's elements to create a visual effect.

3. removeHoverStyle(photo): This function removes hover styles from a photo when the user moves the cursor away from it. It resets the styles to their default values.

4. showMore(element): This function displays more information about a selected photo in a modal. It extracts the image source and description from the clicked photo and updates the content of the modal accordingly.

5. closeSingleImage(): This function closes the modal displaying detailed information about a photo when the user clicks on the close button. It hides the modal and restores the display of all photos on the page.

6. transformString(input): This function transforms a given string based on specific conditions. If the length of the string is divisible by 15, it reverses the string and converts each character to its ASCII code separated by spaces. If the length is divisible by 3, it simply reverses the string. If the length is divisible by 5, it converts each character to its ASCII code separated by spaces. Otherwise, it returns the original string.

 Usage:

To use this web application, simply open the `index.html` file in a web browser. You will see a grid of wildlife photos displayed on the page. Hover over a photo to see additional information, and click on "Know more" to view detailed information about a photo in a modal.

 Dependencies:



- Font Awesome (version 6.5.1)
- Google Fonts: Bebas Neue, Kanit (version 2)

 Contributors:

Imaniragena Yvonne
