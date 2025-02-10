Seen the types of selectors
1. Element selector
2. Class Selector
3. Id Selector
----------------------------------------------------------
Specificity:
Id Selector > class Selector > Element Selector
----------------------------------------------------------
Note:
1. It will indicate h1 or h2
    h1, h2 {
        color: blue;
    }

2. It will indicate h2 inside h1 i.e, nested
    h1 h2 {
        color: blue;
    }
----------------------------------------------------------
we will use * to apply for global css, note: there is global reset option, need to check
* {
    font-family: sans-serif;
}

----------------------------------------------------------
Note: CSS follow waterfall i.e, it wll take the last definition i.e, specificity order will change.
---------------------------------------------------------
Inheritance, means parent properties will be inherited to child, i.e, only valid properties only.
ex: border will not be inherited from body to p, but it will inherit from * to all.

----------------------------------------------------------
we will use 
htm {
    font-size=22px;
}

for global selector, 

also, there is semantic selector
main {
    font-family:monospace;
}

here, main only applicable for body elements and appears only one time.
----------------------------------------------------------
Note: !important we can use it for prioritize this property value. means it overrides everything.
----------------------------------------------------------
ref: 
specificity calculator: https://specificity.keegan.st/
