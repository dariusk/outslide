# OutSlide

This is the source code to a program I wrote that takes a simple outline and turns it into a slide deck. It does this by grabbing the first Google Image Search result for each line of your outline, and slapping the image into an [impress.js](https://github.com/bartaz/impress.js/) slide deck with the text of the line itself on top. [You can see it in action here.](http://tinysubversions.com/outslide)

To run the Google Image Search, I use the (deprecated) [Google Image Search API](https://developers.google.com/image-search/v1/devguide), more or less copying [their hello world](https://developers.google.com/image-search/v1/devguide#hiworld).

OutSlide also features speech synthesis, provided by [speak.js](https://github.com/kripken/speak.js).

Finally, the version of [impress.js](https://github.com/bartaz/impress.js/) that I'm using here has been hacked horribly in order to enable the dynamic addition of slides.
