# Accessibility Audit and Fixes - m5-hw5-johnston-summer

## Tools Used
    - Chrome Lighthouse
    - WAVE
    - Mac Voiceover

### Issues Found and Fixed

    1. Low contrast in the title
        - added dark filter to the background (linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5))) 

    2. Low contrast in the nav and footer
        - fixed color: #555 to #cecece to make it more readable 

    3. Low contrast in the (h3) and contact form 
        - fixed color: #999 to #4f2f44 

    4. Header is not in descending order - goes from h1 to h3
        - changed h3 to h2

    5. Lacking HTML5 landmark
        - included a <main> tag enclosing the body copy

    6. No HTML labels for the form placeholder text
        - added labels and ids for the form-section 
