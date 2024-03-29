# My-Portfolio

## Summary 

This is an updated version of my Portfolio.

https://ronmelendres.herokuapp.com/

## Site Picture

![alttext](public/images/portfolio-snapshot.png)

## Technologies Used

Express.js - Used to create the http server for this page.

Bootstrap - Bootstrap is used to create the basic layout of the page. The main aspects from Bootstrap used is the navbar and cards.

HTML- Used to create the basic structure of the page.

CSS- Adds scrolling behavior, background image, and some style to the sections and text of the page.

## Future Development

This version of my portfolio introduces some backend concepts using express in the server.js file. At the moment, my portfolio is designed to be one page, however as my knowledge grows, the portfolio may expand to have multiple pages. 

As this portfolio will always be evolving, another developement may be to try another responsive build like Bootstrap. 

## Code Snippet

The snippet shown is mainly the navbar portion that contains the links to the "About", "Portfolio", and "Contact" sections. However one small detail that I have not done before is in the hrefs, instead of a link going to another page, it directs to another id. By doing this, and adding in the css file "scroll behavior", when you click on of the three options, the page will automatically scroll down to the section. 

``` html

 <div class="collapse navbar-collapse justify-content-end" id="navbarSupportedContent">
                <ul class="nav">
                    <li class="nav-item">
                        <a class="nav-link" href="#about-me">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#portfolio">Portfolio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
            </div>