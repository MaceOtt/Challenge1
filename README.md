# Challenge1 

## Technology Used 

| Technology Used
| ------------- |:-------------:| 
 CSS
 HTML
 Git    |    

## Description 

[Visit the Deployed Site](https://github.com/MaceOtt/Challenge1/blob/main/index.html)

In this Challenge1 we added semantic elements to he index.html to better understand each element in the webpage


![Site Langing Page](./site.gif)


## Table of Contents (Optional)


* [Code Refactor Example]
* [Usage]
* [Learning Points]
* [Author Info]


## Code Refactor Example

Added we added semantic elements to he index.html to better understand each line of code



```html
<div class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </div>
    </div>
```

Converting the above non-semantic div with the class of 'header' to an appropriate [<header> semantic element](https://www.w3schools.com/html/html5_semantic_elements.asp). 

```html
<header>
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </nav>
    </header>

```

This change require some additional modification to the CSS selector: 

```css
.header {
    padding: 20px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    background-color: #2a607c;
    color: #ffffff;
}
```

No longer targeting the element on the page with the class of 'header' but instead the css selector targeting the 'header' element 

```css
header {
    padding: 20px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    background-color: #2a607c;
    color: #ffffff;
}

```

## Usage 

In this webpage you are able to use nav elements to learn more about each subject on the webpage
```


## Learning Points 

This Challenge helped identify where each semantic element needs to be placed to better understand the index.html


## Author Info
Mason Ott
```md
### Mason Ott

* [Github](https://github.com/MaceOtt/Challenge1)
```

## Credits



---

© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.




