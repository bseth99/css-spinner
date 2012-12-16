CSS3-only Animated Spinner
===========

Includes Sass/Compass partial to generate spinners with different options.

You can download the basic spinner CSS from the css directory (css-spinner.css).

Or you can check out the source and build the CSS files using Compass.  From the main directory, run:

    compass compile
    
This will regenerate the CSS files from the SCSS files.

Requires additional Gem [animation package](https://github.com/ericam/compass-animation) which includes the required animation/keyframe mixins:

    gem install animation --pre

The scss folder contains the partial _spinner.scss which contains the mixin to generate spinner classes.  

Check out the [demo page](http://bseth99.github.com/css-spinner/) for working examples.
