# sass-preprocessing 
# SASS is a preprocessor which lets you use features that don't exist in CSS yet like variables, nesting, mixins, inheritance and other nifty goodies that make writing CSS fun again.

# It compiles the .sass or .scss to .css files

# Once Sass is installed, you can compile your Sass to CSS using the 'sass' command.

# Tell the compiler which file to compile and provide the output
- command: sass input.scss output.css

# Watch the files with the --watch flag
- command: sass --watch input.scss:output.css

# Watch and output to directories by using folder paths as your input and output, and separating them with a colon
- command: sass --watch app/sass:public/stylesheets

References:
1. https://sass-lang.com/guide



