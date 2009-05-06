Phing tasks
===========

Just a simple collection of [phing](http://phing.info/trac/) tasks.

Installation
------------
Simply copy the appropriate task to a subfolder within the tasks folder of your local phing install.  On
my Ubuntu machine, the tasks folder is `/usr/share/php/phing/tasks`, within which I create a subfolder 
`/usr/share/php/phing/tasks/my` for hacking around with phing.  

When using a custom task, you will also need to register the new task using the
`taskdef` task within phing.  For instace:
	<taskdef name="mynewtask" classname="phing.tasks.my.MyNewTask" />
