# My-Blog
Html CSS JS

25 mins

28 mins - Adding Social Icons

    - Go to font awesome.com and download (Free for Web)
    - Extract
    - Copy the webfont folder to the root directory of the project
    - all.css file from the css folder
    - include the all.css in the index.html

33:45 - Adding font family (Note: i used the CDN version) found the problem no semi-colon

    - google fonts (fonts.google.com)
    - abel, anton, Josefin Sans, Lexend Deca, Livvic
    - Download
    - Extract and copy to the root directory
    - To use the fonts
        - create a fonts.css file in the css folder
        - create a font face rule
            - /* font-family: Abel */
                @font-face {
                font-family: Abel;
                src:url('../fonts/Abel/Abel-Regular.ttf')
                }
        - in the style.css
            - @import url('../css/fonts.css')

    - if CDN
        - <link href="https://fonts.googleapis.com/css?family=Abel|Anton|Josefin+Sans|Lexend+Deca|Livvic&display=swap" rel="stylesheet">

43:09 - Making a Variable example fonts

    <!-- to declare a variable -->
    root:{
      --Abel:'Abel',cursive;
    }

    <!-- to use the variable -->
    - font-family: var(--Abel);

45:00 - Colors

    - same as text declared in variable
    root:{
        --text-gray:#3f4954;
    }

    a {
        color: var(--text-gray);
    }

    - www.coolors.co
        - browse on color schemes
    
    - Gradient Color
        - www.webgradients.com
        - copy css

48:00 - Adjusting the styling of nav menu

50:00 - Social icons

51:12 - making navbar responsive

55:50 - adding a hamburger menu

1:00:06 - adding javascript
    
    