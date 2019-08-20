# Sass

Fonte: https://sass-lang.com/guide

Sass is a stylesheet language that’s compiled to CSS. 

It allows you to use variables, nested rules, mixins, functions, and more, all with a fully CSS-compatible syntax. 

Sass helps keep large stylesheets well-organized and makes it easy to share design within and across projects.

## Install 
https://sass-lang.com/install 

## Preprocessing
Sass, it will take your preprocessed Sass file and save it as a normal CSS file that you can use in your website.

```bash
sass <input.scss> [output.css]
```
```bash
sass [<input.css>:<output.css>] [<input/>:<output/>]...
```
```bash
sass input.scss output.css
```
```bash
sass --watch input.scss output.css
```
```bash
sass --watch app/sass:public/stylesheets
```
```bash
sass source/stylesheets/index.scss build/stylesheets/index.css
```

## Variables

### Sintaxe SCSS
```scss
$font-stack:    Helvetica, sans-serif;
$primary-color: #333;

body {
  font: 100% $font-stack;
  color: $primary-color;
}
```

### Sintaxe SASS
```sass
$font-stack:    Helvetica, sans-serif
$primary-color: #333

body
  font: 100% $font-stack
  color: $primary-color
```

