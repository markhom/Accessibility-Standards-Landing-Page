# Accessibility Standards Landing Page
Code Refactoring Challenge

## The Challenge
To refactor an existing webpage in order to make it accessible, so it is optimized for search engines.

The Acceptance Criteria for the webpage:
- Follows accessibility standards
- Applies semantic HTML elements
- Logical structure independent of styling and positioning
- Includes accessible alt attributes in images
- Heading attributes fall in sequential order
- Concise, descriptive title element

## What I did
To refactor the code and keep the webpage running, many elements were added or changed, such as:
- Added semantic HTML elements
- Combined or removed certian parts of CSS and styling
- Rename many elements of the HTML

## My modifications

```
<!-- Header -->
<!-- Main content -->
<!-- Additional content -->
<!-- Page footer -->

<header class = "header">

renamed divs such as the one above to something more logical

CHANGES TO CSS

.benefit-lead img,
.benefit-brand img,
.benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

#search-engine-optimization,
#online-reputation-management,
#social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

#search-engine-optimization img,
#online-reputation-management img,
#social-media-marketing img {
    max-height: 200px;
}
```
## The Application
This project was uploaded to GitHub via this repository: [https://github.com/markhom/Accessibility-Standards-Landing-Page](https://github.com/markhom/Accessibility-Standards-Landing-Page)

The refactored webpage: [https://markhom.github.io/Accessibility-Standards-Landing-Page/](https://markhom.github.io/Accessibility-Standards-Landing-Page/)