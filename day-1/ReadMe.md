Concepts

1. Types of HTML Tags
2. Types of CSS Inclusion
   a. inline
   b. internal
   c. external
3. Targetting DOM Elements (Traversing DOM)
    .container p              // Apply styles to all p tags inside .container class
    .container .content       // Apply styles to .content class inside .container class
    .container .content > p   // Apply styles to all first level p tags inside .container .content classes
    .container .content + p   // Apply styles to p tag which is adjucent to .content class
    .container.content        // Apply styles to tag that contains both .container & .content
4. Specificity
    a. element's specificity is 1
    b. class's specificity is 10
    c. id's specificity is 100
5. Types of selectors
   a. element
   b. class
   c. id
   d. pseudo
