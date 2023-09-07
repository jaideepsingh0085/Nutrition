# Nutrition
![Screenshot 2023-09-08 000221](https://github.com/jaideepsingh0085/Nutrition/assets/128147644/7c5d8eba-6212-4441-9674-ef7fcb146743)
![Screenshot 2023-09-08 000232](https://github.com/jaideepsingh0085/Nutrition/assets/128147644/30732eaa-26dc-453f-a4fe-56070785965e)
![Screenshot 2023-09-08 000241](https://github.com/jaideepsingh0085/Nutrition/assets/128147644/dde763ea-808f-45d0-9064-9891d6b6d579)
![Screenshot 2023-09-08 000253](https://github.com/jaideepsingh0085/Nutrition/assets/128147644/e9ff3eaf-3749-4d97-8874-4ae0f7c3366d)
![Screenshot 2023-09-08 000304](https://github.com/jaideepsingh0085/Nutrition/assets/128147644/c05b83df-44e1-41c2-8719-9407a29eeef1)
Hosted Link: https://jaideepsingh0085.github.io/Nutrition/index.html

Description : 
<div class="label">: This <div> element acts as a container for the entire nutrition label.

<header>: The <header> element contains the header information for the nutrition label, including the title "Nutrition Facts," servings per container, and serving size.

<h1 class="bold">Nutrition Facts</h1>: This <h1> tag displays the title "Nutrition Facts" with a "bold" class applied for styling.

<p>8 servings per container</p>: This <p> tag displays information about the number of servings per container.

<p class="bold">Serving size <span>2/3 cup (55g)</span></p>: This <p> tag displays the serving size, with a "bold" class applied, and includes a <span> element for additional styling of the serving size.

Various <div> and <span> elements with different classes are used to structure and style the content of the nutrition label.

<p class="note">* The % Daily Value (DV) tells you how much a nutrient in a serving of food contributes to a daily diet. 2,000 calories a day is used for general nutrition advice.</p>: This <p> tag displays a note at the bottom of the label.

The HTML structure and classes are used to format and style the content, while CSS styles from external stylesheets are likely applied to control the appearance of the label's elements.

* { box-sizing: border-box; }: This is a universal selector that applies the box-sizing property to all HTML elements. It ensures that an element's padding and border are included in its total width and height calculations.

html { font-size: 16px; }: This sets the base font size for the entire HTML document to 16 pixels. It establishes a baseline font size that can be used for relative sizing in other elements.

body { font-family: 'Open Sans', sans-serif; }: This defines the font family for the text within the <body> element. It specifies "Open Sans" as the preferred font, with a fallback to generic sans-serif fonts.

.label { border: 2px solid black; width: 270px; margin: 20px auto; padding: 0 7px; }: These styles are applied to an element with the class "label." It adds a black border, sets a fixed width of 270 pixels, centers the element horizontally using margin: 20px auto;, and adds padding on the left and right sides.

header h1 { text-align: center; margin: -4px 0; letter-spacing: 0.15px; }: These styles are applied to an <h1> element within the <header>. It centers the text using text-align: center;, removes default margins using margin: -4px 0;, and adjusts the letter spacing for the header text.

p { margin: 0; display: flex; justify-content: space-between; }: These styles are applied to all <p> elements. It removes default margins with margin: 0;, and it makes the <p> elements flex containers with display: flex; and justifies content evenly, creating space between elements using justify-content: space-between;.

.divider { border-bottom: 1px solid #888989; margin: 2px 0; }: These styles are applied to elements with the class "divider." It adds a bottom border with a 1-pixel solid line and provides vertical spacing above and below the elements with margin: 2px 0;.

.bold { font-weight: 800; }: This class defines bold text by setting the font-weight property to 800, which is a heavier font weight.

.large { height: 10px; }: This class sets the height of elements with the class "large" to 10 pixels.

.large, .medium { background-color: black; border: 0; }: These styles apply a black background color and remove borders for elements with either the "large" or "medium" class.

.medium { height: 5px; }: This class sets the height of elements with the class "medium" to 5 pixels.

.small-text { font-size: 0.85rem; }: This class reduces the font size to 0.85 rem (root em unit) for elements with the class "small-text."

.calories-info, .calories-info h2, .left-container p, .calories-info span, .right, .indent, .double-indent, .daily-value p:not(.no-divider), .note: These are class selectors used to apply specific styles to various elements within the nutrition label. They include margin adjustments, font sizes, and other styling properties.
