### CSS Dimension Properties
- Width
- Height
- Min-height
- Min-width
- Max-height
    ```
    /* to handle overflow */
    overflow: scroll;
    ```
- Max-width
    ```
    /* to handle overflow */
    overflow: scroll;
    ```

#### Overflow Property
The overflow CSS shorthand property sets the desired behavior for an element's overflow, i.e., when an element's content is too big to fit in it's block formatting context, in both directions.
- Values
    - Visible
    - Hidden
    - Scroll
    - Auto

#### CSS Position Property
The position property specifies the type of positoning method used for an element (static, relative, fixed, absolute or sticky)
- Static (By Default no need to setup)
    - HTML elements are psotioned static by default. An element with position: static; is not postioned in any special way, it is always positioned according to the normal flow of the page. 
- Relative 
    - An element with position: relative; is positioned relative to it's normal position.
    - Setting the top, right, bottom, and left properties of a relatively-postioned element will cause it to be adjusted away from it's normal position. Other content will not be adjusted to fit into any gap left by the element.
- Fixed
    - An element with position: fixed; is postioned relative to the viewport
    - which means it always stays in the same place even if the page is scrolled. The top, right, bottom, and left properties are used to position the element.
- Absolute
    - An element with position: absolute; is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).
    - However, if an absolute positioned element has no positioned ancenstors, it uses the document body, and moves along with page scrolling
    - Absolute positioned elements are removed from the normal flow, and can ovrlap elements.
- Sticky
    - An element with position: stick; is positioned based on the user's scroll position.
    - A sticky element toggles between relative and fixed, depending on the scroll position. It is positioned relative until a given offset position is met in the viewport, then it "sticks" in place (like position: fixed)

#### Excercise 
***Position Text in all corners && center of an image*** 
