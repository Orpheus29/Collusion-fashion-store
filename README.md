<h1 align="center">🔥Collusion🔥</h1>

<p align="center">
    <sup>Fashion clothing store landing page.</sup>
</p>

<p align="center">
  <a href="https://orpheus29.github.io/Collusion-fashion-store/">
    <strong>✨GO TO✨</strong>
  </a>
</p>


 <h2 align="center">📋About📋</h2>

Welcome to the vibrant world of Collusion promotional clothing store website, crafted using BEM component-based approach, state-of-the-art Nunjucks "templating weapon" and advanced SCSS styling capabilities. 🌟

If your screen width is less than 1000 px, on the top right corner you will see a 'burger' icon unveiling a pop-up navigation menu.

In the heart of the page six sections unfold, each presenting new fashion collections.

At the bottom of the page you will find contact details and an invitation to join the inner circle of trendsetters by subscribing with your email address.
Enjoy your shopping experience! 💃🛍️

<h2 align="center">🧙‍♂️Technologies used🧙‍♂️</h2>

 ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![NUNJUCKS](https://img.shields.io/badge/Nunjucks-1C4913?style=for-the-badge&logo=nunjucks&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white) ![WebPack](https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=Webpack&logoColor=white)

<h2 align="center">📌Instructions how to run application locally📌</h2>

To continue working on the website, *fork*, *clone* or *download* the repository.

#### Cloning or downloading
In order to clone this repository, run the command below; if you wish to download it, follow the *Code / Download ZIP* link.
```
git clone https://github.com/Orpheus29/Collusion-fashion-store.git
```

#### Forking
Forking makes a copy of this repository which is then available as your own repository in your profile. Click the *Fork* button or see help [here](https://help.github.com/en/articles/fork-a-repo).

#### Usage
This project uses [Yarn](https://yarnpkg.com/) as the package manager. Follow the instructions on the provided link if you haven't installed it before. When done, run `yarn install` to install all dependencies.

To continue working on the website, start the development server (live reload of changes), running `yarn dev` (or `yarn dev --open` to open the webpage automatically).

To build a production version of the updated site, run `yarn build`. The resulting site will be available in the `dist` directory.

#### HTML: Nunjucks
This website uses a powerful [**Nunjucks**](https://mozilla.github.io/nunjucks/) templating engine built by Mozilla. The syntax is similar to (and inspired by) Python's jinja2.
For more on templating using Nunjucks, read [**Nunjucks' documentation**](https://mozilla.github.io/nunjucks/templating.html).

If your page files have the `.njk` extension, webpack will automatically run them through Nunjucks. If you wish to use some templates via e.g. `{% extend "base.njk" %}`, you may add those templates into the `src/templates` directory and refer to them in your pages directly (meaning `base.njk`, not `../templates/base.njk`).
