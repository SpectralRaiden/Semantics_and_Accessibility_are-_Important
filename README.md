# The Signifigance of Refactoring Code

## **What is Refactoring**
<br/>

Refactoring is the process of restructuring code, while not changing its original functionality. The goal of refactoring is to improve internal code by making many small changes without altering the code's external behavior.

## **Refactoring in this Project**
<br/>

Semantic elements introduced in HTML5 not only help better structure your code, but also adds implicit meaning to the parts that make up your code. This was originally done with` <div>` tags with classes denoting the purpose i.e. `<div class="header">`. However `<div>` has no meaning of it's own.

<br/>

Not only that, but semantic elements also helps your browser meaningfully read your webpage and also aids in accessibility by making it easier for screenreaders to parse your code.

<br/>

Therefore we can make it clear what the purpose of each area of our document does by refactoring it. By replacing generic `<div>` tags with semantic ones we are doing just that. Such refactoring was done to this very document and the changes are as follows:

<br/>

-   `<div>` with `class="header"` replaced with `header` tags

-   `<div>` containing `<li>` tags replaced with `<nav>` tags
-   `<div>` with `class="content"` replaced with `<main>` tags
-  The  `<div>` tags  within  `<main> ` were replaced with `<article>` tags with attribute `id ` and `class` values retained
-   `<div>` with `class="benefits"` replaced with `<aside>` tags
-   `<div>` with `class="footer"` replaced with `<footer>` tags
-   an `alt` attribute was added to each `<img>`
tag with a short description of linked image
-   each **css** selector corresponding to refactored `<div>` tags were changed to reflect the semantic element it was replaced with. Values remain unchanged
-  `<footer>` element's `<h2>` was changed to `<h4>` to keep with **heading** rule of sequential order





