# Week 1 Challenge - 01 HTML, CSS, and Git: Code Refactor

## Setup
1. Cloned Challenge from GitLab
2. Initialised a Local Repository
3. Created a Remote Repository on GitHub

## Environment
1. MacOSX Monterey
2. git version 2.37.1 (Apple Git-137.1)
3. VSCode Version: 1.78.2 (Universal)

## Analysis:

1. Review Web Page
2. Review HTML Code
3. Review CSS
4. Noted Structure:
    1. Header
    2. Hero
    3. Contents
    4. Benerfits
    5. Footer
5. Notes
    1. Page Title was just a PlaceHolder
    2. Hero, Content and Benfits sections were divs, not sections
    3. All Headings (h1, h2 & h3) were qualified. Multiple classes use to style h2 & h3 elements in content and benefits section
    4. 3 identical classes used for benefits - replaced with single class
    5. 3 identical classes used for benefits imgs - replaced with single class
    6. 3 identical classes used for content - replaced with single class
    7. 3 identical classes used for content imgs - replaced with single class
    8. 1st div in body with class header should be a header element not a div & css can be applied to the element
    9. div enclosing ul menu structure should be nav
    10. nav is unique so doesn't need to be qualified in css
    11. the benefits section should be an aside
    12. divs in content section should really be articles - stand alone ideas
    13. SEO Optimisation in nav bar not moving to SEO Optimisation artcle because id missing in article
    14. Thought about wrapping h2s in articles in header tags but didn't make sense because of article structure
    15. Added alt attributes to images in case img doesn't load
    16. Wrapped img elements in figure element
    17. Added comments to CSS - should these be removed before deploying in production?
    18. Folder called Assets, code refers to assets
    19. Folder rename was introduced by me - corrected & code updated

## Changes Made:

1. HTML PlaceHolder Title - Replace with meaningful Title
2. H2 in Footer - Assign Class to reduce specificity
3. Change Hero, Contents and Benfits Divs into Sections
4. Assign a single Class for H2s in Content Section - 1 Class to maintain and reduces specificity
5. Assign a single Class for H3s in Benefits Section - 1 Class to maintain and reduces specificity
6. Assign a Class for H1 in Header - 1 Class to maintain and removes qualified heading
7. Removed qulification for seo class - soe class appears once only so not needed
8. Assign a single class for benefits divs replacing the 3 identical classes
9. Assign a single class for bennefits img tags replacing the 3 identical classes
10. Assign a single class for content divs replacing the 3 identical classes
11. Assign a single class for content img tags replacing the 3 identical classes 
12. Moved content class and content img class code to the content section to correct order
13. Changed ist div in body to header & changed css to refer to header element
14. changed div enclosing menu ul in header to nav & updated css
15. there is only 1 nav in the html so removed header qualification to reduce specificity
16. changed benefits section to an aside and updated css
17. corrected error in html - removed space in class for h2 headings in section
18. changed divs in content section to articles
19. added id="search-engine-optimization" to seo optimisation article
20. added alt attributes to images
21. wrapped img elements in figure elements
22. added comments to CSS
23. changed css link code from ./assets/css/styles.css to /Assets/css/styles.css
23. changed css link code from /Assets/css/styles.css to ./assets/css/styles.css


## Resources Used

1. Lesson Material for Week 1
2. GIT Cheat Sheet - https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet
3. W3 Schools Website Smenatic Elements - https://www.w3schools.com/html/html5_semantic_elements.asp
4. Prior knowledge (even if a bit rusty)

