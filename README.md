# sketch-webfont
A npm based script to create web icon fonts from sketch 

##Requirements 
*[node](https://nodejs.org/en/)
*[sketchtool](https://developer.sketchapp.com/guides/sketchtool/)
> you'll need to add sketchtool to your $PATH `/Applications/Sketch.app/Contents/Resources/sketchtool/bin`
*[icon-font-generator](https://www.npmjs.com/package/icon-font-generator)

##Usage
* `npm install` - dependency resolving. Must do for first time.   
* `npm run build` - export icons from icons.sketch and create an iconfont with demo html.
* `npm run export` - export icons to assets/icons/ only
* `npm run create` - takes the svgs from assets/icons/*.svg and create iconfont with demo in dist directory (Will create if not available)

#License
MIT 
