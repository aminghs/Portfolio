# Simplefolio ⚡️ [![GitHub](https://img.shields.io/github/license/cobidev/simplefolio?color=blue)](https://github.com/cobidev/simplefolio/blob/master/LICENSE.md) ![GitHub stars](https://img.shields.io/github/stars/cobidev/simplefolio) ![GitHub forks](https://img.shields.io/github/forks/cobidev/simplefolio)

## A minimal portfolio template for Developers!

<h2 align="center">
  <img src="https://github.com/cobidev/gatsby-simplefolio/blob/master/examples/example.gif" alt="Simplefolio" width="600px" />
  <br>
</h2>

**_IMPORTANT NOTE_**: New fastest version came out, built with React + Gatsby! 🎉🎉🎉 See more: [Gatsby Simplefolio](https://github.com/cobidev/gatsby-simplefolio)

<h2 align="center">
  <img src="https://media.giphy.com/media/3oFzmq6Kj4yXZUVHmE/giphy.gif" alt="Look up!" width="600px" />
  <br>
</h2>

## Features

⚡️ Modern UI Design + Reveal Animations\
⚡️ One Page Layout\
⚡️ Styled with Bootstrap v4.3 + Custom SCSS\
⚡️ Fully Responsive\
⚡️ Valid HTML5 & CSS3\
⚡️ Optimized with Webpack\
⚡️ Well organized documentation

To view a demo example, **[click here](https://simplfolio.netlify.com/)**\
To view a live example, **[click here](https://cobidev.com/)**

---

## Getting Started 🚀

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites 📋

You'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [NPM](http://npmjs.com)) installed on your computer.

```
node@v10.16.0 or higher
npm@6.9.0 or higher
git@2.17.1 or higher
```

Also, you can use [Yarn](https://yarnpkg.com/) instead of NPM ☝️

```
yarn@v1.21.1 or higher
```

---

## How To Use 🔧

From your command line, first clone Simplefolio:

```bash
# Clone this repository
$ git clone https://github.com/cobidev/simplefolio

# Go into the repository
$ cd simplefolio

# Remove current origin repository
$ git remote remove origin
```

Then you can install the dependencies either using NPM or Yarn:

Using NPM:
```bash
# Install dependencies
$ npm install

# Start development server
$ npm start
```
Using Yarn:
```bash
# Install dependencies
$ yarn

# Start development server
$ yarn start
```

**NOTE**:
If your run into issues installing the dependencies with NPM, use this command:

```bash
# Install dependencies with all permissions
$ sudo npm install --unsafe-perm=true --allow-root
```

Once your server has started, go to this url `http://localhost:8080/` and you will see the website running on a Development Server:

<h2 align="center">
  <img src="https://github.com/cobidev/gatsby-simplefolio/blob/master/examples/example.png" alt="Simplefolio" width="100%">
</h2>

---

### STYLES

Change the color theme of the website ( choose 2 colors to create a gradient ):

Go to `src/styles/abstracts/_variables.scss` and only change the values on this classes `$main-color` and `$secondary-color` to your prefered HEX color

```scss
// Default values
$main-color: #02aab0;
$secondary-color: #00cdac;
```

**NOTE**: I highly recommend to checkout gradients variations on [UI Gradient](https://uigradients.com/#BrightVault)

---

## Deployment 📦

Once you have done with your setup. You need to put your website online!

I highly recommend to use [Netlify](https://netlify.com) to achieve this on the EASIEST WAY

Because this template use Webpack maybe you can get errors during deployment, Please watch my step-by-step video tutorial to successfully upload your Simplefolio Website on Netlify!

**[WATCH NOW MY STEP-BY-STEP TUTORIAL FOR DEPLOYMENT](https://www.youtube.com/watch?v=soaG3GNSxJY)**

## Others versions 👥

[Gatsby Simplefolio](https://github.com/cobidev/gatsby-simplefolio) by [Jacobo Martinez](https://github.com/cobidev)\
[Ember.js Simplefolio](https://github.com/sernadesigns/simplefolio-ember) by [Michael Serna](https://github.com/sernadesigns)

## Technologies used 🛠️

- [Webpack](https://webpack.js.org/concepts/) - Static module bundler
- [Bootstrap 4](https://getbootstrap.com/docs/4.3/getting-started/introduction/) - Front-end component library
- [Sass](https://sass-lang.com/documentation) - CSS extension language
- [ScrollReveal.js](https://scrollrevealjs.org/) - JavaScript library
- [Tilt.js](https://gijsroge.github.io/tilt.js/) - JavaScript tiny parallax library
- [Popper.js](https://popper.js.org/) - JavaScript popover library

## Authors

- **Jacobo Martinez** - [https://github.com/cobidev](https://github.com/cobidev)

## Status

[![Netlify Status](https://api.netlify.com/api/v1/badges/75600296-89eb-4640-9e7e-fa87fba7ce76/deploy-status)](https://app.netlify.com/sites/simplfolio/deploys)

## License 📄

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments 🎁

I was motivated to create this project because I wanted to contribute on something useful for the dev community, thanks to [ZTM Community](https://github.com/zero-to-mastery) and [Andrei](https://github.com/aneagoie)
