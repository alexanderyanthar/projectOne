# Juno College Cohort 49 - Project 1

## The objective: 

Convert a static multi-page PSD* using HTML and CSS into a well-tested, accessible, responsive and pixel-perfect website for desktop and mobile. Site must responsive all the way down to 320px, and mobile view should provide good user experience.  

*The design and assets were provided by Juno College. 

## Technical challenges: 
- SVGs not loading despite changing fill color. SOLVED by applying width to svgs. 
- SVG colors are off. Look over properties that need to be leveraged. 
- Box-shadow for nav not showing. SOLVED by applying position: relative to nav. Shadow was initally rendering beneath the hero div. 
- Box 7 in shop section disappears when resizing browser. 
- Updated border for product containers but cannot close space between image container and product info container in shop. 
- Footer logo not given in the right color. Is there a way to change the color of a png?
- Footer content not lining up perfectly at the bottom. 

## Technical wins: 
- Initial draft of desktop landing page completed in under 24hours.
- Leveraged mixins to keep SCSS short and sweet.  

## To improve:
- Refine details of overall landing page. 
- Create more consistency with font styling. 
- Look over mixins and look for new mixin and/or resuseable code opportunities. 
- Revisit SVGs. Make sure you can figure it out how to use them before using FA fonts. Using FA fonts would only be to keep the HTML code shorter. 
- Revisit bottom of footer alignment issue. 
- Time permitting, create a branch to see how you would go about the project the second time around. 

## To do:
- Create contact page, but finalize the landing page before proceeding.
- Media queries for multiple devices, all the way down to 320px. 
- Seperated SCSS into partials. 
- Experiment with animations and transitions in a seperate branch. 


