<div align="center" id="top"> 
  <img src="./.github/app.gif" alt="PacmenFactory" />

  &#xa0;

  <!-- <a href="https://pacmenfactory.netlify.app">Demo</a> -->
</div>

<h1 align="center">PacmenFactory</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/Alvgonz/pacmenfactory?color=56BEB8">

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/Alvgonz/pacmenfactory?color=56BEB8">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/Alvgonz/pacmenfactory?color=56BEB8">

  <img alt="License" src="https://img.shields.io/github/license/Alvgonz/pacmenfactory?color=56BEB8">

  <!-- <img alt="Github issues" src="https://img.shields.io/github/issues/Alvgonz/pacmenfactory?color=56BEB8" /> -->

  <!-- <img alt="Github forks" src="https://img.shields.io/github/forks/Alvgonz/pacmenfactory?color=56BEB8" /> -->

  <!-- <img alt="Github stars" src="https://img.shields.io/github/stars/Alvgonz/pacmenfactory?color=56BEB8" /> -->
</p>

<!-- Status -->

<!-- <h4 align="center"> 
	🚧  PacmenFactory 🚀 Under construction...  🚧
</h4> 

<hr> -->

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/Alvgonz" target="_blank">Author</a>
</p>

<br>

## :dart: About ##

This web application has two buttons. with the first you can add pacmans randomly on the screen. the second button starts movement to pacmen and they move with random velocity and direction for each one.

This projects was made to test DOM manipulation using Javascript, using the document.getElementById method. An empty array of Pacmen is defined in the begining and there is a function to create a pacman that stablish the image from the folder, initial position and initial velocity, then this object is pushed as a div in the empty array. For the movement a function use setTimeOut to update position based in the position and veolocity established when the pacman was created. 

## :rocket: Technologies ##

The following tools were used in this project:

- [HTML](https://developer.mozilla.org/es/docs/Web/HTML)
- [CSS](https://developer.mozilla.org/es/docs/Web/CSS)
- [JavaSript](https://developer.mozilla.org/es/docs/Web/JavaScript)


## :white_check_mark: Requirements ##

Before starting :checkered_flag:, you need to have [Git](https://git-scm.com) and [Node](https://nodejs.org/en/) installed.

## :checkered_flag: How to run ##

for running this project you can click the button code and then open with Github Desktop. Then you can open the index.html inside pacmen folder in your github folder in your local disk.

if you don't have github desktop you can clone and run this project following the next steps.

```bash
# Clone this project
$ git clone https://github.com/Alvgonz/pacmenfactory

# Access
$ cd pacmenfactory

# Install dependencies
$ yarn

# Run the project
$ yarn start

# The server will initialize in the <http://localhost:3000>
```

## :sparkles: Roadmap of future improvements ##

:heavy_check_mark: I plan to include inclination of pacman image changing with the relations between the valocity in y and x;\
:heavy_check_mark: I plan to change pacman image to animate it to change between open mouth and close mouth en each position change;\
:heavy_check_mark: I plan to put a label that you can use to change the image for a different character. I tcan be ghosts of different colors;

## :memo: License ##

This project is under license from MIT. For more details, see the [LICENSE](LICENSE.md) file.


Made with :heart: by <a href="https://github.com/Alvgonz" target="_blank">Alvaro Gonzalez</a>

&#xa0;

<a href="#top">Back to top</a>
