"Mieszkanix" Service Specification
Designed for searching and viewing listings of apartments, houses, rooms, and plots for sale and rent. It is adapted to various screen sizes and devices. The target group is users looking for or having properties to purchase/rent.

Website Structure (index.html)

<head>:
Meta tags (charset, viewport).
Title: "Mieszkanix".
Link to favicon.
Link to the CSS style sheet.
Links to Google Fonts.
<body>:
Header: Contains the logo and links to different sections of the site.
Search Engine: Enables filtering of offers based on property type, transaction type, location, price, and size.
Offer Sections:
Featured Offers: Selected offers.
For Sale: Offers for sale.
For Rent: Rental offers.
About Us: Information section about the company.
Footer: Contains a contact form, links to social media, and legal information.
Footer
Contact Form:

Enables users to contact the site administrator.
Contains fields for entering email address and message.
"Submit" button is used to send the form.
Social Media Links:

Redirects to the service's profiles on Instagram, Twitter, and Facebook.
Social media icons are clickable and open in a new tab, thanks to the target="_blank" attribute.
Legal Information and Additional Links:

"Mieszkanix by Jakub Bartosik" and copyright information.
Links to additional pages: "Page details" and "CMS".
JavaScript Scripts
Expanding Additional Images in "For Sale" and "For Rent" Sections:

Clicking the "View More" button in the "For Sale" section makes additional images visible, and the button disappears.
A similar functionality is implemented for the "For Rent" section.
Use addEventListener to listen for click events on buttons.
User Interactions

Search Buttons: Activate filtering of offers based on selected criteria.
"View More" Buttons: Expand the list of offers for sale and rent.
Header Links: Allow quick scrolling to selected sections of the page.
Contact Form: Allows users to send an email message.
SEO and Optimization

Use of semantic HTML tags.
Descriptive alt tags for images.
Inclusion of meta tags for better visibility in search engines.
Styling (style.css)

Global Styles: Settings for the entire document (margin, padding, box-sizing).
Structural Elements:
Header: Style and positioning.
Sections: Appearance, background color, size, and placement.
Responsiveness: Using media queries, the page adjusts to different screen sizes (e.g., column layout, text size).
CMS

Access to CMS is through a link in the footer of the homepage. By filling out the login form, we are directed to the statistics.html file located in the CMS folder.

The header has 4 tabs (posts, users, statistics, profile) that respectively take us to the next pages, as well as a "Logout" tab, which allows returning to the homepage.

Through the CMS, we can also edit selected users or posts; just click the "Edit" button in the corresponding table row.

Additional Remarks:
All pages use a style sheet defined in the "style.css" file.
Images used on the pages are free graphics created using DALL-E.
The pages contain information about the author in the details.html file, including the album number, year and subject of study, as well as the browser version under which the service was tested.






