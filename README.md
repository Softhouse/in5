# In 5 Website

This repo is the working copy of the website for Softhouse:s popular In five minute series where we summarise
important topics related to Software development.

The site is staticly generates using [Docpad](http://docpad.org/) 

## Setup
### Requirements
in order to work with this repo you need these softwares on your computer
* Bash 
* git
* node
* npm
* docpad
* cake

### Geting started
* clone the repo
* navigate to the root directory of the Repo. 
* Run `./setup`
* Run `docpad run `
* Open a browser and go to  [http://localhost:9778/in5/](http://localhost:9778/in5/)
* if you see the website all went well and you are ready to work with the content


### Edit a book

The books are written in markdown and the files containing the written content can be found in
`render/in5/books` and the pictures in `static/in5/img/`


###Custom Markdown

In order to enable a little more formatting than vanilla markdown allows we have added some custom things to the renderer
the cutomization is that a paragraph starting with a word starting with a dot  `.word Content` will render into ´<div class="word"> Content </div>`
instead of ´<p> .word Content </div>`
