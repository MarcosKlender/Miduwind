<a id="readme-top"></a>

<div align="center">

![Astro](https://astro.build/assets/press/astro-icon-light-gradient.svg)

[![Available at](https://img.shields.io/badge/Available%20at-Astro%20Themes-purple?style=for-the-badge&link=https://astro.build/themes/details/astrolinkhub/)](https://astro.build/themes/details/miduwind/)

</div>

<h1 align="center">Miduwind</h1>

<div align="center">

![Astro](https://img.shields.io/badge/Astro-0C1222?style=for-the-badge&logo=astro&logoColor=FDFDFE)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JSON](https://img.shields.io/badge/json-5E5C5C?style=for-the-badge&logo=json&logoColor=white)

Open source links page, customizable via JSON. Made with Astro 5 and Tailwind 4.

</div>

![AstroLinkHub Screenshot](/public/screenshot.webp)


## Table of Contents

  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li>
      <a href="#json">JSON</a>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
  </ol>


## About The Project

> [!IMPORTANT]
> I'm glad to announce that this project is available on [Astro Themes](https://astro.build/themes/details/miduwind/)! 🚀

After the amazing reception of [AstroLinkHub](https://astrolinkhub.netlify.app/) I've decided to bring you an improved, modern and fully customizable link page. Inspired by the work of the talented [Midudev](https://midu.dev/) and his [Tailwind 2025 course](https://www.youtube.com/watch?v=R5EXap3vNDA), I introduce you to [Miduwind](https://miduwind.netlify.app/):
- Using Astro (v5.7) and Tailwind (v4.1)
- Create your very own links page for FREE
- And most importantly, update it very easily using JSON

<p align="right"><a href="#readme-top">Back to top ⬆️</a></p>


## Getting Started

### Prerequisites

- **Node.js** -> `v18.17.1` or `v20.3.0` or higher. (`v19` is not supported)
- **Visual Studio Code** -> with the [Official Astro Extension](https://marketplace.visualstudio.com/items?itemName=astro-build.astro-vscode).

Personally I prefer using `pnpm` instead `npm` and to install it you can use:

  ```sh
  npm install -g pnpm
  ```

### Installation

1. Clone this repo to your computer:
   ```sh
   git clone git@github.com:MarcosKlender/Miduwind.git
   ```
2. Install Astro dependencies:
   ```sh
   cd Miduwind
   pnpm install
   ```
3. Run the Astro dev server:
   ```sh
   pnpm dev
   ```
   
<p align="right"><a href="#readme-top">Back to top ⬆️</a></p>


## JSON

The best part of Miduwind is that you can modify every aspect of the website very easily, you just have to edit the `data.json` file. This JSON contains the following sections:

- **html** -> Edit language, title, description, favicon (replace it in `/public`) and the page gradient background.
- **header** -> Edit your photo (replace it in `/public`) and your username.
- **about** -> Edit your name and a summary about you.
- **links** -> Highlight your links with a gradient background and a logo.
- **footer** -> Edit the copyright and URL of your choice (Made just for you 😎).


## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "feature".
**Don't forget to give the project a star!** ⭐

<p align="right"><a href="#readme-top">Back to top ⬆️</a></p>


## License

Distributed under the MIT License. `Open Source` is pretty self-descriptive.

<p align="right"><a href="#readme-top">Back to top ⬆️</a></p>
