# Protezione Civile di Settimo Milanese

## Overview
This repository contains the source code for the official website of the Protezione Civile di Settimo Milanese: [protezionecivile-settimomilanese.it](https://protezionecivile-settimomilanese.it).

The site is built with [Nuxt.js](https://nuxtjs.org/) (Vue.js framework) and uses [Vuetify.js](https://vuetifyjs.com/) for UI components and styling.

## Features
- Responsive design for desktop and mobile
- Volunteer and vehicle information
- Operations and alerts management
- Multilingual support (Italian, English)
- Modern UI with Vuetify

## Prerequisites
- [Node.js](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/)

## Getting Started

### 1. Clone the Project
```shell
$ git clone https://github.com/andreacw5/procivsm-site.git
$ cd procivsm-site
```

### 2. Install Dependencies
```shell
$ yarn
```

### 3. Run the Development Server
```shell
$ yarn dev
```
The site will be available at `http://localhost:3000` by default.

## Production Build & Deployment
After a pull request, Travis CI publishes the compiled static pages to GitHub Pages.

To build for production locally:
```shell
$ yarn build
$ yarn start
```

## Contributing
Contributions are welcome! Please open issues or submit pull requests for improvements or bug fixes.

## License
See [LICENSE.md](LICENSE.md) for details.

## Contact
For questions or support, contact the project maintainers via [info@protezionecivile-settimomilanese.it](mailto:info@protezionecivile-settimomilanese.it).
