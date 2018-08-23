## Website Performance Optimization portfolio project

Access the website here: [here]( https://github.com/aselkg/web_site_optimization/)

## Getting Ready
* verify node is installed, can do `node -v` to check version, if doesn't error we are good.
* update npm to latest version `npm update -g npm`
* create a directory for you project and cd into it.
* once in your directory install grunt-cli `npm install -g grunt-cli`

### Install Required Apps for Image Minification
* Download and install [graphicsmagick](http://www.graphicsmagick.org/download.html)
* Download and install [ghostscript](https://www.ghostscript.com/download/gsdnld.html)
* Download and install [imagemagick](https://www.imagemagick.org/script/download.php) Make sure to check the option 'Install legacy utils'
* On windows. Install `gm` with `npm install -g gm`
* Restart system

## Clone the Repo
* Clone `git clone https://github.com/aselkg/website_optimization.git` 
* Run `npm install` to install all required packages from package.json file
* Run grunt to start minification by `grunt` if task is default or `grunt responsive_images`

## Used Resources 
* [CSS Minifier](https://cssminifier.com/) 
* [HTML Minifier](https://html-minifier.com/)
* [JavaScript Comressor](https://jscompress.com/)
* [Udacity Forums](https://discussions.udacity.com/)
* [Slack Overflow](https://stackoverflow.com/)


## Optimizations

### index.html 

* Added async attribute to the google analytics script
* Reduced image size with [Grunt](https://www.npmjs.com/package/grunt-responsive-images)
* Inlined css into html file
* Minified css with [CSS Minifier](https://cssminifier.com/) 
* Minified html [HTML Minifier](https://html-minifier.com/)
* Minified js [JavaScript Comressor](https://jscompress.com/)


### pizza.html

* `document.querySelector` was replaced by `document.getElementbyID` or `document.getElementsbyClassName`
* Reduced image size with [Grunt](https://www.npmjs.com/package/grunt-responsive-images)
* Minified css with [CSS Minifier](https://cssminifier.com/) 
* Minified html [HTML Minifier](https://html-minifier.com/)
* Minified js [JavaScript Comressor](https://jscompress.com/)