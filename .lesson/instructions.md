# Instructions  

The coding challenges will be centred around creating a food recipe web page. There are 3 main parts you will work on:

1.  Creating the recipe structure using HTML (8 marks)
2.  Writing some 'reviews' and formatting with HTML (4 marks)
3.  Styling the HTML elements using CSS (8 marks)

## Recipe HTML
Write the appropriate HTML to display the recipe content on a web page. This should include:

-   A semantic container element appropriate for this kind of distributable/reusable content
-   The name of the food as a heading, with a suitable id attribute
-   An image of the food which you have found from a creative commons source. It should:
    -   be imported on your page as a relative path to an uploaded file on replit
    -   include a clickable link to the image source as a caption below the image
-   3 different sections for the ingredients, instructions and reviews
-   An **Ingredients** subheading followed by a bullet-point list of ingredients
-   An **Instructions** subheading followed by a numbered list of instructions

## Reviews HTML

Inside the section your created for the reviews in the previous part, make **3 fictional reviews** for the recipe. Each review should have:

-   Some kind of generic container element to house the review content, with a suitable class attribute
-   A name for the fictional person leaving the review **(bold text)**
-   A rating out of 5 using star emojis:⭐
-   A date when they left the review *(italic text)*
-   A line to provide some visual separation
-   A text reviewing the recipe - write this yourself and be as creative as you want!

## CSS styles

Using the appropriate **element (type)** selectors:

-   Set the page background to the dark colour from your specified palette
-   Set the recipe container element background to the light colour from your specified palette
-   Apply 40px spacing:
    -   On the inside of the recipe container
    -   On the outside of each section
-   Set a single custom font for headings and subheadings
    -   Set all other text to the default browser sans-serif font
-   Set the link color to the dark colour from your specified palette when hovered over

Using an **id** selector:

-   Set the food name heading to be a larger font-size, aligned to the center of the page
-   Remove the top margin from the food name heading

Using a **child** selector:

-   Set the image width to be 100%

Using a **class** selector:

-   Apply 40px spacing
    -   On the inside of each review
    -   On the outside, but only on top of each review
-   Create a border around each review using the dark colour from your specified palette (you choose the style)