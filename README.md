# 2ui-sass

UI Tools, Sass

# Local Dev

To output `main.css`, and watch for changes

```
npm start
```

To generate Sassdocs, and open in a browser (no auto reload, and need to build after every change)

```
npm run sassdoc
```

# Usage

To use in your project

```
npm install --save @2ui/sass
```

## Include CSS in your Sass file

This will depend on your configuration, but something like this

```scss
@import "~@2ui/sass";
```

## Include Sass in your Sass file

If you want to use the functions in your Sass file

```scss
@import "~@2ui/sass/src/lib";
```

And you can override existing variables before importing, because variables are declared using [Sass `!default`](https://sass-lang.com/documentation/variables#default-values)
