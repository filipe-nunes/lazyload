TODO
====

* [PERF] Once processed, mark images as processed using a data-llp attribute. When looping images, remove the processed ones adding them to processedElements.
* [PERF] Stop listening to "scroll" when 0 elements remains, restart listening after content was added
* [SHOW] Add a readme. Declare that IE7 isn't supported + suggest a fallback.
* [SHOW] Create an index demo page. Change the images source in all demos.
* [FEAT] Support for the srcset attribute
* [FEAT] Support for the picture tag (populate source.src and source.srcset instead of img.src or img.srcset)
* [NERD] Convert to coffeeScript?