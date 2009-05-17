Phing tasks
===========

Just a simple collection of [phing](http://phing.info/trac/) tasks I've developed
to help with the day job.  

Installation
------------
Simply copy the appropriate task to a subfolder within the tasks folder of your local phing install.  On
my Ubuntu machine, the tasks folder is `/usr/share/php/phing/tasks`, within which I create a subfolder 
`/usr/share/php/phing/tasks/my` for hacking around with experimental phing tasks.  

When using a custom task, you will also need to register the new task using the
`taskdef` task within phing.  For instance:
	<taskdef name="mynewtask" classname="phing.tasks.my.MyNewTask" />

Further reading
---------------
If you're interested, there are a couple of short blog articles on each of these
tasks on my site [codeinthehole.com](http://codeinthehole.com):
- TwitterUpdateTask: [Phing task to update a Twitter status](http://codeinthehole.com/archives/14-Phing-task-to-update-Twitter-status.html)
- UnfuddleMessageTask: [Phing task to create an Unfuddle message](http://codeinthehole.com/archives/15-Phing-task-to-create-an-Unfuddle-message.html)
