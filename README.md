# Hosted link https://ayush19bansal.github.io/box_model/
# HTML
![image](https://github.com/Ayush19bansal/box_model/assets/118842033/18784a67-3097-46ac-96cd-e4fac31a1507)
This HTML code represents a webpage structure with various nested elements:

- The outermost container has a class "main_container".
- Inside it, there is a container with class "container".
- Within this "container", there are three main divisions:
  1. "conatner1" containing an `h1` header saying "I'm a box".
  2. "content2" containing a paragraph with Lorem ipsum text.
  3. An unordered list with class "content3", containing two list items, each saying that they are boxes.
- Finally, there is a "footer" division with a button and a link styled as boxes.

The content is organized within these nested divisions, and elements like headers, paragraphs, lists, buttons, and links are all enclosed within these containers, forming a structured layout for the webpage. The text inside these elements varies, but the common theme is that they're all referred to metaphorically as "boxes".*

# CSS
![image](https://github.com/Ayush19bansal/box_model/assets/118842033/6cd49be3-d55e-4f27-935e-f927d03c9de9)
![image](https://github.com/Ayush19bansal/box_model/assets/118842033/22414175-a19a-42dc-9ba7-c32af569eb4f)
This is a CSS code snippet that provides styling for the HTML structure you previously described:

- The `*` selector sets default styling properties for all elements, including zero margins and padding while accounting for the box model.
- `.main_container` styles the outermost container with hidden horizontal overflow, making it span the entire viewport width and height.
- `.container` styles the main content container with a red border, 50% width and height, and centered alignment using margin.
- `.conatiner1` (typo: should be `.container1`) styles the sub-container with a red border, 10% padding, and 20% top margin and 10% side margin.
- `h1` styles the header with centered text alignment, red border, and margin and padding.
- `.content2` styles the content section with a red border and margin and padding.
- `.content3` styles the unordered list with a red border, margin, and padding.
- `.one` and `.two` styles the list items with red borders, padding, and outside list-style positioning.
- `.footer` styles the footer section with margin.
- `.f1` and `.f2` styles the button and link within the footer with red borders.

Overall, the CSS rules define a consistent visual style for the various sections and elements within the HTML structure, with red borders highlighting each section's boundaries, and controlled margins and padding for spacing and alignment. The "box-sizing: border-box" property ensures that padding and borders are included in the specified width and height.
