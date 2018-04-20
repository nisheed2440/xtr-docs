# Webpack

## Quadrant
ubiquitous

## Type
Tool

## Description
Webpack is a static module bundler for modern JavaScript applications. When webpack processes your application, it recursively builds a dependency graph that includes every module your application needs, then packages all of those modules into one or more bundles.

## Resources
https://webpack.js.org/

``` js
module.exports = {
    entry : './src/index.js',
    output : {
        path : __dirname,
        filename : 'bundle.js'
    },
     module: {
    rules: [
        { 
            test : /\.js$/,
            exclude : /node_modules/,
            use : 'babel-loader'
       }
    ]
  }
}
```

## Github
https://github.com/webpack/webpack/

### Platform
Web,Mobile