# Bootstrap-Portfolio
Recreation of my portfolio webpage using Bootstrap.
****
<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
<!-- Webpage icon -->
  <a href="https://github.com/icollier77/inessa-collier-portfolio">
    <img src="./assets/images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h1 align="center">Bootstrap Portfolio</h1>

  <p align="center"> This is recreation of my portfolio webpage using Bootstrap.</p>
    <!-- links to deployment -->
    <a href="https://icollier77.github.io/Bootstrap-Portfolio/">Bootstrap Portfolio</a>
    ·
    <a href="https://github.com/icollier77/Bootstrap-Portfolio">GitHub repo</a>
    ·
    <a href="https://icollier77.github.io/inessa-collier-portfolio/">Previous Webpage</a>
  <br>
  <br>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#mock-up">Mock-Up</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#wireframe">Wireframe</a></li>
        <li><a href="#colour-palette">Colour Palette</a></li>
          <ul>
            <li><a href="#main-colour-palette">Main colour palette</a></li>
            <li><a href="#accent-colours">Accent colours</a></li>
            <li><a href="#font-colourfont-colour">Font colour</a></li>
            <li><a href="#webpage-palette">Webpage palette</a></li>
          </ul>
        <li><a href="#images">Images</a></li>
          <ul>
            <li><a href="#photos">Photos</a></li>
            <li><a href="#icons">Icons</a></li>
          </ul>
      </ul>
    </li>
    <li><a href="#development">Development</a></li>
      <ul>
        <li><a href="#bootcamp-resources">Bootcamp Resources</a></li>
        <li><a href="#other-sources">Other Sources</a></li>
          <ul>
            <li><a href="#line-animation">Line Animation</a></li>
            <li><a href="#object-size-transformation">Object Size Transformation</a></li>
            <li><a href="#box-shadow">Box Shadow</a></li>
            <li><a href="#smooth-scrolling">Smooth Scrolling</a></li>
            <li><a href="#href-on-images">Href on Images</a></li>
          </ul>
      </ul>
    <li><a href="#project-takeaways">Project Takeaways</a></li>
    <li><a href="#deployed-project">Deployed Project</a></li>
      <ul>
        <li><a href="#deployed-application">Deployed Application</a></li>
        <li><a href="#links-to-deployed-project">Links to Deployed Project</a></li>
      </ul>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## `About The Project`
The goal of this project is re-create my portfolio webpage using [Bootstrap][bootstrap-url] as I continue to progress through the [Front-End Web Development Bootcamp][bootcamp-url].

<p>The webpage recreated with Bootstrap should have the following:</p>
<ol>
  <li>A navigation bar with links connected to different sections on the page.</li>
  <li>A hero section (a jumbotron that includes my name, picture, and any other relevant information).</li>
  <li>A work section that displays my projects in grid.</li>
  <li>A card is used for each work projects and includes project description and a link to the deployed application.</li>
  <li>A section listing all the skills that I expect to learn from this bootcamp.</li>
  <li>A section with information about me.</li>
  <li>A section with my contact information, where the title of the section is on the same line as the links.</li>
  <li>A footer section where all hyperlinks have a hover effect and buttons display a box shadow effect upon hover.</li>
  <li>The Bootstrap solution should minimize the use of media queries.</li>
</ol>
</p>

### `Previous portfolio webpage`
My previously deployed portfolio webpage looked like this:

![Previous portfolio][previous-gif]

You can see the previous portfolio webpage deployed [here]

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### `Built With`

I used the following technologies when building this portfolio page: 
* [HTML][html-url]
* [CSS][css-url]
* [Bootstrap][bootcamp-url]
* [JavaScript][js-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## `Getting Started`

<p>I did not create a new wireframe as this was about recreating an existing webpage. However, the layout slightly changed from the previous version as there was no requirement to make one card larger than the others. I leverage the flex layout in Bootstrap with rows and columns to arrange my project cards and make the layout responsive.</p>

However, in general, using [Figma][figma-url] is very beneficial when building a website is the service provides all information I would need to create and customize the layout: margins, padding, colours, fonts, etc, which I can copy directly as css code.

### `Colour Palette`

I simplified the colour palette for the new webpage. The main goal is to create a clean page that guides the viewer to the desired CTA: to contact me (and hopefully start a collaboration).

As a result, I selected the <b>following colours</b> for the website:
<ul>
  <li>Main background colour: #0D0221</li>
  <li>Secondary background colour: #6688B0</li>
  <li>Main font colour: white</li>
  <li>Hover link: #C419BE</li>
  <li>Highlight font colour: #2628DD</li>
</ul>

These colours are set as <i>global variables</i> in the css file.

### `Images`

#### `Photos`

I sourced free photos from [Unsplash][unsplash-url]. In addition to the images used on the previous webpage version, I used one more:

- [ ] [cover image for Project 6][project6-url]


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- The build process -->
## `Development`

The development using Bootstrap was much faster and more streamlined compared to the regular build. One of the biggest time savers was positioning of elements using margin and padding classes, as well as the flex layout using rows and columns. Thanks to this layout I spent significantly less time on the page responsiveness.


### `Web sources for some code`

However, in some cases I turned to the web to find instructions on how to achieve certain outcomes.

#### `Changing navbar colour on scrolling`

I was not sure how to make my navbar background turn dark when scrolling down the page. This [video][navbar-scroll-url] was very helpful.

#### `Aligning cards vertically`

Some of my project cards had longer description which caused the cards to have different heights. I found how to correct this [here][align-cards-url].

#### `Increase card size on hover`

Although I had done this in my previous webpage, I still had to refresh my memory on the [code][cards-hover-url] required to achieve this nice effect.

#### `Underline navigation links on hover`

Finally, I thought it would be nice to have underlining effect on hover for the navigation links. This [video][navigation-underline-url] was very helpful.


<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- TAKEAWAYS -->
## `Project Takeaways`

In general, Bootstrap prooved to be a valuable tool for creating website. I found that I could still customize my design to make it my own, but the in-built classes sped up the work significantly. The biggest challenge lies in learning the different classes and how to combine them to achieve the desired effect. For that, I found it very helpful to watch various YouTube tutorial and code along line by line.
<br>
<br>
I feel that I still need to master Figma and Font Awesome properly as well to really benefit from their features.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- Deployed project -->
## `Deployed project`

The project is now live.

### `Deployed application`

![Deployed page][deployed-gif]

### `Links to deployed project`

You can find the current portfolio webpage, its corresponding code, and the previous portfolio webpage here:

- [ ] [Inessa Collier portfolio][deployed-url]
- [ ] [Project repo][repo-url]
- [ ] [Previous portfolio webpage][previous-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
[bootstrap-url]: https://getbootstrap.com/

[html-url]: https://www.w3schools.com/html/
[css-url]: https://www.w3schools.com/css/default.asp
[js-url]: https://www.w3schools.com/js/default.asp

[deployed-url]: https://icollier77.github.io/Bootstrap-Portfolio/
[previous-url]: https://icollier77.github.io/inessa-collier-portfolio/#work 

[deployed-gif]: assets/images/bootstrap-portfolio.gif
[previous-gif]: assets/images/previous-portfolio.gif
[previous-url]: https://icollier77.github.io/inessa-collier-portfolio/ 

[repo-url]: https://github.com/icollier77/Bootstrap-Portfolio

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/inessacollier/



[bootcamp-url]: https://www.edx.org/boot-camps/coding/skills-bootcamp-in-front-end-web-development

[figma-url]: https://figma.com


[project6-url]: https://unsplash.com/photos/creativity-flowing-advertisement-SZgVZPbQ7RE


[navbar-scroll-url]: https://www.youtube.com/watch?v=z70GTU3p72I
[align-cards-url]: https://www.youtube.com/watch?v=wolSRMGJ-Ls
[cards-hover-url]: https://www.youtube.com/watch?v=KAHjf1Xj0SU
[align-row-url]: https://stackoverflow.com/questions/50740468/how-to-align-the-header-and-button-on-the-same-line-using-bootstrap-4
[navigation-underline-url]: https://www.youtube.com/watch?v=0uZ_ZnlEJ68

