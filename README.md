<div align="center">
<img height="150" alt="preview" src="./public/logo.png" />
</div>

<h1 align="center">React Awesome Shapes</h1>

<h3 align="center">🌀 Insert Awesome Shapes into Your React Site with Ease.</h3>

<p align="center">
  <a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fashutosh1919%2Freact-awesome-shapes&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false"/></a>
  <a href="https://nodejs.org/en/blog/release/v16.14.0/"><img alt="NodeJS" src="https://img.shields.io/badge/node-16.14.0-important?style=flat-square" /></a>
  <a href="https://www.npmjs.com/package/npm/v/8.3.1"><img alt="NPM" src="https://img.shields.io/badge/npm-8.3.1-61DAFB?style=flat-square" /></a>
  <a href="https://github.com/prettier/prettier"><img alt="code style: prettier" src="https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square?style=flat-square" /></a>
  <br/>
  <a href="https://app.netlify.com/sites/awesomeshapes/deploys"><img alt="Netlify Status" src="https://api.netlify.com/api/v1/badges/eb7f832f-44d6-4460-af97-fab64038b91c/deploy-status" /></a>
  <a href="https://github.com/ashutosh1919/react-awesome-shapes/blob/main/LICENSE"><img alt="License" src="http://img.shields.io/:license-mit-blue.svg?style=flat-square?style=flat-square" /></a>
  <a href="https://github.com/ashutosh1919/react-awesome-shapes/commits/main"><img alt="Maintenance" src="https://img.shields.io/badge/maintained-yes-green.svg?style=flat-square" /></a>
  <a href="https://awesomeshapes.netlify.app/"><img alt="Website" src="https://img.shields.io/badge/website-up-yellow?style=flat-square" /></a>
  <a href="https://img.shields.io/badge/price-free-ff69b4"><img alt="Price" src="https://img.shields.io/badge/price-free-ff69b4?style=flat-square" /></a>
</p>



<p align="center"> 
    <a href="https://awesomeshapes.netlify.app/" target="_blank">
    <img src="./public/preview.png"></img>
  </a>
</p>
:star: Star us on GitHub — it helps!

# Getting Started 🎬

The easiest way to use one of the shapes from **Awesome Shapes** is to install the NPM package and import the particular shape to use it.

## Install NPM Package

```bash
npm install react-awesome-shapes
```

## Import And Use

```jsx highlight={1,6}
import { ShapeName } from "react-awesome-shapes";
...
function ShapeComponent(props) {
    return (
        ...
        <ShapeName {...passParametersToCustomise} />
        ...
    );
}

export default ShapeComponent;
```

The shapes are very easier to import and use wherever you want and in any web framework that uses NPM.  
You can set different sizes of different variety of shapes by passing props.

Read the complete in detail documentation in the [Usage section](#).

## Usage

Currently, the package contains shapes: [Circle](#), [Donut](#), [CircleGrid](#), [Diamond](#), [PolygonCard](#), [Polygon](#), [Star](#), [Cross](#), [Heart](#), [SquareDonut](#), [Arrow](#), [Message](#).

All of the shapes currently present in the package are made responsive and the responsiveness is customisable too. To do that, one of the prop to each shape component is `breakpoints` which is an array of numbers. It represents the breakpoints in which you will define the responsiveness. By default, `breakpoints` are defined as `[600, 900, 1200]`. So, you can pass array of 4 elements for `size` prop which corresponds to `<=600`, `600<size<=900`, `900<size<=1200`, `>1200`. Similarly, you can pass other props in form of array if you want to define different sizes for different breakpoints. You can see list of props corresponding to each shape in the respective implementation file linked above with shape.

By default, all the shapes have `position: absolute;` so that you can define the coordinates to put the shapes to exact position. But you can change the `position` attribute in case you want.

Basic usage of the Shape in your react site is illustrated on the [project website](#).

# License 📄

This project is licensed under the MIT License - see the [LICENSE.md](#) file for details.
You can use this project for personal as well as commercial purposes. But if you think you have modified the project and built something really good, we will humbly request you to raise the pull request and share with the opensource community.

# Contributing 💡

‌Awesome Shapes is created with the help of what is available for free on the internet and hence it will always be available for free. This makes it an open source project and everyone are welcome to contribute to different aspects of the project.

You may want to contribute on adding new shapes, fixing bugs, improving/refactoring code etc.




# References 👏🏻

[Gatsby Themes](https://themes.lekoarts.de/) by [@LekoArts](https://github.com/LekoArts) was the biggest inspiration for this project.
