# Debugging Assignment Files

# Debugging Results
## HTML Errors and Warnings

Error 1:
Warning: This document appears to be written in English. Consider adding lang="en" (or variant) to the html start tag.

Fix 1:
<!--<html> -->
<html lang="en">


Error 2:
Error: Element meta is missing one or more of the following attributes: charset, content, http-equiv, itemprop, name, property.

Fix 2:
    <!-- <meta> -->
    <meta charset="UTF-8" />


Error 3: 
Info: Trailing slash on void elements has no effect and interacts badly with unquoted attribute values.

Fix 3:
    <!-- <meta name="viewport" content="width=device-width, initial-scale=1.0" /> -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0" > 


Error 4: 
Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.


Fix 4:
   <!-- <img src="easter-bunny-150-profile.png"> -->
   <img src="easter-bunny-150-profile.png" alt="Easter Bunny">

Error 5: 
Error: Element p not allowed as child of element h3 in this context. (Suppressing further errors from this subtree.)

Fix 5:
         <h3>Enough Content</h3>
         <p>You need enough content to thoroghly populate your page. The content should cause the page to be long enough to need to scroll. Keep copy/pasting content from Wikipedia until you have enough content to scroll. You will use this page later to embellish it with styles, color, formatting and layouts.</p>


Error 6:
Error: End tag article seen, but there were open elements.

Fix 6:
<article>
          <!-- <h3>Enough Content -->
            <h3>Enough Content</h3>

            <p>You need enough content to thoroghly populate your page. The content should cause the page to be long enough to need to scroll. Keep copy/pasting content from Wikipedia until you have enough content to scroll. You will use this page later to embellish it with styles, color, formatting and layouts.</p>
        </article>


Error 7:
Error: Unclosed element h3.

Fix 7:
<!-- <h3>Enough Content -->
   <h3>Enough Content</h3>



# Debugging Results
## CSS Errors and Warnings


Error 1:
Value Error : color #B2 is not a valid color 3 or 6 hexadecimals numbers : #B2

Fix 1:
/* color: #B2; */
   color: #B2D732;


Error 2:
Value Error : font-size Too many values or values are not recognized : 5 vw

Fix 2:
/* font-size: 5 vw; */
font-size: 5vw;


Error 3: 
Value Error : line-height Unknown dimension 1.35me

Fix 3:
/* line-height: 1.35me; */
	line-height: 1.35;


Error 4: 
Value Error : color #FE27122 is not a valid color 3 or 6 hexadecimals numbers : #FE27122

Fix 4:
/* color: #FE27122; */
	color: #FE2712;
  

Error 5: 
Value Error : text-decoration all is not a text-decoration value : all

Fix 5:
/* text-decoration: all; */
	text-decoration: underline;















Welcome to the Debugging Assignment repository! This repository contains the resources for the debugging assignment in the Web Design Tools course. Students will debug the provided HTML and CSS files to meet W3C standards and accessibility guidelines.

## Files Included

1. **index.html**
   - Contains intentional errors for students to identify and fix.
   - Errors include issues with HTML syntax, structure, accessibility, and semantic correctness.

2. **style.css**
   - Includes intentional errors related to CSS syntax, selectors, and properties.

3. **Expected Site Design**
   - Includes a screenshot of the error-free page (`images/expected-site-design.png`) to serve as a reference for students.

### File Structure
```
debugging-html-css/
├── css/
│   ├── style.css
│   ├── layout.css
├── images/
│   ├── easter-bunny-150-profile.png
│   ├── expected-site-design.png
├── index.html
├── README.md
```

## Objective

The goal of this assignment is to:
- Develop debugging skills by identifying and correcting errors in HTML and CSS.
- Improve familiarity with W3C standards and accessibility best practices.
- Practice using debugging tools and validators to ensure standards-compliant code.
- Learn to document errors and resolutions in a structured manner.

## Instructions

1. **Clone this repository** to your local machine:
   ```bash
   git clone <repository-url>
   ```

2. Open the `index.html` and `style.css` files in your favorite text editor or IDE (e.g., Visual Studio Code).

3. Identify the errors in both files. Use tools like:
   - [W3C HTML Validator](https://validator.w3.org/)
   - [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
   - [Wave Accessibility Checker](https://wave.webaim.org/)

4. Resolve all identified errors in the `index.html` and `style.css` files by:
   - Commenting out the original error code.
   - Adding the corrected code directly below the commented-out error code.

5. Once all errors are corrected:
   - Commit your changes and push them to your own GitHub repository.
   - Deploy the corrected project to GitHub Pages.

6. Submit your GitHub repository link and GitHub Pages link as instructed in the course.

## Tools and Resources

- [W3C HTML Validator](https://validator.w3.org/)
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
- [Wave Accessibility Checker](https://wave.webaim.org/)
- [MDN Web Docs](https://developer.mozilla.org/)

## License

This repository is for educational purposes only. All content is copyrighted by the course instructor and may not be distributed without permission.

---

Happy debugging!


