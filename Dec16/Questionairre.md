# Questionnaire

1. What is doctype?

`<!doctype>` is the tag used to denote which version of xml or html you are using.

2. What are the different positions in CSS?

Absolute (removes from flow, position from top, left, bottom, and/or right), Relative (same as absolute except not removed from flow), Fixed (locks position on screen regardless of scrolling), and Static (default).

3. What does the float property do?

It removes an element from the normal flow and causes remaining content to flow around wherever it is positioned.

4. How do you change the direction of HTML text

The dir attribute is used to change the direction of text, with "rtl" making it right to left.

5. Explain how the new HTML5 features works:

Many of them are semantic tags, such a `<article>, <header>, <footer>, & <section>,` that act as `<div>` elements with more specific names based on common classes from html4.

6. What are `<label>` elements used for?

It is used to link the `<label>` to an `<input>` within a form.

7. When would you use a `<div>`, `<section>`, or `<article>` tag?

When wrapping content that all has a common purpose and/or formatting.

8. How can you apply CSS to only a part of the HTML document?

Create a div wrapper with an ID or class and then use descendent selectors in the CSS.

9. What are the new features introduced by CSS3?

border-radius:, expanded attribute selectors, border images, box `&` text shadows, gradients, opacity, transformations, & column properties.

10. What is responsive design?

Using media queries to automatically adjust a layout based on the size of the screen it is being viewed on. Insert the "media="(DIMENSION:Xpx)"" attribute into the link tag to denote when to apply a specific style sheet.

11. Explain the different CSS units of measurement.

px= pixels on the screen, %= percentage of related element, em= width of M.

12. What are the possible values for the display rule and what do they do?

none= does not display element, inline= displays inline with other elements, block= displays as a block, inline-block= displays as a block that is inline with other elements.

13. What is a class and an id?

An ID is a unique attribute that can be used as a selector with high specificity. A class is a non-unique attribute with a lower specificity than ID.

14. How do you target a direct child element?

p>a would target the first a element that is a child of p.

15. Can you target a single, specific element with a particular class?

Yes, you would use TAG.CLASS assuming no other tags of the same type have that class.

16. What is the difference between display:none and visibility:hidden?

Display:none will simply ignore the element when generating the page, as though it does not exist, while visibility:hidden will not display the element but will still reserve space for it in the page layout.

17. Does overflow: hidden create a new block formatting context?

Yes, otherwise it would create issues with floated blocks.

18. Is it possible to use percentages in border widths?

No.

19. Is it possible to use percentages in margins?

Yes, margin: TOP% RIGHT% BOTTOM% LEFT%.

20. How do you reset a CSS style?

Most use a reset.css sheet that removes the automatic html formatting and standardizes things so the developer has a reliable baseline for applying their own css styles to. They key is to create a set of declaration blocks that defaults everything to a single format so that you can easily create a standardized experience regardless of which browser is being used to view your website. This is desirable because some browsers displays things like headers and lists slightly different.

21. If you have a way of dividing an interface horizontally and vertically, could any layout be made?

Yes, though certain ways of dividing the interface will more easily create certain layouts.

22. What debug tools are available for CSS?

Developer Tools in many browsers can be used for debugging since you can simply refresh to see the effects of your code, as well as FireBug and Xyle Scope.

23. Explain how the box-model works.

A box consists of margin (space between elements), border (edge of element), padding (space between border and content), `&` content. CSS takes every element and creates a box to contain it.

24. Name a few pseudo-classes and what they are used for

:hover for when a user has the cursor over content, :active for when a user clicks on content, :visited for when a user has visited a web page, `&` :link for when they have not visited that web page.

25. Explain how CSS shorthand syntax works for padding/margin.

You use the padding/margin property then enter in TOP RIGHT BOTTOM LEFT in that order.

26. How can an inline style be overridden

Use the display property to determine a style other than inline, or use the inline tag as a selector to change how it formats the text.

27. Explain how to implement a carousel using CSS / CSS3

Create a div that is the size of a single image and place an inner div inside that which is large enough to contain all the images at the same time. Then place all of the images within inner div, allowing only one image to be displayed at a time, and create an animation that translates the inner div in the desired direction so that it reveals new images.

28. Is there a performance difference between the different selectors?

Yes, specificity is important and using ID/Class selectors wisely will prevent the system from hunting through the entire html document. For example, #gohere has a much smaller performance impact than "html body div p em."

29. Explain how CSS3 animations work.

You use keyframes to denote the frames of the animation, then use the animation properties to call upon them and determine other factors like overall time and if it should repeat.

30. Explain how transitions work

They are used to animate change to content that would normally be instantaneous. You specify the properties to be modified with transition-property, set a delay with transition-delay, and set a duration with transition-duration. Any changes made will undergo a the transition.

31. How would you create a menu in which each element takes the same portion of space from its container, and if you change its size, it still remains the same space for each one

You would use percentages for height and width to dictate the box size of each element to be equal and add up to 100%.

32. What cross browsers issues have you ran into and how did you deal with them?

I have run into very few cross browser issues, but being forced to use Chrome in the military would generate issues sometimes. Typically I would just switch to Firefox. For my own coding, I would simply use more universal formatting placed above newer formatting in the CSS document so that browsers that understand the newer CSS will override the older styles.

33. What is flexbox? Have you used it?

It allows you to re-order the contents using CSS. No.

34. What are media queries?

They allow you to query the screen size and browser type being used to view your website. Insert the "media="(DIMENSION:Xpx)"" attribute into the link tag to engage in a media query.

35. How is an HTML5 form implemented?

`<form action="URL">
  <input type="TYPE" name="NAME" />
  <label for="NAME">TEXT</label>
</form>`

36. What is the specificity?

It is the importance given to a style based on the type of selector used. Higher specificity will override lower specificity. When equal, the last style takes precedence.

37. How would you use sprites?

You create a div smaller than the whole image so that it only displays a portion of the image at a time, and then create conditions that move the image around in the div to display other parts. When the parts of the image are all similar but slightly different, it creates the illusion of altering the image.

38. How can you load CSS resources conditionally?

Media queries can be used to load CSS styles only when being viewed by certain screen widths, of you can use the browser conditional for IE versions.

39. When sending form data, what is the difference between the GET and POST methods?

Get attaches the input to the URL of the page defined by `<action>`, while post attaches it to the body of the page.
