# kpmp-common-styles
The [sass](https://sass-lang.com/) stylesheets used across the KPMP applications

## Installation

```
$ npm i kpmp-common-styles --save
$ npm i sass -g
```

## Usage

There are a couple ways to use this library:

1. Import the compiled index.css onto a react page
```
import "kpmp-common-styles/dist/index.css";
```

2. Import the uncompiled sass into another sass file to allow the application library to handle sass compilation
```
@import "../node_modules/kpmp-common-styles/common-values.scss";
```




## To modify

Make any changes inside of the .scss files and then convert the .scss to .css using the following command:

```
$ sass index.scss dist/index.css
```
