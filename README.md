# anu-pre-interview-task
Naomi Pham - ANU Pre-interview task

## Overview
Create an equal-height card grid that displays at least 6 event items with a title, date, short summary, and link. The grid is to be responsive across mobile and desktop screen sizes, and accessible.

## Tech stack
HTML\
CSS\
Bootstrap 5.3.8

## How to run project
1. Download or clone the repository.
``` bash 
git clone https://github.com/naomipham/anu-pre-interview-task.git
```
2. Navigate to the project folder.
3. Double-click the index.html file OR right-click > Open with your preferred browser.

## Approach
- Built the page using semantic HTML to follow accessibility and SEO best practices and ensure a clear, meaningful structure for all users.
- Used the Bootstrap framework to create a responsive layout efficiently, leveraging its grid system and components to help streamline development while maintaining consistency.
- Organise files into logical folders to improve maintainability, and ease navigation throughout the project.


## Assumptions
- Events data is static and hardcoded as no backend or API integration were provided.
- No build tools or preprocessors were used, the project relies solely on HTML, CSS and the Bootstrap framework.
- Layout and grid responsiveness are designed for desktop, mobile and tablet screen sizes.
- Users are expected to view the site in modern browsers such as Safari, Chrome, Firefox, Microsoft Edge.

## Trade-offs
- Static vs dynamic content: using hardcoded data simplifies development and reduces page processing but limits scalability and dynamic updates.
- No JavaScript: the page is fully static and lightweight, but any dynamic features interactivity or advanced behaviours would require adding JavaScript.
- Basic CSS structure: using plain CSS is sufficient for this small project but would not be scalable for larger projects.

## How it would be implemented in modern Drupal
- Content Modelling: events can be developed as a custom content type with the fields title, date, short summary and link.
- Styling: CSS would be incorporated into the theme layer providing consistency across the website.
- Dynamic features: dynamic content would be rendered using the Drupal Views module, allowing for filtering, pagination, and sorting. Layout and styling of the event cards would be configured within Views.

## Credits
Author: Naomi Pham\
Web styling: Australian National University