# Personal Web Site Template

This is a personal website template, showcasing projects, providing information, and allowing visitors to contact.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Project Structure](#project-structure)

## Features

- Responsive design
- Showcases personal projects with descriptions and technologies used
- Provides information about Anil Bora
- Contact form for visitors to reach out
- Social media links

## Technologies

- HTML
- CSS
- JavaScript
- Font Awesome
- Google Fonts

## Project Structure

```
├── CSS/
│ ├── global.css
│ ├── main.css
│ ├── reset.css
│ └── responsive.css
├── images/
│ ├── AnilBora.jpeg
│ ├── project-1.png
│ ├── project-2.png
│ └── project-3.png
└── index.html
```


## CSS Files
- ``reset.css``: Resets default styling.
- ``global.css``: Contains global styles like background colors and text styles.
- ``main.css``: Main stylesheet with detailed styling for different sections.
- ``responsive.css``: Styles for different screen sizes to ensure responsiveness.

## JavaScript
- Included in the index.html file to handle the navigation menu toggle:

```html
<script src="https://code.jquery.com/jquery-3.7.1.min.js" integrity="sha256-/JqT3SQfawRcv/BIHPThkBvs0OEvtFFmqPF/lYI/Cxo=" crossorigin="anonymous"></script>
<script>
    $(".nav-icon").click(function(){
        $("#nav-links").toggleClass("nav-menu");
        return false;
    });
</script>
```


