# fnx_coding_template
Gulp based frontend template. Thist template use scss, minify css, uglify js and sourcemaps.

### Precondition
You must install package manager npm. See[here](https://www.npmjs.com/).

### Install
    npm install

### Usage
Running server
    
    gulp devel
    
Releasing

    gulp release

### Basic structure of css
All is contacted to one css file css/style.min.css. If you want to use some external css, just import it to style.scss. (@import "path/to/file.css";)

### Basic structire of css
js/main.min.js - your scripts

js/third-party/third-party.min.js - put here some third-party scripts. Recomended is not minified versions.

js/provided/*.js - put here everythink you want. For example jquery. Dont forget add link into head tag.
    
    <script src="js/provided/jquery.min.js"></script>

### Ready to use icons
You can use icon fonts by uncomment it in style.scss.