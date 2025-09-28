# alx_html_css
# CSS basics

# Project Overview
This project demostrates how to use CSS for styling, how to use flexbox for layout and how create responsive webpage.
Completing this project I have learnt how to do the following:
- Apply display: flex and flex-direction to container elements.
- Control the width allocation of child elements using the flex property.
- Make sections scrollable using overflow-y: auto.
- Ensure a responsive design for different screen sizes, including smartphones.

# Requirement
- Basic knowledge of HTML and CSS.
- A modern web browser that supports CSS Flexbox.
- The provided base CSS file to understand style rules.
- Optional: Unicode characters for a simple logo in the header.

# Implementation

Flexbox Containers:
    - Apply display: flex to <body> and <main>.
    - <body> uses flex-direction: column for header, main, and footer.
    - <main> uses flex-direction: row for article and aside.

Child Element Sizing
    - <article> takes 2/3 of the width using flex: 2.
    - <aside> takes 1/3 of the width using flex: 1.
    - <main> uses flex: auto for automatic sizing.

Scrolling
- Add overflow-y: auto to <article> and <aside> so content can scroll if necessary.
- Responsive Design
- Add class="works_on_smartphone" to <body> for smartphone layout.
 -Add the viewport meta tag in <head>:
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

Additional Styling (Optional)
- Customize colors, backgrounds, borders, and content inside <article>.
- Add a logo using a Unicode character with the logo class.

# Restrictions:
Do not change the Flexbox layout strategy outside <article>.
Avoid repositioning <header>, <main>, <aside>, or <footer>.