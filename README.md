repl.it
=======

An online environment for interactively exploring programming languages, based
on [jsREPL](https://github.com/replit/jsrepl).

Current Languages
-----------------

* JavaScript Variants
  * JavaScript
  * CoffeeScript
  * Kaffeine
  * Move
  * JavaScript.next

* Esoteric
  * Bloop
  * Brainfuck
  * LOLCODE
  * Unlambda
  * Emoticon

* Classic
  * Quick Basic
  * Forth

* Serious
  * Scheme
  * Lua
  * Python
  * Ruby (beta)


Stackato
--------

To deploy to Stackato:

    stackato push -n

Stackato will download, configure and install the dependencies
for you, **so the following instructions should only be heeded
for local development**.


Getting the Code
----------------

    git clone --recursive git@github.com:Cloud-Apps/repl.it.git
    cd repl.it

Dependencies
------------

#### [node.js](http://nodejs.org/)  

#### [npm](http://npmjs.org/)

    curl https://npmjs.org/install.sh | sh
   
#### [CoffeeScript](http://jashkenas.github.com/coffee-script/)
  
  Using npm:
  
    npm install -g coffee-script

#### [Pygments](http://pygments.org/)

  Using easy_install:
  
    easy_install Pygments
    
  Using pip:
  
    pip install Pygments

Running repl.it
---------------

repl.it comes bundled with a static node HTTP file server and a CoffeeScript file watcher & (re)-compiler:

    ./server.js 8888
    
repl.it can then be opened at http://localhost:8888/index.html.

License
-------

repl.it is available under the MIT license. External libraries used in repl.it
may use other licenses. Please check each library for its specific license.
