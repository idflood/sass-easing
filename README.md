Sass Easing Transitions
======================================

A simple sass file providing standard easing functions for css transitions.
It is based on [compass-ceaser-easing extension](https://github.com/jhardy/compass-ceaser-easing) but without the compass dependency. This make it compatible with [libsass](http://libsass.org/).

Example
======================================

    @import "sass-easing/stylesheets/sass-easing";
    .transition {
      transition: all 4.2s $easeInOutQuart;
    }

Notes
======================================

Since it doesn't rely on compass you will have to handle vendor prefixes with [autoprefixer](https://github.com/postcss/autoprefixer) for example.