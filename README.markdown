Overview.
===

This is a fork of Krzystof Kowalczyk's FoFou forum software modified for my
own personal needs.

This code can be see live at [Terminally Incoherent Forums](http://forum.terminally-incoherent.com).

Original Project Information
===

For more info on the original project see: http://blog.kowalczyk.info/software/fofou/

Fofou (Forums For You) is a simple forum software inspired by
Joel On Software [forum software](http://discuss.joelonsoftware.com/?joel).

It's mostly a port of [FruitShow PHP forum](http://sourceforge.net/projects/fruitshow) to 
[Google App Engine](http://code.google.com/appengine/).

Where can I see it in action?
=============================

Forums for [Sumatra PDF viewer are powered by Fofou](http://blog.kowalczyk.info/forum_sumatra/)

Installation.
=============

Fofou runs on Google App Engine infrastructure. You need to get App Engine
account and upload fofou (see [AppEngine Documentation](http://code.google.com/appengine/docs/gettingstarted/uploading.html) 
for details).

Once installed, you can create one or more forums through web interface.

Deployment philosophy.
======================

Fofou isn't designed as a forum hosting platform for hosting hundreds of forums
for many people.

It's designed to host a few forums for one person so the owner of App Engine
account is implicitly an admin for all forums hosted from that account.

Design philosophy.
==================

You'll quickly see that Fofou differs in many ways from most common forum
software. There are good reasons for the differences and Joel Spolsky describes
those reasons [in great detail](http://www.joelonsoftware.com/articles/BuildingCommunitieswithSo.html)


License.
========

The python code is written completely by me and is in Public Domain.

Html/css/js files are mostly lifted from FuitShow, so they fall under
FruitShow's BSD license.

Contributing.
=============

Fofou is open-source so if you want to improve the code, contribute more skins
etc., fork http://github.com/kjk/fofou/tree/master and create pull request.
