Stand Alone jQuery.Deferred
===========================

I've loocked through the available Promises/A implementations, and the one I liked the most was the jQuery one, so I decided to extract it form the jQuery source, to be able to use it when writing vanilla javascript (ie. chrome extensions), avoiding having to include the entire library.

This is an *almost* mindless extraction of the original code, but I made sure that all the oficial jQuery.Deferred unit tests were being passed, so this should be safe for production apps.

Only weights 8k minified, and should be way more easier with memory consumption too.
