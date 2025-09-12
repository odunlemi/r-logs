# Round 1 Log

This is for the first 100 days of code. Start: Mon Sep. 8, 2025.

---

### R1D1 - Sep. 8, 2025
Block and inline elements. By default, block elements will appear on the page stacked atop each other, each new element starting on a new line. An example is the h1 - h6 tags and the paragraph tag, p.

Inline elements do not start on a new line. They appear in line with whatever elements they are placed beside. Examples being the anchor tag, a, and span, which is used to group text to be applied styles.

The middle ground is the *inline-block*, which formats an element to be inline but take the characteristics of a block level element.

More in the [resources](./resources.md) tab.

Completed an assignment, hosted [here](https://github.com/odunlemi/css-exercises/tree/main/foundations/block-and-inline), and rebuilt an earlier recipes website with new css skills - https://odunlemi.github.io/odin-recipes/

## R1D2 - Sep. 9, 2025
Flexbox provides a way to arrange items into rows or columns. These items will flex, grow, or shrink based on defined rules.

Flexbox is just not a single css property, it's a toolbox of properties to arrange things where you need them. Elements can either become a flex container or a flex item. An element becomes a flex container with its display set to flex like so `display: flex`, and a an element is a flex item when it is nested in a flex container. 

More in the [resources](./resources.md) tab.

Worked on: a flexbox example - https://codepen.io/odunlemi/pen/dPYLJPg

## R1D3 - Sep. 10, 2025
Floats were the sole option of laying out a complex webpage. However, floats were originally designed for magazing-style layouts, and the kinds of layouts you can achieve with floats are somewhat limited. Flexbox was created to break out of the limitations. Flexbox gives complete control over the alignment, direction, order, size of the elements (boxes) in our layout.

More materials on the [resources](./resources.md) tab especially [interneting is hard](https://internetingishard.netlify.app/html-and-css/flexbox/).

Worked on: an example demonstrating all the flexbox properties - https://codepen.io/odunlemi/pen/azvrvvd

## R1D4 - Sep. 11, 2025
`flex: [value]`. The flex declaration is actually a shorthand for 3 properties that you can set on a flex item. These properties affect how flex items size themselves within their container. In this case, `flex` is actually a shorthand for `flex-grow`, `flex-shrink` and `flex-basis`.

With a value of 1, as commonly used, `flex: 1` equates to: `flex-grow: 1`, `flex-shrink: 1`, `flex-basis: 0`.

When `auto` is defined as a flex keyword it is equivalent to the values of `flex-grow: 1`, `flex-shrink: 1` and `flex-basis: auto` or to `flex: 1 1 auto` using the flex shorthand. Note that `flex: auto` is not the default value when using the flex shorthand despite the name being “auto”.

More in the [resources](./resources.md#css-layouts) tab.

Worked on: my r-log webpage, making it responsive using flexbox and setting it up for long term use - https://odunlemi.github.io/r-logs/

## R1D5 - Sep. 12, 2025
Axes in flexbox. When an element is made a flex container, its items align across two axes - the main axis and the cross axis. `justify-content` aligns items across the main axis. To change the placement of items along the cross axis use `align-items`. The main axis and cross axis are based on the `flex-direction` of the container, if `row` which is the default, the main axis goes from left to right (horizonatal) and the cross axis goes from top to bottom (vertical). 

Flex direction set to `column` switches those axes and `justify-content` then aligns items vertically and, `align-items`, horizontally.

More in the [resources](./resources.md#css-layouts) tab.

Working on*: an interactive guide to flexbox and course assignments - [Josh w. comeau's guide](https://www.joshwcomeau.com/css/interactive-guide-to-flexbox/) & [Foundation css exercises](https://github.com/odunlemi/css-exercises/tree/main/foundations/flex)