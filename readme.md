# A website built from scratch

-HTML
-CSS
-Wireframnes
-git
-Markdown

## HTML

We started creating skeleton (! + Enter in VSCode), then we created the header, linked the CSS and the other two big containers, main and footer.

Header, contains a logo, a heading and a navagation.

```    <header>
        <div class="logo">
            <p>My Logo</p>
        </div>
        <h1>Personal Traning</h1>
        <na class="nav-items">
            <a href="">Training</a>
            <a href="">About us</a>
            <a href="">Contact</a>
        </na>

    </header>
    ```

## CSS

Defined promary and secondary colours, add them to the backgrounds and text colors.

Flex box for the header to align the three elements inside centered and vertically.
```header{ 
    background-color: #FCD0A1;
    display:  flex;
    flex-direction: column;
    align-items:  center;
}
```