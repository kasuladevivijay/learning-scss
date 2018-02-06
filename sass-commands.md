# sass commands

SASS help
- sass -h

Convert the SASS files to SCSS and vice versa
- sass-convert input.sass input.scss
- sass-convert input.scss input.sass

Compile into CSS
- sass input.scss:output.css

Watching the changes in the files
- sass --watch input.scss:output.css

Watching the changes in the directories
- sass --watch app/sass:public/css

Compressing styling in generated css files [ styles to choose: nested(default), compact, compressed, expanded(prettify) ]
- sass input.scss:output.css --style compact

Avoid generating the source-map files using the 'sourcemap' flag
- sass input.scss:output.css --style compact --sourcemap=none


