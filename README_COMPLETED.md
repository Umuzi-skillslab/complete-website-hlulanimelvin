## Portfolio Website README file.

## Overview

This is a portfolio project that is built using HTML5 and CSS. The project purpose is to showcase a person’s skills, projects, education and experience in software development.

 ## Major issues Found:

1.	There are no navigation links across all 4 pages.
2.	There are missing semantic elements like on all 4 pages.
3.	Divs are used instead of semantic elements on all 4 pages.
4.	There are missing meta elements on all 4 pages.
5.	The html element has no lang attribute.
6.	On the contact page form there are no labels for the input element.
7.	The image element on the about.html, index.html and projects.html pages have missing alt tags.
8.	There is a missing data table on the about page.
9.	The is header is not aligned on the CSS file.
10.	There was no styling for the navigation links.
11.	The colour combination in the CSS file has bad contrast.
12.	The hero image takes full width leaving no room for texts.
13.	The form is inadequately styled in CSS file.
14.	The footer is not aligned to the left instead of center.
15.	There is no styling for the data table all.

## Fixes Implemented:

1.	Implemented a consistent nav section on all pages with links to Home, About, Projects, and Contact pages. 
2.	Replaced generic div elements with proper semantic elements such as header, nav, main, section and footer to improve structure and accessibility.
3.	Refactored layouts to reduce overuse of div tags and ensure meaningful HTML structure. 
4.	Included essential meta tags to all pages.
5.	Updated the html tag with lang="en" to improve accessibility and SEO. 
6.	Added label elements properly linked to inputs using the for and id attributes to improve usability and accessibility. 
7.	Added alt text for all images to improve accessibility. 
8.	Created a structured table to display relevant information like skills, education and experience.
9.	Fixed the header alignment using CSS using flexbox.
10.	Added CSS styles for navigation links, including spacing and hover effects.
11.	Updated color combinations to ensure better readability.
12.	Adjusted hero image width size to 50% to ensure it doesn’t fill the page.
13.	Styled form inputs, labels, and button for better spacing, alignment, and usability. 
14.	Cantered the footer content using CSS (text-align: center). 
15.	Added CSS for the table including borders, padding, and alternating row colors to improve readability.

 ## HTML Structure & Semantic Choices:

The website uses semantic HTML to improve readability and accessibility:
1.	header for the top section with navigation.
2.	nav for menu links.
3.	main for primary content.
4.	section for grouping related content. 
5.	footer for bottom information. 
This structure improves both maintainability and SEO.

## CSS Styling Approach:
1.	Used class selectors for reusable styles. 
2.	Used element selectors for general styling.
3.	Applied flexbox for layout alignment. 
4.	Added hover effects for navigation links. 
 

## Accessibility Improvements:
1.	Proper label associations with form inputs. 
2.	Added alt attributes to images.
3.	Improved color contrast for readability. 
4.	Used semantic HTML elements.

 ## How to Run Locally:
1.	Download or clone the repository. 
2.	Open the project folder.
3.	Double-click index.html
4.  Open with browser.

## Screenshots:
•	Home page
![Home screenshot](/screenshots/home_screenshot.png)
•	About page
![About screenshot](/screenshots/about_screenshot.png)

•	Projects page.
![Home screenshot](/screenshots/projects_screenshot.png)

•	Contact page
![Home screenshot](/screenshots/contact_screenshot.png)
•   Navigation menu with hover states
![Home screenshot](/screenshots/hover_screenshot.jpeg)



## Reflection:

While debugging the starter code, I faced challenges like fixing mismatched labels and inputs, correcting structural issues without affecting the layout, and maintaining consistent styling across pages. I resolved these by reviewing validation errors, testing changes step by step, and applying proper HTML/CSS practices.
