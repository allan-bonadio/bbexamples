Articulated Vertebrae
=====================

### small programs that articulate Backbone.js

These examples came about because I had to learn Backbone.js for my job.
From the start, I had a problem with it; why do we need all this complexity?
All of the examples, even the <i>simple</i> ones, seemed to have dozens of files and several other technologies, some that I'd never seen before, often with some sort of server application in whichever language/technolgy the author wrote in.
These are fine for the project they were intended for; just not good for getting up to speed quickly with Backbone.js.

Meanwhile, Backbone.js, as of the start of 2013, can be described as 'testy', meaning, you have to test after each little change you make to be sure you didn't break anything.  My attempts to start from an empty file and make a BB app were desperate and brutal.  Unless I can type in a 'hello world' program from memory, or set up a trivial example, I don't really believe that I 'know' a system.

I'm assuming that you're a web programmer familiar with current JavaScript, and with jQuery, as I was, too, when I started.
<a href=http://backbonejs.org>Backbone</a> also uses 
<a href=underscore.js>underscore.js</a> .  

Some of these are based (loosely) on the 'very simple backbone application' by 
<a href=mailto:lostsoul&#64;beyondtheclouds.net>lostsoul&#64;beyondtheclouds.net</a>.
Indeed, I made it simpler.  But without lostsoul, I would have been a lost soul as most of my attempts to write BB scripts from scratch did nothing.

All of the apps are in the ArticulatedVertebrae directory.  Each BB app has a '.html' file that runs the app; put them anywhere a server serves or you can just drag the file into a browser window.  Make sure the three .js files are in the same directory.  There are no other files; no .css or .sass or .mustache or any other kind of file: just JavaScript and jQuery and Understroke.js, which Backbone needs to run.

The first example is <b>helloworld</b>; as its name says it's the good old minimal page that uses Backbone.js.
Totally useless itself, but it shows the bare bare minimum BB stuff you need for every page/panel.  Plus some gotchas.
It uses backbone's Router and View classes, no others.

<b>jrivers</b> is a small app using nothing from BB but a Model class.  Not even routers or views!  Everything else done in regular html, js and jQuery.

The last example is <b>carnac</b>.  It's mostly a simplified version of lostsoul's example.



