# article-simple-css
A simple approach to designing a single-column responsive article with CSS, sans media queries, complete with a fixed footer and a background-image friendly header.

By browsing the details of the CSS, you may discover a number of increasingly common designs & styles that can be found in most websites today.

* *Note: Not all the styles (background-image properties in particular) are supported by older browsers as-is, so be sure to test them for yourself when using this as a reference tool. The support for more intituive CSS styles is becoming better and more ubiquitos, but front-end designers should always be cautious to assume that the latest and greatest CSS rules will work for every user.*

## Background-image-friendly feader
The header is layered into three sections:
* An empty div with background-image properties
* A content container with padding rules and a transparent, but dark, background-color
* The written content itself (headers)

This allows the text to readable, but the background image to be seen through the negative space--a common practice in many websites today.

## Typography
Utilizes remote Google Fonts and well-supported typography styles to create a light-weight but balanced hierarchy.

## Fixed footer
This is optional, but is also a feature many websites use today, for instance: a fixed navigation bar on mobile devices. Remove the "fixed" class from the div containing the footer element to turn this off and return the footer to the normal flow of the website (it will appear after everything else).

## Positioning
The inline "Yes/No" list items are a way of turning a traditionally stacked list into a horizontal UI, and placing it exactly where you want it within a parent element. Replace the text with CSS dimensions (width/height, etc.) and add icons as background images to fill the empty list-items for the full effect.
