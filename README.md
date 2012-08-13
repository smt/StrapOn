StrapOn (NEW!)
==============

StrapOn is a Responsive HTML Prototyping framework that uses the Serve gem to generate static websites using any number of tempating languages.

StrapOn is supported by:
-------------------------
* SASS
* Compass
* Susy (for semantically-friendly responsive grids)
* Serve (local webserver, sass compiler, template assembler, etc..)
* Ruby (runs all of these wonderful tools)
* ERB, Haml, HTML, Markdown, Textile (Your markup language of choice..)

Usage
-----
_Requirements:_
1. Ruby

_On first use:_
`$ bundle install` downloads all gem dependacies.

`$ rake StrapOn:start` Starts webserver at http://localhost:4000
ctrl+c Ends the web server process and generates a static version of the site at ./_site/

`$ rake StrapOn:export` generates a static version of the site at ./_site/ without starting the webserver

Changes
-------
* No longer using Jekyll as templating framework
* No longer useing Foreman to mange multiple processes
* Rake tasks manage server, and static site export
