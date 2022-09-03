# Horiseon Refactoring Task 

## Description

This is the Challenge after completing the Unit 1 of Adelaide University Coding Bootcamp. 

## User Story

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

## Acceptance Criteria

GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

## Solution 

The following changes are made to the HTML file:
1. Change the title to a meaning description in the <head> tag. 
2. Add viewport attribute in the <head> tag. 
3. Specify the type of the link in the <head> tag. 
4. Review the attributes in <head> tag to ensure they are in proper ordering. 
5. Change the <div> tags to <header>, <nav>, <article>, <aside>, <section> and <footer> tag. 
6. Add title attribute for the <div> tag with background image. 
7. Add alt attribute for the images in the <img> tag. 
8. Add the missing #Id attribute to the search engine optimization section. 

The following changes are made to the CSS file:
1. Change the corresponding class selectors to element selectors. 
2. Group the repeated class selectors with the same styles to the corresponding section selectors. 
3. Remove the repeated class seelctors from the file. 
4. Examine and ensure the order of the selectors lised in the file following the logical sequence. 

## How to review the solution

1. Click the Github Page link to open the page in Chrome browser. On the page, right click "Inspect" to review the code in Dev Mode. 

2. Click the Github repository link to examine the files in the repository.


## Installation 

No installation required. 

## License 

No Applicable  
