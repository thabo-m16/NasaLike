Adding external resources:
/* Adding links from the original website before using the font*/
<head>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;800&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="styles.css" />
    </head>
    
/* 1. Register the custom font */
@font-face {
  font-family: 'MyCustomFont';
  src: url('fonts/my-custom-font.woff2') format('woff2'),
       url('fonts/my-custom-font.woff') format('woff');
  font-weight: normal;
  font-style: normal;
  font-display: swap;
}

/* 2. Apply it to elements */
body {
  font-family: 'MyCustomFont', Arial, sans-serif;
}

Difference between id and class:
The primary difference is that an id uniquely identifies a single element on a page, while a class can be reused across multiple elements.

Instead of using div to group elements use <span>:
The <span> tag in HTML is a generic, inline container used to group and mark up a specific part of a text or document.

text-shadow: (horizontal) (vertical) (blur) (color)
Using background image: background: url();
