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
5. Noted
    1. Page Title was just a PlaceHolder
    2. Hero, Content and Benfits sections were divs, not sections
    3. All Headings (h1, h2 & h3) were qualified. Multiple classes use to style h2 & h3 elements in content and benefits section
    4. 3 identical classes used for benefits - replaced with single class
    5. 3 identical classes used for benefits imgs - replaced with single class
    6. 3 identical classes used for content - replaced with single class
    7. 3 identical classes used for content imgs - replaced with single class
## Changes Made:

1. HTML PlaceHolder Title - Replace with meaningful Title
2. H2 in Footer - Assign Class and use in place of qualified heading
3. Change Hero, Contents and Benfits Divs into Sections
4. Assign a single Class for H2s in Content Section - 1 Class to maintain and removes qualified heading
5. Assign a single Class for H3s in Benefits Section - 1 Class to maintain and removes qualified heading
6. Assign a Class for H1 in Header - 1 Class to maintain and removes qualified heading
7. Removed qulification for seo class - soe class appears once only so not needed
8. Assign a single class for benefits divs replacing the 3 identical classes
9. Assign a single class for bennefits img tags replacing the 3 identical classes
10. Assign a single class for content divs replacing the 3 identical classes
11. Assign a single class for content img tags replacing the 3 identical classes 
