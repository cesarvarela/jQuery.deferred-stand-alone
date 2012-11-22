Stand alone jQuery.Deferred

I've loocked through the available Promises/A implementations, and the one I liked the best was the jQuery one, so I decided to extract it form the jQuery source, to be able to use it when writing vanilla javascript (ie. chrom extensions), avoiding having to include the entire javascript library.

This is an *almost* mindles extration of the code, but I made sure that all the oficial jQuery.Deferred unit test were being passed, so this should be secure for production.

