Pure CSS skin for JPlayer CirclePlayer
=======================

I liked the circleplayer a lot, but having to jump into photoshop to make new assets was a pain and too old-school.

I have recreated the base circle-player skin with pure css, making it far easier to reskin on the fly.

![CirclePlayer](https://github.com/mix3d/circleplayer/raw/master/screencaps/circleplayer2.png)


TODO: 
 - remove the fallback image and styles; if we're all CSS, it's all or nothing!
 - refactor style into SCSS for easy scaling / generating any size and color player.
 - a better font/asset for the play and pause? SVG, Font Awesome, etc? 
   - Pseudo classes can work, but can't get the hover effect easily
   - no dependancies is better
 - add new skin samples

**CirclePlayer readme.MD:**

----------------
 
CirclePlayer is a demo intended to showcase the jQuery HTML5 Media Library jPlayer
[https://github.com/happyworm/jPlayer](https://github.com/happyworm/jPlayer) 

[Try the latest version.](http://happyworm.com/jPlayerLab/circleplayer/)   

Uses HTML5 Audio, CSS3 Transforms (transform:rotate) hooks provided by : [https://github.com/lrbabe/jquery.rotate.js](https://github.com/happyworm/jPlayer)

A full browser fallback is planned, jPlayer provides the Flash HTML5 Audio fallback and the idea is to use a sprite map to display progress in non CSS3 compliant browsers. [http://modernizr.github.com/Modernizr/](http://modernizr.github.com/Modernizr/) could be used to check CSS3 transform:rotate compliance. 

Possibilities exist to enhance the demo with [https://wiki.mozilla.org/Audio_Data_API](https://wiki.mozilla.org/Audio_Data_API) for supporting browsers.

Note the progress bar will not function correctly in Opera 11 due to a JIT compiler bug in the Opera browser : [http://twitter.com/dstorey/status/28108260418523137](http://twitter.com/dstorey/status/28108260418523137) 

The demo's current look is heavily inspired by [http://forrst.com/posts/Untitled-CJz](http://forrst.com/posts/Untitled-CJz)       

Thanks to [Jussi Kalliokoski](http://twitter.com/quinnirill) for contributing.

CirclePlayer is dual-licensed under the GPL and MIT licenses

 
