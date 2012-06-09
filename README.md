useful-bash-scripts
===================

These are some bash scripts I use to do stuff on my Mac.

boilerplate
--------------
Usage: `boilerplate myproject -s`
This copies a modified version of HTML5 Boilerplate into a new directory. In the future I will add other settings, like a popcorn boilerplate, etc.

serv
--------------
Usage: `serv myproject [-or]`
This copies a github directory into a folder I have set up with apache.
-or overwrites the older version, otherwise the older version is renamed with a timestamp.

lh
-------------
lh t1335    => Opens ticket 1335
lh -a     => Shows all tickets for popcorn maker
lh -n       => Opens a new ticket
lh -m       => Opens all tickets tagged templates. Specific to my workflow.
lh prep t1335 => Preps a pull request and associated things for templates. Specific to my workflow.
