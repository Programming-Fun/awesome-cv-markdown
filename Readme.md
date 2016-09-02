Awesome CV in markdown 
==============

A port of the latex [Awesome CV](https://github.com/posquit0/Awesome-CV) template to create an html version created using markdown and the [Pelican](https://github.com/getpelican/pelican) static website generator. 

# Features

* CSS styles for both web and print. Allows creation of PDF by simply printing the website. Avoids having to keep two different versions in sync.
* Can generate publication lists from BibTeX files (uses pybtex and my pelican-perpagepublications). This was an important feature for me so I would not loose the main advantage of creating the CV from LateX.
* CSS files are generated from SASS for much easier editing.

Requirements
============

* [Pelican](https://github.com/getpelican/pelican) with the `assests` plugin
* For rendering math formulas use the `render_math` pelican plugin
* If you want to have a publication list generated you will have to use my fork of `pelican-bibtex` called [`pelican-perpagepublications`]( https://github.com/cycomanic/pelican-perpagepublications)
* If you want to integrate counts of publications into your content use the `pelican-jinja2content` plugin


This project only contains the templates and style files to generate the CV, no other pelican theme files are included. 
