# Basic Tailwind CSS project, extended with ATX .js



ATX.js is a JavaScript library for building applications with a consistent design and code structure.
it makes maintaining static html pages simpler and more efficient.

At the moment, ATX.js is a work in progress.


## How to use
```
yarn # install dependencies
yarn dev # builds css
yarn build # compiles components with ATX.js, purges, autoprefix and minify css
```
## How does ATX.js work?

You will need a folder called `src` and inside of it you will need a folder called `components` and another folder called Pages.
like this:
```
    src/
        components/
        pages/
```

You will need to put y your components in the `components` folder and your pages in the `pages` folder.
like this:

```
    src/
       components/
          navbar.component.html
          hero.component.js
       pages/
          index.template.html
```
Note: the .template.html and .component.html extensions are not required, but anything after the first dot is ignored.


## FAQ

**Is the name ATX final?**
No, probably it's not. I'm working on a new name.

**Do I need to use Alpine.js?**
No, you don't need to use it. It's imported via CDN on index.template.html.

**Do I need to use Tailwind CSS?**
No, you don't need to use Tailwind CSS. this template is configured to work with it, but I'm currently working on the standalone ATX package.

**When will ATX.js be released?**
Depends on how many people likes it.



## Contributing
Feel free to contribute! I'm open to any suggestions.

---

### Thanks to
Tailwind compiling features are based on [estevanmaito's tailwindcss boilerplate](https://github.com/estevanmaito/tailwindcss-boilerplate)

---