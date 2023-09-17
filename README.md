# grid-template
https://tanishka-khamesara.github.io/grid-template/grid.html




![Screenshot (89)](https://github.com/Tanishka-khamesara/grid-template/assets/127411985/1f58f4c4-eb33-42e3-8dce-d03cbf834cf7)
![Screenshot (90)](https://github.com/Tanishka-khamesara/grid-template/assets/127411985/55399234-dde5-483a-b8f6-c5d328964e0e)
![Screenshot (91)](https://github.com/Tanishka-khamesara/grid-template/assets/127411985/1c7c5981-b7c7-4fc2-be51-76bea934c391)
![Screenshot (92)](https://github.com/Tanishka-khamesara/grid-template/assets/127411985/87477ea6-87ec-48b5-9b6b-0fcd05700da8)
![Screenshot (93)](https://github.com/Tanishka-khamesara/grid-template/assets/127411985/fb027e35-d1a5-485e-88d3-d8335570ff50)
HTML EXPLAINATION-->
<!DOCTYPE html>: Declares the document type and version of HTML being used.
<html lang="en">: Defines the HTML document and specifies the language as English.
<head>: Contains metadata about the HTML document.
<meta charset="UTF-8">: Sets the character encoding to UTF-8 for proper text rendering.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport properties for responsive design.
<title>: Sets the title of the web page displayed in the browser tab.
<link rel="stylesheet" href="style.css">: Links an external CSS file called "style.css" for styling.
<body>: Contains the visible content of the web page.
<main class="main">: Defines the main content section of the page with a class attribute for styling.
<article class="t1 testimonial light">: Represents a testimonial section with specific classes for styling.
<div>: A generic container for grouping and styling elements.
<img src="..." alt="...">: Embeds an image with a source URL and alternate text for accessibility.
<h2>: Defines a level 2 heading.
<p>: Represents a paragraph of text.
</article>: Closes the testimonial article section.
</body>: Ends the body of the HTML document.
</html>: Closes the HTML document.

![Screenshot (94)](https://github.com/Tanishka-khamesara/grid-template/assets/127411985/9ef32d37-a552-42da-b42c-425cdda5eb92)
![Screenshot (95)](https://github.com/Tanishka-khamesara/grid-template/assets/127411985/2b3ecd5e-22df-4999-911f-2dd0f1c38df4)
![Screenshot (96)](https://github.com/Tanishka-khamesara/grid-template/assets/127411985/f9519cd3-fd28-4b08-8ac9-255a7ee13251)
![Screenshot (97)](https://github.com/Tanishka-khamesara/grid-template/assets/127411985/d1db0db6-c2f8-42cb-b2b6-b2944bd6f674)
CSS EXPLAINATION-->
*: Targets all elements and sets their box model, margin, padding, font, and font-weight properties.
box-sizing: Specifies the box model to include padding and border in element sizing.
margin: Sets the outer spacing around elements to zero.
padding: Sets the inner spacing within elements to zero.
font-family: Defines the preferred font family for text content.
font-weight: Specifies the thickness of characters in the font.
body: Styles the entire webpage's background, display, and alignment.
display: Sets the display mode of an element (grid in this case).
place-content: Centers content both horizontally and vertically within an element.
min-height: Specifies the minimum height of an element as a percentage of the viewport height.
background-color: Sets the background color of an element.
.main: Styles the main content container using grid layout, defining grid areas, width, gap, and padding.
grid-template-areas: Defines the layout of child elements within the grid container.
width: Sets the maximum width of the grid container.
gap: Specifies the gap between grid items.
grid-auto-columns: Sets the size of automatically generated grid columns.
padding-block: Sets the padding on the block axis (top and bottom).
margin-inline: Sets the margin on the inline axis (left and right).
.testimonial: Styles testimonial elements, including padding, border-radius, and box-shadow.
.t1, .t2, .t3, .t4, .t5: Styles specific testimonial elements with unique backgrounds.
.light, .dark: Styles text color for light and dark testimonial sections.
.desc-heading: Styles font size and margin for description headings.
.desc: Styles opacity, font size, line height, and margin for descriptions.
.name: Styles the container for names and images using flex layout and gap.
.name img: Styles images within name containers, applying border-radius and width.
.name h2: Styles heading font size within name containers.
.name p: Styles paragraph font size and opacity within name containers.
