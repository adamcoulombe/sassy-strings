sassy-strings
=============

String Functions extension for SASS/Compass

These are mostly just SASS [functions pulled from Chris Eppsteins fork](https://github.com/chriseppstein/sass/blob/a07a585f8ec743b8b0948a824100ce7567447aca/lib/sass/script/functions.rb) of SASS. I've packaged them in a Compass extension to make them easy to use until SASS gets some string functions in the permanent API.

List of Functions
-----------------

* str_length(string) *eg.* `str-length("foo") => 3`
* str_insert(original, insert, index)