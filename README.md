# Challenge1
## Table of Contents (Optional)



* [Code Refactor Example](#code-refactor-example)
* [Usage](#usage)
* [Learning Points](#learning-points)
* [Author Info](#author-info)
* [License](#license)


## Code Refactor Example

What are the steps required to install your project? Provide a step-by-step description of how to get the development environment running.


```Changed non-semantic div element changing it to class of header to the index.html
`
<header class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
            <ul>
                <li><a href="#search-engine-optimization">Search Engine Optimization</a></li>
                <li><a href="#online-reputation-management">Online Reputation Management</a></li>
                <li><a href="#social-media-marketing">Social Media Marketing</a></li>
            </ul>
            </nav>
    </header>
```

"""added header and nav element - this allows to indicate the header of the index.html as well as changing div  element to nav - this allows links to navagate to sections of webpage """""
```
<header class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <!-- added nav element-->
        <nav>
            <ul>
                <li><a href="#search-engine-optimization">Search Engine Optimization</a></li>
                <li><a href="#online-reputation-management">Online Reputation Management</a></li>
                <li><a href="#social-media-marketing">Social Media Marketing</a></li>
            </ul>
            </nav>
    </header>
```
In this section added Section elements into index.html, also fixed class elements to match Style.css
```
<section class="hero"></section>
    <section class="content">
        <!-- changed class to id and added class-->
        <section id="search-engine-optimization" class="Horiseon-services">
            <img src="https://static.bc-edx.com/coding/full-stack/01-HTML-Git-CSS/assets/search-engine-optimization.jpg" alt="social-media-marketing" class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </section>
        <section id="online-reputation-management" class="Horiseon-services">
            <img src="https://static.bc-edx.com/coding/full-stack/01-HTML-Git-CSS/assets/online-reputation-management.jpg" alt="social-media-marketing" class="float-right" />
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </section>

In this section added Section elements into index.html, also fixed class elements to match Style.css
        <section id="social-media-marketing" class="Horiseon-services">
            <img src="https://static.bc-edx.com/coding/full-stack/01-HTML-Git-CSS/assets/social-media-marketing.jpg" alt="social-media-marketing" class="float-left" />
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
        </section>
        </section>

In this added aside element to identify section if webpage, Section elements into index.html, also fixed class elements to match Style.css
        <aside class="benefits">
        <section class="benefit-section">
            <h3>Lead Generation</h3>
            <img src="https://static.bc-edx.com/coding/full-stack/01-HTML-Git-CSS/assets/lead-generation.png" />
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </section>
        <section class="benefit-section">
            <h3>Brand Awareness</h3>
            <img src="https://static.bc-edx.com/coding/full-stack/01-HTML-Git-CSS/assets/brand-awareness.png" />
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </p>
        </section>
        <section class="benefit-section">
            <h3>Cost Management</h3>
            <img src="https://static.bc-edx.com/coding/full-stack/01-HTML-Git-CSS/assets/cost-management.png" />
            <p>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </p>
        </section>
    </aside>
    
</main>

added footer element
    <footer class="footer">
        <h2>Made with ❤️️ by Horiseon</h2>
        <p>
            &copy; 2024 Horiseon Social Solution Services, Inc.
            </p>
        </footer>

</body>

</html>

This change require some additional modification to the CSS selector: 

```css - updated Style.css to not have excess code
.benefit-section {
    margin-bottom: 32px;
    color: #ffffff;
    /*height: 150px;*/
}


.benefit-section h3 {
    margin-bottom: 10px;
    text-align: center;
}


.benefit-section img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.Horiseon-services {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.Horiseon-services img {
    max-height: 200px;
}
```

## Usage 

This Challenge had us identify where elements needed to be placed within index.html and also to content repeat code in Style.css



## Learning Points 


I learned how the nav element will link with ID elements in the webpage to take you to that portion of webpage. this is very useful tool to help navagate webpages easliy. 

I had also learned more about the aside element. The aside element is the portion of the webpage that will show ether left of right side of webpage




## Author Info

```Mason Ott

* [Github](https://github.com/MaceOtt/Challenge1)

The user has looked through your whole README, and gotten familiar with your application. 
This is where you take credit, and make it easy for them to learn more about you!
Direct them to the following:
- Your GitHub Profile
- Your LinkedIn
- Your Portfolio Website
- And Anything Else You Want!


## License
The last section of a good README is a license. This lets other developers know what they can and cannot do with your project. If you need help choosing a license, use [https://choosealicense.com/](https://choosealicense.com/)




