==============================New Readme Section=========================================
HTML:
This HTML file defines the structure of the "Tech Time and Learn" website:

Header Section:
Description:
Includes two logos, one on each side of the site title "Site Map - Tech Time and Learn."
The logos and title are centered using inline Flexbox styles: display: flex; justify-content: center; align-items: center;. This ensures the content is centered both vertically and horizontally in the header.
HTML Elements:
<img> tags are used for the logos, and the alt attribute provides descriptions for accessibility.
The <h1> tag contains the site title, styled with white text.
Navigation Bar:
Description:

Contains links to different pages: "Home," "Classes," "Learning Center," "Events & Room Bookings," "About," and "Contact Us."
The navigation links are wrapped in <a> tags, which provide clickable text that directs the user to different pages of the website.
CSS Styling:
The links are styled with bold white text, no underline (text-decoration: none), and a border around each link for a button-like appearance.
On hover, the background color changes to light blue, with a stronger 3D effect applied through the box-shadow.
Main Content:
Description:
The content is divided into three main sections, each wrapped in a <div class="box">. Each box represents a different section:

Website Structure: This section provides links to various pages on the website, such as "Home," "Classes," "Learning Center," etc.
Upcoming Classes: Lists upcoming classes with clickable links to the detailed pages.
Upcoming Events: Highlights upcoming events with clickable links, such as the "Tech Time Annual Conference" and other tech-related gatherings.
Room Bookings: Provides available rooms with their respective booking dates.
CSS Styling:
The .box class styles each section with a light blue background, rounded corners, and a subtle shadow effect, creating a card-like appearance.
The hover effect on each box slightly lifts the box and intensifies the shadow, creating a 3D effect to engage users.
Footer Section:

Description:
Displays partner logos inside a <div> with the site logo centered.
Provides footer navigation links, such as "Site Map," "Contact Us," and "About Us."
HTML Elements:
<img> tags are used for displaying the partner logos and site logo.
Links in the footer (.footer-links a) are styled to appear in white, with no underline, and spaced evenly.

CSS:
This CSS file defines the visual styling for the HTML elements, ensuring the layout and design are both functional and aesthetically pleasing:

Global Styles:
Body Styling:
Font and Layout: The body uses Arial as the default font, and margins and padding are reset for a clean layout.
Background Color: A dark blue background (darkblue) is applied to the page for a modern, professional look.
Flexbox Layout: The layout uses Flexbox with flex-direction: column, which ensures the child elements are stacked vertically. The min-height: 100vh ensures the page takes up the full height of the screen, even when the content is minimal.

Header Section Styling:
Background and Text:
The header has a dark background (#333) with white text to contrast the logos and the title.
Logo Size: The logos are sized to 250px by 160px with margins to ensure proper spacing around them.
Flexbox Alignment: The header uses Flexbox (display: flex; justify-content: center; align-items: center;) to center the logos and title both horizontally and vertically.
Navigation Styling:

Layout:
The navigation links are centered and spaced evenly with a vertical margin between them.
Each navigation link is styled with a bold font, white color, and a black border with rounded corners, giving them a button-like appearance.
Hover Effects: When hovered over, the background changes to light blue and the box-shadow becomes stronger, enhancing the visual interaction.
Active State: Links change color to bright blue when actively clicked.
Main Content Styling:
Flexbox Layout: The .content class uses Flexbox (display: flex; justify-content: space-evenly) to evenly distribute the three boxes across the page.

Box Styling: Each .box:
Has a light blue background, padding for spacing, and rounded corners.
A light border (1px solid #ddd) and a subtle shadow give the box a card-like appearance.
Text inside the boxes is centered for readability.
On hover, the boxes are lifted slightly and have a stronger shadow effect, improving the 3D feel.
Footer Section Styling:
Background and Text:
Similar to the header, the footer uses a dark background (#333) and white text for contrast.
Logo and Image Size: Images in the footer (partner logos and site logo) are styled with consistent sizing (250px by 160px) and margin spacing.
Footer Links: Footer links are styled with white text and no underline. They are spaced evenly for a neat appearance.

Conclusion:
Together, the HTML and CSS structure provides the foundation for a clean, responsive, and visually appealing website. The HTML defines the layout and content sections, while the CSS handles the visual styling, creating an engaging user experience through Flexbox for layout control, hover effects, and 3D elements. The combination of these elements ensures that "Tech Time and Learn" offers easy navigation, clear content presentation, and an attractive design for users.

==============================OLD Readme Section=========================================
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