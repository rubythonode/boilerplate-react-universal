# boilerplate-react-universal

**Version 1.0.0** - [Change log](CHANGELOG.md)

Boilerplate to start new projects using the react stack libraries.

## Motivation

We know that there are many boilerplates out there and of course that this is another one, but some of them don't tell us how they were built and how the things were configured under the hood or are messy.<br>
Couples of times we used to start new projects including many libraries and there are some of them that in occasions we forget their names or how we configured them in the past.<br>
The main idea is having this repository with all the necessary things to start a new project without having to remember all the libraries and how they were configured.

### What are the benefits?

- Focus on the things that really matter.
- A code generated in ES5 with babel of your project to avoid having problems during the deploy process.
- Hot Reloading
- dev-server in parallel running in a different process to avoid problems during the server restarting (only if the server is active)
- and more...

### Where can it be used?
It can be used for Server Side Rendering, also only client usage using the webpack-dev-server.<br>

**Note:** This boilerplate gives you the necessary libraries and a detailed README.md of each directory, so it will be easy to understand or to edit the config files to adapt it to your own needs.

**Feature list:**

- React.js
- React Router V4
- React-Hot-Loader-3
- CSS Modules
- Webpack
- WebpackDevServer
- Webpack Dll
- Webpack Bundle Analyzer
- Babel
- Favicons generator
- Templates engines flexibles
- Nodemon
- FS Scanner
- Code Splitting
- Universal Rendering
- Universal Requests
- Preprocesors (Stylus + nib, Sass, Less)
- Css
- PostCss
- FontIcons (ionicons + fontawesome)
- Fonts
- Images loader

### How to use it:

1. Install the dependencies:

``` bash
yarn install
```

2. Start the cli:
``` bash
npm start
```

![Image of the CLI interface](https://user-images.githubusercontent.com/2402579/31302866-8c728e94-aac2-11e7-9325-5e2f8cea86e1.png)
![dev](https://user-images.githubusercontent.com/2402579/31303526-444ba38a-aacc-11e7-8347-dd8ba2790083.png)
![prod](https://user-images.githubusercontent.com/2402579/31303527-444d9690-aacc-11e7-8cbf-1eab592c53d1.png)
<br>
**Easy, just follow the instruccions.**

**Note:** If you don't want the cli for production you can use the command "build" and it will compile your project, it will create a new directory in the cwd called "build" that directory will include the code ready for production.


### Example:

?

---

### Contributors

![Image of Mantainer](http://s.gravatar.com/avatar/c3d34f6dbeeef3c39942d0ecb1247228?s=80)<br/>
[Norman Carcamo](https://github.com/normancarcamo)<br/>
[NPM - modules](https://www.npmjs.com/~normanfx)<br/>

---

### License & Copyright

© Norman Carcamo, Software developer

Licensed under the [MIT License](LICENSE)
