Stand Alone jQuery.Deferred
===========================

Through all the available Promises/A implementations, the one I liked the most was the jQuery one, but when writing some vanilla javascript I've found overkill to include the entire jQuery library, so I decided to extract it form the jQuery source, and make an stand alone version.

This is an *almost* mindless extraction of the original code, but I made sure that all the oficial jQuery.Deferred unit tests were being passed, so this should be safe for production apps.

Only weights 8k minified, and should be more easier on the memory consumption too.

The jQuery.noConflict() has been preserved, in case you want to use the Deferreds with an older version of jQuery or another library that also uses the dollar sign.

(The extensions jQuery.extend, jQuery.Callbacks and jQuery.each also are contained in the source and avaible to use, since they are used internally by jQuery.Deferred)