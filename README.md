# Landing Page
A multi-section landing page, with a dynamically updating navigational menu based on the amount of content that is added to the page .
the starting project was provided by Udacity.
There're four behaviors we want to see in landing page

Navigation is built dynamically as an unordered list.
Adding active class to that section that at viewport.
When clicking an item from the navigation menu, the link should scroll to the appropriate section.
Responsive landing page.
Usage
you have a menu with menu items (collapse and numbers of sections).
if you clicked on anyone of the section items the web page will be scrolled to that particular section we you get there you're going to notice the bubbles that play around and an upButton to get back to header.
section if you decide to collapse the page the collapse button will remove every single section and the menu leaving you with header and Footer sections

# Development
createMenu that responsible for creating the menu dynamically based on the number of the sections .

scrollingUpdate that 'scroll' event listens to and it Adds class 'active' to section when near top of viewport to highlight the section.

we have added a click event to menu items to scroll to a particular section and the scroll event will highlight the section.

Responsiveness across all devices.

Adding new features
Adding an upButton that scrolls up to the header Section and got up-arrow icon from Font Awesome cdn.

Collapse button to remove all sections and the menu.

setTimeout() to indicate when scrolling has stopped .I didn't add any action ,but you're free to add any action you want like changing CSS style ,hide menu, etc.

add-content btn to add more sections and menu items.

menu icon for more responsiveness.
