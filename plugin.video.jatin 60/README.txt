For this to import the necessary modules you must make sure you have the
modules4all repo source added into your very own repo. If you've already used
the repository creator at http://totalrevolution.tv/create_repo.php then it will already be setup, if not
then use it to create a repo and copy the modules4all section into your own repo addon.xml.

<h3>ONCE ADD-ON IS INSTALLED:</h3>
Go through the default.py and read the comments for each section.
Enable each section in the Main_Menu() function one by one and start to see your add-on come to life!

<h3>ONCE ADD-ON IS INSTALLED:</h3>
Go through the default.py and read the comments for each section.
You'll see this is linked to a test XML file which is online but
there is also a locally stored XML file in the resources folder
and in the default.py you can use this if you prefer.

The comments in the Main_Menu() function are slightly more advanced and if
you have no interest in understanding how or why the code does what it does then
you can skip all of this and literally just start creating your XML files online.
This add-on is good to go straight out of the box, the only thing you need to edit
is the line 58 in default.py where the main_xml url is set - just set that to your
own URL and you have yourself a fully functional playlist add-on!

Basically if you don't have access to a server or don't have internet
access then you can set the local file to be your master xml file (for testing)
but when you push your add-on live you'll most likely want to have your files online
as it will make it very easy to update content. The add-on should never need updating
(unless you want to add new features), the only thing you'd need to update is your
online xml files.


<h3>Frequently Asked Questions:</h3>
Can I use this code commercially?
-- Please look at our TRMC system for commercial options: http://totalrevolution.tv