Exceptional Realty Group

test website for learn.co

#### CSS Syntax
```
@import url('https://fonts.googleapis.com/css?family=Roboto');

/* This is how you write comments */

/* CSS Syntax:

selector {
    property : value;
    property : value;
}
 */

 /* Type selector */
p { /* select all <p> */
    font-size: 1em; /* 16px, ?pt, 100%, 1em */
    line-height: 1.5em;
    font-family: 'Roboto', sans-serif;
}

figcaption {
    /*font-weight: normal;
    font-size: 0.75em;
    line-height: 1.5em;
    font-family: Georgia, "New Times Roman", sans-serif;*/
    font: normal 0.75em/1.5em "Roboto", "New Times Roman", sans-serif;
    color: #334433;
    text-align: right;
}

/* Class selector (applied to as many elements as you like) */

.shadow-text { /* select elements with class="shadow-text" */
    font: bold 2.6em "Roboto", sans-serif;
    color: white;
    text-shadow: 0 1px 1px #000;
}

/* id selector (apply to one unique element per page) */

#logo { /* select elements with id="logo" */

}

/* Descendent Selector */

#logo h1 { /* only style <h1> if inside id="logo" element */
    font-family: "Roboto", sans-serif;
    margin: 0;
}
```
