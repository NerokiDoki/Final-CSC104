HTML:
This HTML file defines the structure of the "Tech Time and Learn" website:

Header Section:

Includes two logos (on both sides) and a site title ("Welcome to Tech Time and Learn!").
The logos and title are centered using inline styles (display: flex; justify-content: center; align-items: center;).
Navigation Bar:

Contains links to different pages: "Classes," "Learning Center," "Events & Room Bookings," "About," and "Contact Us." These links are wrapped in anchor (<a>) tags for navigation.
Main Content:

The content is divided into three sections (<div class="box">), each styled to display:
Latest News and Upcoming Events: A section that lists important dates such as the Learning Fair, classes start, and 3D printing week.
Room Bookings: Lists available rooms with their corresponding classes.
Upcoming Classes and Learning Fairs: Shows upcoming classes and events with dates.
These sections are wrapped in div tags with the class box, making them easy to style using CSS.

Footer Section:

Displays partner logos inside a div.
In the center, it shows the site logo.
Footer links (Site Map, Contact Us, About Us) are also included for further navigation.

CSS:
This CSS file defines the visual styling for the HTML elements:

Global Styles:

The body has the Arial font family, and margins/padding are reset to create a clean layout.
A light background color (#f4f4f4) is applied to the entire page for a soft look.
Header Section Styling:

The header has a dark background color (#333) with white text to contrast the site logo and title.
The header img rule sets the logo size to 250px by 100px with margins for spacing.
A flexbox layout (display: flex; justify-content: center; align-items: center;) is used to ensure the logo and title are properly aligned.
Navigation Styling:

The nav element centers the links and adds vertical spacing with margin: 20px 0.
Each <a> tag in the navigation has a margin for spacing between links and is styled to be bold with no text decoration (text-decoration: none), making them stand out.
Main Content Styling:

The .content class uses a flexbox layout (display: flex; justify-content: space-around) to distribute the three boxes evenly across the page.
The .box class styles the individual sections by giving them:
A white background (background-color: #fff), padding for spacing, and a light border (border: 1px solid #ddd).
Rounded corners (border-radius: 5px) and a subtle box shadow (box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1)) for a card-like effect.
Text within the boxes is centered to improve readability.
The .box h2 and .box p rules add spacing and ensure text is centered.
Footer Styling:

Similar to the header, the footer uses a dark background (#333) and white text.
The footer images (partner logos and site logo) are styled with the same size (250px by 100px) and margin spacing for a uniform appearance.
The .footer-links a styles the footer links, ensuring they are white, not underlined, and spaced evenly.
Together, the HTML provides the content structure, and the CSS controls the layout and design, ensuring that the page looks neat and is easy to navigate.
