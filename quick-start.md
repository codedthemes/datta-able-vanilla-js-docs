---
description: Quick Start using Gulp for Datta Able Installation
---

# 📐 Quick Start

### Installation <a href="#installation" id="installation"></a>

Navigate to your root folder **(i.e. `datta-able-vanilla-js`)**

```
c:>cd datta-able-vanilla-js
```

Install packages by npm or yarn according to your preferences. Here we are using the npm package manager.

```
> npm i
```

After package installation, you can start your app by using **`Gulp`** command. This will regenerate the dist folder. You can keep this command running while making changes in the `src` folder. It will auto-apply to the `dist` folder and your browser.

```
> gulp
```

{% hint style="info" %}
If you are interested more in learning about gulp, check the below section, else you can skip it.
{% endhint %}

<details>

<summary>Gulp</summary>

Gulp is a toolkit for automating painful or time-consuming tasks in your project development workflow, so you can stop messing around and build something easier than ever.

* Auto Minify/Uglify CSS, HTML, and JS codes
* Auto Compile SaSS file
* 3000+ Plugins

#### Gulp for Datta able

Use Gulp in Datta able for building different layouts and theme customization with lots of functional tasks like Image Optimization, SaSS compilation, etc...which useful to make the production-ready `dist/`directory

</details>



#### Gulp for Datta Able

Use Gulp in Datta Able is for building different layouts and theme customization with lots of functional tasks like Image Optimization, SaSS compilation, etc...which really useful to make the production-ready **`dist/`**&#x64;irectory

#### How to set up Gulp for Datta Able?

1. Make sure that you have already installed **Nodejs and Gulp** on your server/computer
2. Open the "Nodejs Command prompt" and redirect to your project root directory.
3. Enter the command `npm install` or  `yarn` in the command prompt.
4. After that, you need to run the below `gulp` tasks to build a production-ready dist/ directory.

### **Gulp Commands(task)**

#### Default task

<table><thead><tr><th width="226">Gulp Command</th><th>Description</th></tr></thead><tbody><tr><td><code>gulp</code></td><td>which build template in <code>/dist</code> directory</td></tr></tbody></table>

#### Basic task

<table><thead><tr><th width="224">Gulp Command</th><th>Description</th></tr></thead><tbody><tr><td><code>gulp sass</code></td><td>which compile .scss files from <code>/src/assets/scss</code> directory and place it into a <code>/dist/assets/css</code> directory</td></tr><tr><td><code>gulp imgmin</code></td><td>which use to optimize images from <code>/src/assets/images</code> directory and place it into a <code>/dist/assets/images</code> directory</td></tr><tr><td><code>gulp build</code></td><td>which use to copy files from <code>/src/assets</code> directory and place it into a <code>/dist/assets</code> directory</td></tr><tr><td><code>gulp build-html</code></td><td>which uses compiling your HTML file from <code>/src/html</code> directory and place it into a <code>/dist</code> directory</td></tr><tr><td><code>gulp build-js</code></td><td>which use to build <code>.js</code> files from <code>/src/assets/js</code> directory and place it into a <code>/dist/assets/js</code> directory</td></tr><tr><td><code>gulp watch</code></td><td>It will automatically start your build process if you make any changes in HTML, scss or js files from <code>/src</code> directory and put new changes to <code>/dist</code> directory</td></tr><tr><td><code>gulp watch-minify</code></td><td>It will automatically start your build process if you make any changes in HTML, scss or js files from <code>/src</code> directory and put new changes to <code>/dist</code> directory with <strong>minify assets</strong></td></tr></tbody></table>

\
