# Designers Guide for Design System
**If you are the designer of the design system then below are the areas you should take care of before sharing with the developers any design file.**

**1. Colors**

Which all colors your design system will have? Primary colors, Alert colors, secondary color etc. Make sure that these colors are passing the contrast ratio.


**2. Typescale**

What would be the typescale of the typography of your design system? There should be minimum font-size your design system should have. Decide on the Typescale - will there be fixed type sizes or user can have any.


**3. Spacing** 

what would be the spacing (padding and margin) guide your design system will have? For example, can user decide the space (margin) between the elements or there will be  some pre-decided space-numbers (classes) the user need to pick from? Same goes with padding. To have the consistency better to have the fixed space scale.


**4. Responsive**

It is very important to have responsive design system. __"Why?" I will ask - "Why not"?.__ This is mobile and tabs era. 
Every component in your design system should be responsive by default. As a designer decide the breakpoints your design system 
is going to support (your design audit will help you here). Once the breakpoints are decided. Start thinking about the 
behaviour of the components on the responsive state. Components behaviour can be handle component by component but few 
things you need to close intiatlly:

1. Will the font-size will change in responsive?
2. What will be the UX of the touch screen?
3. How the active, focus etc state will be on the touch screen?


**5. Progressive enhancement & Browsers**

This would be the collabration work of the UX, UI etc. To deciden the browsers and devices your design system is going to support.As a designer it is important for you to involve in this decision as devs will keep you updated the limitations of the browsers version.ex: a particular property will work on all browser or not? and as a designer you need to decide to keep such design or not. As well as, do we have prgressive enhancement or graceful degradation.


**6. Micro-interactions**

Micro-interactions are very important. This actually the part of the UX which engage the users. Sadly, this is the section which is also most ignorant too.Micro-interactions are basically the small animations, effects, UX very interaction of user with the component will have. As a designer Micro-interactions define the UX of interacting with any components. Such as on hover on a button what all property will change and how they will change, in design system on closing any open element - how it is going to close - with transition or fade etc.These micro-interactions should be global and consistent throught out your design system. Few interactions are:

- hover
- active
- select
- delete
- open 
- close
- scroll
- drag
- drop
- errors
- notifications


**7. UX Guide**

Lot of non-designer folks will be using your deisgn system and it is an opportunity for UX to advocate the non-ux folks about the UX guidelines. Give the UX guide with every component such as:

1. When to use this component?
2. Where to use this component?
3. What are the things needs to take care to have best UX for users.

Eg: When to use button and when to use anchor tag.


**8. Error stages**

Sadly there is no component on error stage. hence as designer you need to make sure you will define the style of the error or notification states such as error, alert, success etc. Again these needs to be define global and should be consisitent too.


**9. Design Kit for scalability**

To gain the trust of your users as well as to have the collabration. Open all your design kit for the users.


**10. Styleguide**

Styleguide is the summary of the Design system's UX decision. Always have a styleguide, this will help the users to look into the design system's UI and UX in one go.


**11. Design tokens**


**12. Decide Flexibility vs consistency**


**13. Themes**


**14. Styleguide**
