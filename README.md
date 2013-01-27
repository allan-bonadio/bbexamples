Articulated Vertebrae
=====================

### minimalist Backbone.js examples

All of these apps are in the ArticulatedVertebrae directory.  Each BB app is a single '.html' file that runs some simple app in JavaScript, for edification or amusement.  They should work anywhere; just make sure the three .js files are in the same directory with the same names.  

There are no other files; no .css or .sass or .mustache or any other kind of file: just JavaScript and jQuery and Underscore.js, which Backbone needs to run.  There is no AJAX. If you're looking for 'Ajax Applications', really you're talking about javascript web applications, javascript enabled DHTML web pages, Web 2.0 pages, all sortof the same thing.  And they don't need AJAX to be web applications, although 90% of the interesting ones do.

<table>
	<tr><th>program <th>
		Router? <th>View? <th>Model? <th>Collection? <th>
		notes
	
	<tr><td>justaview<td>
		.<td>view<td>.<td>.<td>
		bare minimum 'hello world' program, using a BB view
		
	<tr><td>justarouter<td>
		.<td>view<td>.<td>.<td>
		page showing #fragment inner pages, using a BB router.  and colors.
		
	<tr><td>helloworld<td>
		router<td>view<td>.<td>.<td>
		bare minimum BB view and router working together
		
	<tr><td>echo<td>
		.<td>.<td>model<td>.<td>
		a small app using nothing from BB but a Model class.  Not even routers or views!  Everything else done in regular html, js and jQuery.
		
	<tr><td>jrivers<td>
		.<td>.<td>model<td>.<td>
		a model-only page that's a bit more complex.  and fun.
		
	<tr><td>carnac<td>
		router<td>view<td>model<td>collection<td>
		It's mostly a simplified version of lostsoul's example app.  Took out Ajax and the need for a server.  Also took out jQuery.template and the nocss thing.
</table>


The juicy info is in the source comments in the .html files.  I'm assuming that you're a web programmer familiar with current JavaScript, and with jQuery, as I was, too, when I started.
<a href=http://backbonejs.org>Backbone</a> also uses 
<a href=underscore.js>underscore.js</a> .  

These programs are also somewhat rough - for instance, attributes without quotes, &lt;html&gt; tags omitted, all tricks you can get away with on all browsers, although it's considered sloppy.  This was done to simplify the files and avoid distractions.  You can copy my bad habits or not.

### 

These examples came about because I had to learn Backbone.js for my job.
From the start, I had a problem with it; why do we need all this complexity?
All of the examples, even the <i>simple</i> ones, seemed to have dozens of files and several other technologies, some that I'd never seen before, often with some sort of server application in whichever language/technolgy the author wrote in.
These are fine for the project they were intended for; just not good for getting up to speed quickly with Backbone.js.

Meanwhile, Backbone.js, as of the start of 2013, can be described as 'testy', meaning, you have to test after each little change you make to be sure you didn't break anything.  My attempts to start from an empty file and make a BB app were all failures.  Unless I can type in a 'hello world' program from memory, or set up a trivial example, I don't really believe that I 'know' a system.

Some of these are based (loosely) on the 'very simple backbone application' by 
<a href=mailto:lostsoul&#64;beyondtheclouds.net>lostsoul&#64;beyondtheclouds.net</a>.
Indeed, I made it simpler.  But without lostsoul, I would have been a lost soul as most of my attempts to write BB scripts from scratch did nothing.



