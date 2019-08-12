# SASS - The Complete SASS Course (CSS Preprocessor)

## Table of Contents
[01: Welcome](#01---welcome)  

## 01 - Welcome

### What is SASS?
SASS stands for **Syntactically Awesome Style Sheets**.

SASS is a CSS preprocessor with syntax advancements.

### Advantages of SASS

1. SASS helps you to **write CSS code in an easier and more efficient way**. You can write CSS code like the way you do in other programming languages because SASS gives you the capability to use variables, functions, conditional statements, etc. in CSS.
2. Apart from this, SASS helps you to **split your styles in different files**, thereby helping developers to write code in a more convenient manner.

### How does SASS work in browser?
The browser is not capable of understanding SASS code on its own. It needs a transpiler for that purpose. The transpiler converts a human-readable code into another human-readable code. On the other hand, a compiler converts a human-readable code into machine language. 

In this case, the transpiler converts the human-readable code (SASS) into another human-readable code (CSS). The latter is understood by the browser. 

### Syntaxes supported by SASS
SASS supports the following two syntaxes:

**1. Indented Syntax (commonly called SASS)**  
* Indented syntax does not use the curly braces. Instead it uses indentation. 
* Rather than using the semicolon to mark the end of each property, SASS writes every property on a new line. 
* This syntax has the file extension as `.sass`. 

    ```css
    ul 
        font-size: 20px
        margin: 5px

        li
            font-size: 14px
            color: red
    ```

**2. SCSS (Sassy CSS)**  
* It is quite similar to CSS and this is why, most developers prefer using it. SCSS is a superset of CSS with a few additions.
* Like CSS and unlike Indented Syntax, SCSS uses curly braces and semicolons.  
* Every valid CSS is valid SCSS.
* This syntax has the file extension as `.scss`.  

    We'll be using SCSS in throughout this course.


    ```scss
    ul {
        font-size: 20px;
        margin: 5px;

        li {
            font-size: 14px;
            color: red;
        }
    }
    ```

